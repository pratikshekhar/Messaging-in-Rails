source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.4'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem "devise"
gem "auto_html"
gem 'acts_as_votable', '~> 0.10.0'
gem 'faker'

gem 'rake', '< 11'

# design
gem "font-awesome-rails"
gem 'bourbon'
gem 'neat'
gem 'refills'
gem "normalize-rails"

gem 'sdoc', '~> 0.4.0', group: :doc


group :development, :test do
    gem 'rspec-rails', '~> 3.0.0'
    gem "factory_bot_rails"
    gem 'capybara'
    gem 'database_cleaner'
    gem 'shoulda-matchers'
    gem 'faker'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
