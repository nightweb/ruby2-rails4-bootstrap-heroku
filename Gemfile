source 'https://rubygems.org'

ruby '2.1.1'
gem 'rails', '4.0.3'

# Servers
gem 'puma'
gem 'unicorn'

# Multi-environment configuration
# gem 'simpleconfig'

# API
# gem 'rabl'

# ORM
gem 'pg'

# Performance and Exception management
# gem 'airbrake'
# gem 'newrelic_rpm'

# Security
# gem 'secure_headers'

# Miscellanea
# gem 'google-analytics-rails'
gem 'haml'
# gem 'http_accept_language'
gem 'jquery-rails'
# gem 'resque', require: 'resque/server' # Resque web interface

# Assets
gem 'coffee-rails', '~> 4.0.0'
gem 'haml_assets'
gem 'i18n-js'
gem 'jquery-turbolinks'
gem 'sass-rails', '~> 4.0.0'
gem 'turbolinks'
gem 'twbs_sass_rails'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'byebug'
  gem 'delorean'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'pry'
  gem 'pry-byebug'
  gem 'pry-rails'
end

group :development do
  gem 'bullet'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
end

group :test do
  gem 'capybara'
  gem 'coveralls', require: false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'launchy'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webmock', require: false
end

group :staging, :production do
  gem 'rails_12factor'
end
