# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.4.4'
# Use Puma as the app server
gem 'puma', '~> 5.3.1'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5'
gem 'activerecord-import'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.4.3'
# Use jquery as the JavaScript library
gem 'bootstrap', '~> 4.5.0'
gem 'bootstrap-datepicker-rails'
gem 'bootstrap_form'
gem 'font-awesome-rails'
gem 'paper_trail'
gem 'jquery-rails'
gem 'jquery-ui-rails'

gem 'spreadsheet', '1.0.4'

gem 'nested_form'
gem 'jquery-validation-rails'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0.1'
gem 'redis-store'
gem 'sidekiq', '~> 5.2', '>= 5.2.7'
gem 'airbrake', '~> 8.3', '>= 8.3.2'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.13'


## authentication and authorization ##
gem 'cancancan'
gem 'devise'

## multi language ##
gem 'globalize', '~> 5.3.0'
# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false
gem 'rack',  '>= 2.2.0'
gem 'hirb'
gem 'serviceworker-rails', git: 'https://github.com/arvind-reddoorz/serviceworker-rails.git'


group :development do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]

  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'web-console', '>= 3.3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'dotenv-rails'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry'
  gem 'letter_opener'
  gem 'bullet', group: 'development'
  gem 'rack-mini-profiler', require: false
  gem "foreman"
  gem 'brakeman'
  ##3 for capistrano ##
  gem 'capistrano',         require: false
  gem 'capistrano-rvm',     require: false
  gem 'capistrano-rails',   require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano3-puma',   require: false

  gem 'net-ssh', '>= 6.0.2'
  gem 'ed25519', '>= 1.2', '< 2.0'
  gem 'bcrypt_pbkdf', '>= 1.0', '< 2.0'
  ##3 for capistrano end##

end

group :test do
  gem 'rspec-rails', ">= 3.9.0"
  gem 'shoulda', '~> 3.5'
  gem 'shoulda-matchers'
end


gem 'carrierwave-base64'
gem 'prawn'
gem 'prawn-table', '~> 0.1.0'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

gem 'jquery-datatables'
gem 'will_paginate-bootstrap4'

gem 'select2-rails'

## for request options
gem 'rack-cors'

# for doc upload
gem 'carrierwave', '~> 2.1.1'
gem 'fog-aws'

# state management 
gem 'aasm'


# for google maps
gem 'breadcrumbs_on_rails'

## for send data
gem 'httparty', '~> 0.15.6'

gem 'ckeditor', '5.0.0'
gem 'newrelic_rpm'

gem 'geocoder'
gem 'rack-attack'
gem 'material_icons'

gem 'time_diff'
gem 'validates_zipcode'

gem 'rotp'
gem 'active_model_otp'

gem 'jwt'
gem 'sshkey'
