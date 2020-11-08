# Lyrical

Preview the Jekyll pages locally: https://help.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll

tl;dr

    rbenv local 2.6.3  # Jekyll requires Ruby >= 2.5.0
    gem install --user-install bundler
    bundle install
    bundle exec jekyll serve

Troubleshooting: Make sure that `~.gem/ruby/2.6.0/bin` is on the `PATH`.

The GitHub Jekyll themes can be found at https://github.com/pages-themes, in case you need to customize it.
