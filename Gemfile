source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.1'
gem 'pg'
gem 'puma', '~> 3.0'
gem 'react_on_rails'

group :development, :test do
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'rubocop'
  gem 'reek', '~> 4.1'
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-remote', require: 'pry-remote'
  gem 'pry-nav'
  gem 'pry-stack_explorer'
  gem 'rails-erd'
  gem 'dotenv-rails'
  gem 'bullet'
end

group :development do
  gem 'foreman'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-bundler'
  gem 'guard-rubocop'
  # gem 'guard-reek', github: 'etison/guard-reek'
  gem 'terminal-notifier'
  gem 'terminal-notifier-guard'
  gem 'airborne'
end
