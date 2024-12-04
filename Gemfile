source "https://rubygems.org"

# Core Framework and Database
gem "rails", "~> 7.2.2"
gem "pg" # PostgreSQL as the database
gem "puma", ">= 5.0" # Web server

# Rails Utilities
gem "importmap-rails" # JavaScript imports
gem "turbo-rails" # SPA-like page accelerator
gem "stimulus-rails" # JavaScript framework
gem "jbuilder" # JSON API builder

# Manage environment variables
group :development, :test do
  gem "dotenv-rails" # Manage .env files only in development and test
end

# Optional Features
gem "sprockets-rails" # Asset pipeline
# gem "bcrypt", "~> 3.1.7" # Secure password handling
# gem "redis", ">= 4.0.1" # Action Cable in production
# gem "image_processing", "~> 1.2" # Active Storage support

# Development and Testing
group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false # Security vulnerability scanner
  gem "rubocop", require: false # Ruby style and linting
  gem "rubocop-rails", require: false # Additional Rails-specific linting rules
end

group :development do
  gem "web-console" # Debugging in development
  gem "error_highlight", ">= 0.4.0", platforms: [:ruby] # Error location hints
end

group :test do
  gem "capybara" # System testing
  gem "selenium-webdriver" # Browser automation
end

# For Windows compatibility
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Caching and Performance
gem "bootsnap", require: false # Reduces boot times

# GitHub API Client
gem "octokit" # For GitHub API interaction

# Stringio
gem "stringio", "~> 3.1"