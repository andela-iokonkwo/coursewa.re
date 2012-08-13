source 'https://rubygems.org'

gem 'rails'
gem 'haml-rails'
gem 'jquery-rails'
gem 'puma'
gem 'sorcery'
gem 'delayed_job_active_record'
gem 'gettext_i18n_rails'
gem 'roadie'
gem 'cancan'
gem 'public_activity', :github => 'pokonski/public_activity', :branch => '0.4.0-wip'
gem 'friendly_id'
# Speedup a bit things
gem 'multi_json'
gem 'oj'

group :production do
  gem 'pg'
end

group :development do
  gem 'sqlite3'
  gem 'yard'
  gem 'gettext', :require => false
  gem 'ruby_parser', :require => false
end

group :assets do
  gem 'uglifier'
  gem 'therubyracer'
  gem 'sass-rails'
  gem 'compass-rails'
  gem 'zurb-foundation', '~> 3.0.1'
end

group :development, :test do
  gem 'ffaker'
  gem 'fabrication'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'rspec-rails'
  gem 'letter_opener'
  gem 'shoulda-matchers'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'email_spec'
  gem 'simplecov', :require => false
end
