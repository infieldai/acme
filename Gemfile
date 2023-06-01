# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.1'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 5.2'

gem 'pg'
gem 'sequel', require: false
gem 'sqlite3'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma', '~> 5.0'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'jbuilder', '~> 2.7'

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Application gems
gem 'bootstrap_form'
gem 'cancancan'
gem 'httpparty', '< 0.19.0'
gem 'pagy', '< 6'
gem 'redcarpet', '~> 2'
gem 'octokit'
gem 'jwt'
gem 'faraday-retry'
gem "ruby-openai"
gem 'sidekiq', '6.5.8'

gem 'devise'
gem 'omniauth', "< 2"
gem "omniauth-rails_csrf_protection"

# Error reporting
gem "sentry-ruby"
gem "sentry-rails"

gem 'sprockets-rails'

# Tools gems
gem 'roo'

group :development, :test do
  gem 'dotenv-rails'
  gem 'rspec-rails'
  # Start debugger with binding.b [https://github.com/ruby/debug]
  gem 'debug', '>= 1.0.0', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'pry'
  gem 'pry-remote'
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
  # Extracting `assigns` and `assert_template` from ActionDispatch
  gem 'rails-controller-testing'
end
