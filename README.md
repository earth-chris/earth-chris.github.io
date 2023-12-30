# earth-chris.github.io

My personal website, portfolio, and blog.

## Running the local web server

```bash
bundle exec jekyll serve
```

## Setup

Install linux dependencies:

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
```

Set up Ruby defaults:

```bash
echo '# Ruby gem install paths' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/.gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

Jekyll install:

```bash
gem install jekyll bundler
```

I recently had to create an alias because recent bundler installs add a version number to the `bundle` executive.

```bash
alias bundle=bundle2.7
```
