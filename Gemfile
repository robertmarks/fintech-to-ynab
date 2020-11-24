ruby '2.7.1'

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 6'
gem 'puma'

gem 'f2ynab', github: 'syncforynab/f2ynab'
# gem 'f2ynab', path: '../f2ynab'

# Utilities
gem 'awesome_print'
gem 'commander'

group :development, :test do
  gem 'listen'
  gem 'dotenv-rails'
  gem 'rubocop-rails_config'
end

group :test do
  gem 'rspec-rails'
  gem 'codecov'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
