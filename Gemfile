source "https://rubygems.org"

# GitHub Pages側には既に入っているのでコメントアウト
#gem "jekyll", "~> 4.3.2"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# テーマ
# gem "minima", "~> 2.5"
# https://github.com/just-the-docs/just-the-docs
gem "just-the-docs"

# プラグイン
group :jekyll_plugins do
  # gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-last-modified-at'
end
