# frozen_string_literal: true

source 'https://rubygems.org'

gem "bootstrap", "~> 5.2"
gem "webrick", "~> 1.7"

gem 'jekyll', '~> 4'

gem 'faraday-retry', '~> 2.2'
gem 'kramdown-parser-gfm'
gem 'webrick'

group :jekyll_plugins do
  gem 'jekyll-github-metadata', '~> 2.16'
  gem 'jekyll-sitemap'
  gem 'just-the-docs'
end

source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins


group :development, :test do
  gem 'axe-core-capybara'
  gem 'axe-core-rspec'
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'rack'
  gem 'rackup'
  gem 'rspec'
  gem 'selenium-webdriver'
end

group :development, :rubocop do
  gem 'rubocop', require: false
  gem 'rubocop-capybara', require: false
  gem 'rubocop-rspec', require: false
end
