source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'
gem 'rake', '0.8.7'
gem 'sqlite3'
gem 'haml'

group :production do
  gem 'pg'
  gem 'therubyracer-heroku'
end

group :development do
  # To use debugger
  # gem 'ruby-debug19', :require => 'ruby-debug'
 
  # Use unicorn as the web server
  gem 'unicorn'

  # Deploy with Capistrano
  # gem 'capistrano'

  gem 'sqlite3'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end
