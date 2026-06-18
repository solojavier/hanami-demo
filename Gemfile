# frozen_string_literal: true

ruby file: ".ruby-version"

source "https://rubygems.org"

gem "hanami", "3.0.0.rc1"
gem "hanami-assets", "3.0.0.rc1"
gem "hanami-action", "3.0.0.rc1"
gem "hanami-db", "3.0.0.rc1"
gem "hanami-router", "3.0.0.rc1"
gem "dry-validation", "~> 1.0"
gem "hanami-view", "3.0.0.rc1"

gem "dry-types", "~> 1.7"
gem "dry-operation", ">= 1.0.1"
gem "puma"
gem "rake"
gem "sqlite3"

group :development do
  gem "hanami-webconsole", "3.0.0.rc1"
end

group :development, :test do
  gem "dotenv"
  gem "rouge"
end

group :cli, :development do
  gem "hanami-reloader", "3.0.0.rc1"
end

group :cli, :development, :test do
  gem "hanami-rspec", "3.0.0.rc1"
end

group :test do
  # Database
  gem "database_cleaner-sequel"

  # Web integration
  gem "capybara"
  gem "rack-test"
end
