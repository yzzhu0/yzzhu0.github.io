source "https://rubygems.org"

# Plain Jekyll 4 instead of the github-pages gem (which pins Jekyll 3.9 and
# does not run on Ruby >= 3.2). The site is built by .github/workflows/jekyll.yml.
gem "jekyll", "~> 4.4"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jemoji"
end

gem "kramdown-parser-gfm"
gem "webrick" # for `jekyll serve`
