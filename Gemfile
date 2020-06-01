# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0.rc1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.12'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'
gem 'travis', '~> 1.8', '>= 1.8.10'

# devise
gem 'devise'

# devise-jwt
gem 'devise-jwt', '~> 0.5.9'
gem 'dry-configurable', '0.9.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'spring-commands-rspec'
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails', '~> 2.7', '>= 2.7.5'
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 4.0.0.beta2'
  gem 'shoulda-matchers', '~> 4.1', '>= 4.1.2'
  gem 'rubocop', '~> 0.84.0', require: false
  gem 'rubocop-rails', '~> 2.5', '>= 2.5.2', require: false
  gem 'rubocop-performance', '~> 1.6', require: false
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'coveralls', require: false

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
