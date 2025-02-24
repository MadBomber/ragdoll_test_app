# ragdoll_test_app/Gemfile

source "https://rubygems.org"

gem "rails", "~> 8.0.1"       # Full-stack web application framework.
gem "pg"                      # Pg is the Ruby interface to the PostgreSQL RDBMS


gem "propshaft"               # Deliver assets for Rails.
gem "puma", ">= 5.0"          # A Ruby/Rack web server built for parallelism.
gem "importmap-rails"         # Use ESM with importmap to manage modern JavaScript in Rails without transpiling or bundling.
gem "turbo-rails"             # The speed of a single-page web application without having to write any JavaScript.
gem "stimulus-rails"          # A modest JavaScript framework for the HTML you already have.
gem "jbuilder"                # Create JSON structures via a Builder-style DSL
gem "solid_cache"             # A database backed ActiveSupport::Cache::Store
gem "solid_queue"             # Database-backed Active Job backend.
gem "solid_cable"             # Database-backed Action Cable backend.

gem "ragdoll", path: "../ragdoll"  # Local path to the ragdoll engine

gem "bootsnap", require: false  # Boot large ruby/rails apps faster
gem "kamal", require: false     # Deploy web apps in containers to servers running Docker with zero downtime.
gem "thruster", require: false  # Zero-config HTTP/2 proxy


group :development, :test do
  gem 'debug_me'                  # A tool to print the labeled value of variables.
  gem "brakeman", require: false  # Security vulnerability scanner for Ruby on Rails.
  gem 'annotate'                  # Annotates Rails Models, routes, fixtures, and others based on the database schema.
  gem "rubocop-rails-omakase", require: false  # Omakase Ruby styling for Rails
end

group :development do
  gem "web-console"    # A debugging tool for your Ruby on Rails applications.
end

group :test do
  gem 'rspec-rails'                           # RSpec for Rails
  gem "capybara"                              # Capybara aims to simplify the process of integration testing Rack applications, such as Rails, Sinatra or Merb
  gem "selenium-webdriver", require: false    # Selenium is a browser automation tool for automated testing of webapps and more
end
