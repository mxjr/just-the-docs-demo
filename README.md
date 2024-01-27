# Just the Docs

[Just the Docs](https://just-the-docs.github.io/just-the-docs) is a theme for
generating static websites with [Jekyll](https://jekyllrb.com/).  You can
write source files for your web pages using Markdown, the Liquid templating
language, and HTML.  Jekyll builds your site by converting all files that have
front matter to HTML.

To build this site locally install the necessary dependencies:

    $ sudo apt-get install -y g++ gcc make ruby ruby-bundler ruby-dev

and use `bundler` to install Jekyll:

    $ bundle config set --local path "vendor/bundle"
    $ bundle install

then build the site using `jekyll` by running:

    $ bundle exec jekyll build

To serve the site:

    $ bundle exec jekyll serve

To clean the generated files:

    $ rm -Rf .jekyll-cache _site
    $ rm -Rf Gemfile.lock vendor

## References

[Just the Docs](https://just-the-docs.github.io/just-the-docs)  
<https://github.com/just-the-docs/just-the-docs>  
[Just the Docs Template](https://github.com/just-the-docs/just-the-docs-template)  
[Jekyll](https://jekyllrb.com/)  
[The Raspberry Pi Guide](https://raspberrypi-guide.github.io/)  
<https://github.com/raspberrypi-guide/raspberrypi-guide.github.io>  

