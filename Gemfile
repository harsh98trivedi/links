# GEMFILE FOR JEKYLL
source "http://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# gem "jekyll"
gem "jekyll", "~> 4.3.4"
gem "thin"

# This is the default theme for new Jekyll sites. You may change this to anything you like.

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
    gem "jemoji", "~> 0.8"
    gem "jekyll-timeago", "~> 0.13.1"
    gem "jekyll-sitemap"
    gem "jekyll-feed" # = 0.17.0
    gem "jekyll-github-metadata" # = 2.16.1
    gem "jekyll-include-cache" # = 0.2.1
    gem "jekyll-paginate" # = 1.1.0
    gem "jekyll-redirect-from" # = 0.16.0
    gem "jekyll-remote-theme" # = 0.4.3
    gem "jekyll-seo-tag" # = 2.8.0
end
    
gem "rack"
  
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", "~> 1.2"
    gem "tzinfo-data"
end
  
# Performance-booster for watching directories on Windows
gem "wdm" if Gem.win_platform?
