source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.2.0'
gem 'puma', '~> 3.11'
gem 'rack-timeout', '~> 0.5'
gem 'jbuilder', '~> 2.5'
gem 'pg', '~> 1.0'
gem 'redis', '~> 4.0'
gem 'sidekiq', '~> 5.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails', '~> 4.3'
gem 'turbolinks', '~> 5'
gem 'bootstrap-sass', '~> 3.3'
gem 'font-awesome-rails', '~> 4.7'
gem 'tzinfo-data'


group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'rack-mini-profiler', '~> 1.0'
  gem 'web-console', '~> 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

