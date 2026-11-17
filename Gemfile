source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '4.0.9'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'jbuilder', '~> 2.7'
gem 'ostruct'
gem 'pg', '~> 1.3.5'
gem 'puma', '~> 7.2'
gem 'rack-cors'
gem 'rails', '8.0.5.2'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'brakeman', require: false
  gem 'debug', '>= 1.11.1'
  gem 'factory_bot_rails', '6.5.1'
  gem 'faker', require: false
  gem 'rspec-rails', '8.1.0'
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
end

group :test do
  gem 'capybara', '>= 3.40'
  gem 'simplecov', '>= 1.3.2', require: false
end

group :development do
  gem 'web-console', '>= 4.1.0'
end
