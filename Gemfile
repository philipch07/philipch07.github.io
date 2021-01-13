source "https://rubygems.org"

# if you change files, run:
# `bundle update`
# `bundle install`
# and finally,
# `bundle exec jekyll serve` 
# to run the website.
gem "jekyll", "~> 4.2.0"

# gem "jekyll-theme-console" <- was my original theme, but I decided to remove using gem themes
# since I am customizing my own theme. (https://jekyllrb.com/docs/themes/)

# if using GitHub pages, remove "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15.1"
  gem "jekyll-seo-tag", "~> 2.7.1"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

