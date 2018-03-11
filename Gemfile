source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.5'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'turbolinks', '~> 5.1'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'dotenv-rails', '~> 2.2', '>= 2.2.1'
gem 'devise', '~> 4.4', '>= 4.4.1'
gem 'milia', '~> 1.3', '>= 1.3.1'
gem 'twitter-bootstrap-rails', '~> 4.0'
gem 'devise-bootstrap-views', '~> 0.0.11'
gem 'modernizr-rails', '~> 2.7', '>= 2.7.1'
gem 'simple_form', '~> 3.5', '>= 3.5.1'
gem 'bootstrap-datepicker-rails', '~> 1.7', '>= 1.7.1.1'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'




group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'activerecord-session_store', github: 'rails/activerecord-session_store'