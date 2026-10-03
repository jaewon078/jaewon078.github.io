# Only needed to preview the site locally (`bundle exec jekyll serve`).
# GitHub Pages builds the site itself; you don't need this to publish.
#
# Mirrors what GitHub Pages runs (Jekyll 3.10 + its default plugins). We don't
# use the `github-pages` gem because it doesn't support Ruby 4 yet.
source "https://rubygems.org"

gem "jekyll", "~> 3.10"
gem "kramdown-parser-gfm"
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end

# Newer Ruby versions no longer bundle these, but Jekyll 3 needs them.
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "ostruct"
