# https://mirrormirrorontheweb.github.io/wii

A mirror of the complete guide to modding your Nintendo Wii (and Wii mini).

https://mirrormirrorontheweb.github.io/wii

## Running the site locally

This requires the following installed on your system:
- ruby(-dev)
- bundler

To test the website locally, simply run the following commands:
```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --incremental
```
The website should now be running on http://127.0.0.1:4000/.
