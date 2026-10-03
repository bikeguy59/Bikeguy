source "https://rubygems.org"

# Matches the Jekyll version and plugins GitHub Pages uses to build the site.
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Windows and JRuby do not include zoneinfo files.
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", platforms: [:windows]
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
gem "webrick", "~> 1.8"
