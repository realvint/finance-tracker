source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.2'

gem 'rails', '~> 6.1.7', '>= 6.1.7.4'

gem 'devise', '~> 4.9.2'
gem 'puma', '~> 5.0'
gem 'slim', '~> 4.1'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 5.0'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'sqlite3', '~> 1.4'
end

group :development do
  gem 'letter_opener', '~> 1.7'
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
  gem 'slimcop', require: false
  gem 'slim_lint', require: false
  gem 'web-console', '>= 4.1.0'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver', '>= 4.0.0.rc1'
  gem 'webdrivers'
end
