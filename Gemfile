# Specify the source for Ruby gems
source "https://rubygems.org"

# Define the version of Jekyll
gem "jekyll", "3.9.3"

# Specify gems for the :jekyll_plugins group, which is for development-related plugins
group :jekyll_plugins do
  # Generate a sitemap for your Jekyll site
  gem 'jekyll-sitemap', "~> 1.4.0"
  
  # Generate an Atom feed for Jekyll posts
  gem "jekyll-feed", "~> 0.15.1"
  
  # Generate SEO-related meta tags
  gem 'jekyll-seo-tag', "~> 2.8.0"
  
  # Add autoprefixer to your styles
  gem "jekyll-autoprefixer", "~> 1.0"
end

# Specify gems used for Markdown parsing, emoji rendering, XML processing, and Sass
gem 'kramdown', "~> 2.3.2"
gem 'kramdown-parser-gfm', "~> 1.1.0"
gem 'liquid', "~> 4.0.4"
gem 'jemoji', "~> 0.12.0"
gem 'nokogiri', "~> 1.15.2"
gem 'sass', "~> 3.7.4"

# Use the WEBrick HTTP server for local development
gem "webrick", "~> 1.8"

# Interface to JavaScript runtime (for ExecJS)
gem "execjs", "2.7.0"

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
