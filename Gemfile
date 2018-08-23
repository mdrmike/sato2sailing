source 'https://rubygems.org'
ruby RUBY_VERSION
# This Gemfile is used by the `bundler` package manger to manage the version of
# Jekyll and any plugins used and to ensure dependencies are met.
# First, be sure you have the latest verion of bundler: `gem update bundler`

# If you want to use a different version of Jekyll or a plugin (aka gem),
# add/edit it below, save the file, and run `bundle install`.
# Also, after running `bundle install`, use bundler to run the jekyll server
# like this:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
# gem 'jekyll', '3.2.1'


# Add plugins (AKA gems) to jekyll_plugins group
# Use github-pages gem to ensure local development is the same as Github pages.
# Note github-pages, is a meta package that includes many gems available.
# More info:
#       Github-pages: https://github.com/github/pages-gem
#       List of gems included: https://pages.github.com/versions/
#
# To use these plugins, be sure to enable them by editing `_config.yml`
# then adding them to the `plugins` section.
# For example, edit `_config.yml` to include:
#
# plugins:
#   - jemoji
#   - jekyll-titles-from-headings
#
# Also note, some are enabled by default, such as, `jekyll-sitemap`.
gem 'github-pages', '~> 185', group: :jekyll_plugins


# Add plugins to development group
# A few suggested gems for local development or when not using github pages
#     To use, uncomment, then run `bundle install [--with=GROUP[ GROUP...]]`
#     --with=<list> is A  space-separated  list of groups referencing gems to
#        install. If an optional group is given it is installed. If a group is
#        given that is in the remembered list of groups given to --without, it
#        is removed from that list.
#
# Example: bundle install --with development
#gem 'jekyll-admin', require: false, group: :development
gem 'bootstrap-sass', require: false, group: :development
# Add to older version of sass to development group to ensure its available when
# generating sourcemaps using compass 1.0.3 (:bug: with 3.5.x branch)
# see `assets/style.scss` for details
gem 'sass', '~> 3.4.25', group: :development
gem 'compass', '~> 1.0.3', group: :development

# Add gems to travis group
# About Travis CI: http://jekyllrb.com/docs/continuous-integration/
#gem 'html-proofer', group: :travis
#gem 'scss_lint', require: false, group: :travis

# If you have any plugins, put them here!
group :jekyll_plugins do
end

group :travis do
end

group :development, optional: true do
end
