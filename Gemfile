source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'rails', '~> 6.1.3', '>= 6.1.3.2'

gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'jbuilder', '~> 2.7'
gem 'redis', '~> 4.0'
gem 'bcrypt', '~> 3.1.7'
gem 'image_processing', '~> 1.2'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'bootsnap', '>= 1.4.4', require: false
gem 'rack-cors'
gem 'activerecord-nulldb-adapter'
gem 'groupdate'
gem 'pghero'
gem 'rollbar'
gem 'dotenv-rails'

# API Framework
gem 'grape'
gem 'grape-entity'
gem 'grape-middleware-logger'
gem 'grape_on_rails_routes'
gem 'hashie-forbidden_attributes'
gem 'grape-swagger'
gem 'grape-swagger-entity'
gem 'grape-swagger-rails'
gem 'grape-swagger-representable'

# Authentication
gem 'devise'
gem 'jwt'

# Deploying and debugging
gem 'awesome_rails_console'
gem 'daemons'
gem 'delayed_job_active_record'
gem 'api-pagination'
gem 'kaminari'
gem 'rest-client'
gem 'parallel', '~> 1.19', '>= 1.19.1'

group :development, :test, :staging do
  gem 'faker'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'fuubar'
  gem 'guard-rspec'
  gem 'rspec-rails'
  gem 'simplecov', require: false
  gem 'simplecov-cobertura', require: false
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'spring'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'rename'
  gem 'rubocop', require: false
  gem 'rubocop-performance'
  gem 'rubocop-rails'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'rspec_junit_formatter'
end
