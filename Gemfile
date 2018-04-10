source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails'
gem 'puma'
gem 'sass-rails'
gem 'uglifier'
gem 'webpacker'
gem 'coffee-rails'
gem 'turbolinks'
gem 'jbuilder'
gem 'pg', group: :production
gem 'slim-rails'

group :development, :test do
  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'foreman'
  gem 'minitest-reporters'
end
