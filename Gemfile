source "https://rubygems.org"

# GitHub Pages gem for automatic Jekyll version compatibility
gem "github-pages", group: :jekyll_plugins

# Uncomment the following line if you need to specify a different version for local development
# gem "jekyll", "~> 4.3.2"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
end

# Optional gems for performance or Windows-specific features
platforms :mingw, :x64_mingw, :mswin do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
