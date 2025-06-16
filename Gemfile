# frozen_string_literal: true

source "https://rubygems.org"

# Use github-pages gem for GitHub Pages builds
if ENV['JEKYLL_ENV'] == 'github-pages'
  gem 'github-pages', group: :jekyll_plugins
else
  gemspec

  # Additional dependencies for CI/CD
  gem 'faraday-retry'
end
