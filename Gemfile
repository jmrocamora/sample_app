source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.5'

gem 'turbolinks'

gem 'bootstrap-sass'

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

gem 'faker'

gem 'will_paginate'
gem 'bootstrap-will_paginate'


group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
end

# Gems used only for assets and not required 
# in production environments by default. 
group :assets do
	# Use SCSS for stylesheets
	gem 'sass-rails', '~> 5.0'
	# Use Uglifier as compressor for JavaScript assets
	gem 'uglifier', '>= 1.3.0'
	# Use CoffeeScript for .coffee assets and views
	gem 'coffee-rails', '~> 4.1.0'
end

# Use jquery as the JavaScript library
gem 'jquery-rails'

group :test, :development do
  gem 'rspec-rails', '~> 3.0'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'spork'
end

group :test do
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'
end

group :production do
  gem 'pg'
end