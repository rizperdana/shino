source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'rails', '~> 6.1.3', '>= 6.1.3.2'

gem 'bootsnap', require: false
gem 'business_time'
gem 'coffee-rails'
gem 'jbuilder'
gem 'paranoia'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma'
gem 'rails_admin'
gem 'sass-rails'
gem 'turbolinks'
gem 'uglifier'
gem 'sequenced'
gem 'ancestry'
gem 'pdfkit'
gem 'mimemagic', git: 'https://github.com/mimemagicrb/mimemagic', ref: '64b60d1'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
gem 'activerecord-nulldb-adapter'
gem 'groupdate'
gem 'pghero'
gem 'rollbar'
gem 'dotenv-rails'
gem 'grape'
gem 'grape-entity'
gem 'grape-middleware-logger'
gem 'grape_on_rails_routes'
gem 'hashie-forbidden_attributes'
gem 'grape-swagger'
gem 'grape-swagger-entity'
gem 'grape-swagger-rails'
gem 'grape-swagger-representable'
gem 'devise'
gem 'doorkeeper'
gem 'oauth2'
gem 'wine_bouncer'
gem 'awesome_rails_console'
gem 'daemons'
gem 'delayed_job_active_record'
gem 'api-pagination'
gem 'kaminari'
gem 'rest-client'
gem 'fcm'
gem 'google-cloud-storage', require: false
gem 'image_processing'
gem 'mail'
gem 'parallel', '>= 1.19.1'
gem 'prometheus-client'
gem 'rack-cors'
gem 'whenever', require: false
gem 'veritrans'
gem 'rails_admin_material'

group :development, :test, :staging do
  gem 'faker'
end

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'fuubar'
  gem 'guard-rspec'
  gem 'rspec-rails'
  gem 'simplecov', require: false
  gem 'simplecov-cobertura', require: false
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'listen'
  gem 'rename'
  gem 'rubocop', require: false
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'rspec_junit_formatter'
end
