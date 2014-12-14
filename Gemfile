source 'https://rubygems.org'


gem 'rails', '4.1.8'
gem 'pg'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
#gem 'coffee-rails', '~> 4.0.0'
#gem 'therubyracer',  platforms: :ruby

gem 'jquery-rails'
#gem 'turbolinks'
#gem 'jbuilder', '~> 2.0'
#gem 'sdoc', '~> 0.4.0',          group: :doc

gem 'spring',        group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

gem "activeadmin", github: "gregbell/active_admin" # Until it's 1.0.0
gem "devise"

# API time
gem "active_model_serializers"
gem "grape"
gem "grape-active_model_serializers"
gem "grape-swagger-rails"
gem "rack-cors", require: "rack/cors"

group :development do
  gem "better_errors"
  gem "meta_request"
  gem "quiet_assets"
end

group :development, :test do
  gem "capybara"
  gem "capybara-screenshot"
  gem "database_cleaner"
  gem "factory_girl_rails"
  gem "faker"
  gem "poltergeist"
  gem "pry-nav"
  gem "pry-rails"
  gem "pry-stack_explorer"
  gem "pry-theme"
  gem "rspec-rails"
  gem "rubocop"
  gem "shoulda-matchers"
  gem "spring-commands-rspec"
end