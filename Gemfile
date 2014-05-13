source 'https://rubygems.org'

#Framework and dependencies
gem 'rails', '3.2.14'
gem 'mailchimp-api'
gem 'foreman'

# Front-End
gem 'bootstrap-sass', '~> 3.0.2.0'
gem 'jquery-rails'

group :assets do
  gem 'compass-rails'
  gem 'sass-rails',      '~> 3.2.3'
  gem 'coffee-rails',    '~> 3.2.1'
  gem 'uglifier',        '>= 1.0.3'
end

group :development, :test do
  gem 'capybara'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'zonebie'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'brakeman'
  gem 'bundler-audit'
  gem 'metric_fu'
  gem 'rb-fsevent', '~> 0.9.1'
  gem 'quiet_assets'
  gem 'rubocop'
  gem 'ruby_gntp' # also install growlnotify from the Extras/growlnotify/growlnotify.pkg in Growl disk image
end

group :test do
  gem 'faker'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'launchy'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'simplecov-rcov-text', require: false
  gem 'spork'
end

gem 'coveralls', require: false
