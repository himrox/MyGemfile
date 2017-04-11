source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'bootstrap-sass', '3.3.6'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'puma', '~> 3.0'
gem 'rails', '5.0.2'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'brakeman', :require => false
  gem 'byebug', platform: :mri
  gem 'factory_girl_rails'
  gem 'pry-byebug'
  gem 'pry-doc'
  gem 'pry-rails'
  gem 'pry-stack_explorer'
  gem 'rspec-rails', '~> 3.5'
  gem 'sqlite3'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara', '~> 2.12', '>= 2.12.1'
  gem 'database_cleaner', '~> 1.5', '>= 1.5.3'
  gem 'faker', '~> 1.7', '>= 1.7.3'
  gem 'launchy', '~> 2.4', '>= 2.4.3'
  gem 'rails-controller-testing'
  gem 'selenium-webdriver', '~> 3.2', '>= 3.2.1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
