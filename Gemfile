# frozen_string_literal: true
source 'https://rubygems.org'

gem 'active_data', git: 'https://github.com/pyromaniac/active_data.git'
gem 'analytics-ruby', require: 'segment'
gem 'config'
gem 'deltaforce-demo', git: "https://github.com/feelepxyz/dependabot-demo.git"
gem 'draper', '~> 3.1.0'
gem 'faraday', '~> 0.15.4'
gem 'faraday_middleware', '~> 0.13.1'
gem 'ffaker', require: false
gem 'google-api-client', '~> 0.28.4'
gem 'granite', '~> 0.9.0'
gem 'icalendar', '~> 2.3'
gem 'jbuilder', '~> 2.8.0'
gem 'lograge'
gem 'mail', '~> 2.6.6', require: %w[mail mail/parsers]
gem 'memoist', '~> 0.16.0'
gem 'newrelic_rpm'
gem 'pg', '~> 1.1.4'
gem 'phonelib'
gem 'puma', require: false
gem 'rack-cors' # client portal
gem 'rack', '2.0.6'
gem 'rails', '5.2.2.1'
gem 'rails-controller-testing'
gem 'redis-namespace'
gem 'redis-rails'
gem 'redlock'
gem 'rollbar'
gem 'sdoc', '~> 1.0.0', group: :doc
gem 'simple_form', '~> 4.1.0'
gem 'slim-rails'
gem 'stoplight', '~> 2.0'
gem 'twilio-ruby', '~> 5.21.2'
gem 'typhoeus'
gem 'tzinfo', '~> 1.2'
gem 'tzinfo-data', '>= 1.2018.9' # timezone db, keep the version synchronized with Platform / Giorgio
gem 'validates_email_format_of', '1.6.3'
gem 'warden', '~> 1.2'
gem 'sidekiq-postpone', '~> 0.3.1', require: false

source 'https://gems.contribsys.com/' do
  gem 'sidekiq-pro'
end

group :development do
  # for database download from S3
  gem 'aws-sdk', '~> 3.0'
end

group :development, :test do
  gem 'brakeman', require: false
  gem 'eventmachine', '1.2.7', require: false
  gem 'factory_bot_rails', '~> 5.0.1'
  gem 'foreman', require: false
  gem 'fuubar'
  gem 'guard-rspec', require: false
  gem 'pry-byebug'
  gem 'pry-doc'
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'rubocop-rspec', require: false
  gem 'slim_lint', '>= 0.7.0', require: false
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'terminal-notifier-guard', require: false
end

group :test do
  gem 'equivalent-xml', require: false
  gem 'json_spec', require: false
  gem 'nokogiri-pretty', require: false
  gem 'shoulda-matchers', require: false
  gem 'simplecov', require: false
  gem 'vcr', require: false
  gem 'watir-rails', require: false
  gem 'watir-rspec', require: false
  gem 'watirsome', require: false
  gem 'webmock', require: false
  gem 'pact', require: false
  gem 'test-prof', require: false
end

group :test, :integration do
  gem 'timecop', require: false
end
