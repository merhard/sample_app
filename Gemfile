source 'https://rubygems.org'
ruby File.read('.ruby-version').chomp

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

gem 'pg', '0.17.0'

gem "haml-rails", "~> 0.4"

gem 'simple_form'

gem 'bootstrap-sass', '2.3.2.0'

group :development, :test do
  gem 'rspec-rails', '2.13.1'
  gem 'pry-rails'
  gem 'pry-plus'
  gem 'guard-rspec', '2.5.0'
  gem 'spork-rails', '4.0.0'
  gem 'guard-spork', '1.5.0'
  gem 'childprocess', '0.3.9'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request' # enables use of rails panel extension in chrome
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'factory_girl_rails'
  gem 'launchy'
  gem 'growl', '1.0.3'
  gem "simplecov", "0.7.1", require: false
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :production do
  gem 'rails_12factor', '0.0.2'
end

# Use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
