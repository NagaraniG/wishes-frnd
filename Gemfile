source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.2.1'

# gem to load environment variables from .env
gem 'dotenv-rails', '2.5.0'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

# Use Puma as the app server
gem 'puma', '~> 3.7'

# Use SCSS for stylesheets
gem 'sass-rails', '5.0.7'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '4.2.2'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

# delayed for mailer
gem 'delayed_job_active_record'
gem 'daemons'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'


# for database
gem 'pg', '0.18'

# Use jquery as the JavaScript library
gem 'jquery-rails'

gem 'paperclip', '5.0.0'

gem 'friendly_id', '5.2.3'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'pry', '0.10.4'

  # Spring speeds up development by keeping application running in background.
  gem 'letter_opener', '1.4.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

    # Helps find unused routes and controller actions
  gem 'traceroute', '0.5.0'

  # Helps to kill N+1 queries and unused eager loading
  gem 'bullet', '5.5.1'

  # Helps to analysis security vulnerability
  gem 'brakeman', '3.6.1'

  # Ruby static code analyzer
  gem 'rails_best_practices', '1.18.0'
  gem 'rubocop', '0.48.1', require: false

  # Code quality reporter
  gem 'rubycritic', '3.2.0', require: false

end
