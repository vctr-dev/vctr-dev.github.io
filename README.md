## Setup Jekyll (Mac OSX)

These set of instructions are a summary from [Github](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)

1. Check ruby version using `ruby --version`. Make sure it is higher than `2.1.0`.
2. Use either `gem install bundler` to install bundler. If there are permission errors, consider either changing the folder permission of the folder described in the error message, or use `sudo gem install bundler`.
3. Navigate to the root of this project.
4. Run `bundle install`. This is to install the gem group described in the `Gemfile`.

## Upgrade Jekyll (Mac OSX)

If the pages produced by local Jekyll looks different than on Github, it could be that the local version of Jekyll is out of date.

To update Jekyll, run `bundle update`. This will update all gems in the `Gemfile`.

## Serve Jekyll locally (Mac OS)

Run `bundle exec jekyll serve` to serve the pages locally on [https://localhost:4000](https://localhost:4000).