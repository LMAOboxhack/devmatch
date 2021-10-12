source 'https://rubygems.org'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.2.4.3'
# Use Puma as the app server
gem 'puma', '4.3.9'
# Use SCSS for stylesheets
gem 'sass-rails', '5.0.7'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '4.2.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '4.2.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Use jquery as the JavaScript library
gem 'jquery-rails', '~> 4.4'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5.2', '>= 5.2.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.10'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '3.1.7'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Twitter Bootstrap library for frontend UI & layout
gem 'bootstrap', '~> 4.5'

# Popper gem for Bootstrap dependencies
gem 'popper_js', '~> 1.16'

# Use Font Awesome for icon library
gem 'font-awesome-sass', '~> 5.13'

# Use Hirb for better database visual representation in the console
gem 'hirb', '0.7.3'

# Use devise gem for managing user accounts, handling user authentication
gem 'devise', '4.7.2'

# Use Stripe for payment processing
gem 'stripe', '5.22.0'

# Use Figaro for ENV variables
gem 'figaro', '1.1.1'

# Use AWS SDK for Active Storage
gem 'aws-sdk-s3', '~> 1'

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '1.3.13'
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
  gem 'pg', '0.18.4'
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
ruby '2.7.1'