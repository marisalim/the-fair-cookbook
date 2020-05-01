# The FAIR Cookbook

## Running Locally

### Setup
```bash
# Setup python environment
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt

# Setup Ruby environment
bundle config set path 'vendor/bundle'
bundle install

# Setup jupyter book
make install
```

### Using
```bash
# compile book with
make book

# serve book locally with
make serve
```

## Modifying things

- `content/**/*`: The actual pages rendered as HTML but can be written in `*.md` or `*.ipynb`
- `_data/toc.yml`: Configure the relative level of content as seen in the sidebar

