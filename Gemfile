source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


#base
gem 'rails', '~> 5.1.6'
#database
gem 'mysql2', '>= 0.3.18', '< 0.6.0'
#server
gem 'puma', '~> 3.7'

#view
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
# gem 'therubyracer', platforms: :ruby
gem 'jbuilder', '~> 2.5'
gem 'bootstrap'
gem 'jquery-rails'
gem 'popper_js'
gem 'tether-rails'

gem 'devise'
gem 'sidekiq'
gem 'sinatra'
gem 'redis'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'database_cleaner'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rubocop'
  gem 'annotate'
  gem 'overcommit'
end
