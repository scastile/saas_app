source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '7.2.3.1'
# Use Puma as the app server
gem 'puma', '~> 6.4'
# Use SCSS for stylesheets
# Use SCSS for stylesheets (if using Sprockets)
gem 'sassc-rails', '~> 2.1'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '3.0.0'
# Use jQuery as the JavaScript library
gem 'jquery-rails', '4.1.1'
# Turbo Drive for fast navigation (replaces Turbolinks in Rails 7)
gem 'turbo-rails'
# Build JSON APIs with ease
gem 'jbuilder', '~> 2.11'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Twitter Bootstrap library for front-end UI and layout
gem 'bootstrap-sass', '3.4.1'

# Use Font Awesome sass gem for adding icons
gem 'font-awesome-sass', '4.6.2'

#Use Hirb gem for better database view in console
gem 'hirb', '0.7.3'

# Use Devise for user authentication
gem 'devise', '~> 4.9'

# Use Stripe for payment processing
gem 'stripe', '1.48.0'

#Use Figaro  for ENV variables
gem 'figaro', '~> 1.2'

# Use Active Storage for file uploads (Rails 7 default, replaces Paperclip)

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '2.0.0'
end

group :production do
  # Use the PostgreSQL gem for Heroku production servers
  gem 'pg', '~> 1.5'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
ruby '>= 3.0.0'
