source 'http://rubygems.org'

gem 'rake'
gem 'sinatra'
gem 'rack'
gem 'activerecord', '4.0.2'

gem 'unicorn'

group :production do
  gem 'mysql2'
end
group :test do
  gem 'database_cleaner'
  gem 'capybara'
  gem 'rspec'
  gem 'cucumber-sinatra'
  gem 'cucumber'
end

group :development do
  gem 'sqlite3'
  gem 'shotgun'
  gem 'capistrano'
  gem 'capistrano-bundler'
end
