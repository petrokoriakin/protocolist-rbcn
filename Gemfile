source 'https://rubygems.org'
ruby '1.9.3'

gem 'rails',     github: 'rails/rails'
gem 'journey',   github: 'rails/journey'
gem 'arel',      github: 'rails/arel'
gem 'activerecord-deprecated_finders', github: 'rails/activerecord-deprecated_finders'

gem 'pg'
gem 'thin'
gem 'newrelic_rpm', github: 'artfuldodger/rpm'
#gem 'protocolist', github: 'pyotrkoryakin/protocolist'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sprockets-rails', github: 'rails/sprockets-rails'
  gem 'sass-rails',   github: 'rails/sass-rails'
  gem 'coffee-rails', github: 'rails/coffee-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', platforms: :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

gem 'xpath'
gem 'spork'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

group :test do
	gem 'rspec-rails'
	gem 'factory_girl_rails'
  gem 'cucumber-rails'
  gem 'capybara'
  gem 'database_cleaner'
end

group :test, :development do
	gem 'sqlite3'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano', group: :development

# To use debugger
# gem 'debugger'
