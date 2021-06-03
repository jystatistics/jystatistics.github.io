# Thinkgs to do

- Update the main page

- Update the CV (with R markdown)

- Update the blogs post

- Update teaching (upload the material) & Publication

# Notes for me

Info about which pages to edit is in _pages/markdown.md_

Change content of main landing page in _pages/about.md_

Change sidebar content in _config.yml_

Change how sidebar shows up in _includes/author-profile.html_

To run the site locally, run bundle exec jekyll serve

# Reference website for this webpage template

See more info at https://academicpages.github.io/

More information from this website: https://github.com/cduvallet/cduvallet.github.io

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

