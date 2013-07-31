source 'https://rubygems.org'


gem 'rails', '4.0.0'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
end

#Gem used only for assets and not required
# in production environment by default.
group :assets do
  gem 'sass-rails', '~> 4.0.0'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.0.0'
end

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :test do
  
  #This gem allows us to simulate user's interaction with the application
  gem 'capybara'
  
end

group :production do
  gem 'pg'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
