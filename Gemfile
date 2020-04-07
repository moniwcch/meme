source 'https://rubys.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Bundle edge Rails instead:  'rails', github: 'rails/rails'
 'rails', '~> 6.0.2', '>= 6.0.2.2'
 'sqlite3', '~> 1.4'
# Use Puma as the app server
 'puma', '~> 4.1'
# Use SCSS for stylesheets
 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
#  'redis', '~> 4.0'
# Use Active Model has_secure_password
#  'bcrypt', '~> 3.1.7'

# Use Active Storage variant
#  'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  'sqlite3', '~> 1.4'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
   'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
   'web-console', '>= 3.3.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
   'capybara', '>= 2.15'
   'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
   'webdrivers'
end
#  group :production do
#   gem 'pg' 
#   end

# Windows does not include zoneinfo files, so bundle the tzinfo-data 
 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
