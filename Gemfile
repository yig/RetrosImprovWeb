source "https://rubygems.org"
gem "github-pages", group: :jekyll_plugins

ruby '~> 3.4.0'

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "webrick"

# Claude: Your error is happening because Jekyll 4.3.3 needs the csv library, which was removed from Ruby's standard library in Ruby 3.4.0 (you're using that version). The csv gem now needs to be explicitly included.
# Same seems true for "base64".
gem "csv"
gem "base64"
