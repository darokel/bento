# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'image_processing', '~> 1.2'
gem 'inline_svg', '~> 1.7', '>= 1.7.1'
gem 'oj', '~> 3.10'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.1'
gem 'rack-attack', '~> 6.3'
gem 'rack-canonical-host', '~> 1.0'
gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
gem 'recipient_interceptor', '~> 0.2'
gem 'redis', '~> 4.0'
gem 'redis-namespace', '~> 1.7'
gem 'redis-rack-cache', '~> 2.2'
gem 'sass-rails', '>= 6.0.0'
gem 'sidekiq', '~> 6.0'
gem 'turbolinks', '~> 5'
gem 'tzinfo-data', '~> 1.2', platforms: %i[mingw mswin x64_mingw jruby]
gem 'view_component', '~> 2.19', require: 'view_component/engine'
gem 'webpacker', '~> 5.1', '>= 5.1.1'

group :development do
  gem 'letter_opener', '~> 1.7'
  gem 'listen', '~> 3.2'
  gem 'rack-mini-profiler', '~> 2.0', require: false
  gem 'spring', '~> 2.1'
  gem 'spring-commands-rspec', '~> 1.0'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 4.0.4'
end

group :development, :test do
  gem 'action-cable-testing', '~> 0.6', '>= 0.6.1'
  gem 'awesome_print', '~> 1.8'
  gem 'bullet', '~> 6.1'
  gem 'bundler-audit', '>= 0.5.0', require: false
  gem 'byebug', '~> 11.1', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails', '~> 2.7', '>= 2.7.6'
  gem 'factory_bot_rails', '~> 6.1', '>= 6.1.0'
  gem 'i18n-tasks', '~> 0.9', '>= 0.9.31'
  gem 'mock_redis', '~> 0.24'
  gem 'pry-byebug', '~> 3.9'
  gem 'pry-rails', '~> 0.3'
  gem 'rspec_junit_formatter', '~> 0.4'
  gem 'rspec-rails', '~> 4.0', '>= 4.0.1'
  gem 'rubocop', '~> 0.86'
  gem 'rubocop-performance', '~> 1.6', require: false
  gem 'rubocop-rails', '~> 2.6', require: false
  gem 'rubocop-rspec', '~> 1.40', require: false
end

group :test do
  gem 'capybara', '~> 3.33', '>= 3.33.0'
  gem 'codeclimate-test-reporter', '~> 1.0'
  gem 'formulaic', '~> 0.4', '>= 0.4.1'
  gem 'launchy', '~> 2.5'
  gem 'selenium-webdriver', '~> 3.142'
  gem 'shoulda-matchers', '~> 4.3'
  gem 'simplecov', '0.17.1', require: false
  gem 'site_prism', '~> 3.4', '>= 3.4.2'
  gem 'timecop', '~> 0.9'
  gem 'vcr', '~> 6.0'
  gem 'webdrivers', '~> 4.4', '>= 4.4.1'
  gem 'webmock', '~> 3.8'
end

group :production do
  gem 'cloudflare-rails', '~> 0.6', '>= 0.6.0'
  gem 'rack-timeout', '~> 0.6'
  gem 'rails_12factor', '0.0.3'
end
