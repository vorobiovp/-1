source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'breadcrumbs_on_rails'
gem 'meta-tags'
gem 'activestorage', '~> 6.0', '>= 6.0.3.4'
gem 'bootstrap-sass', '~> 3.4.1'
gem 'coffee-rails', '~> 4.2'
gem 'faker', git: 'https://github.com/faker-ruby/faker.git', branch: 'master'
gem 'jbuilder', '~> 2.7'
gem 'jquery-rails'
gem 'oj'
gem 'oj_mimic_json', '~> 1.0', '>= 1.0.1'
gem 'pq'
gem 'puma', '~> 4.1'
gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
gem 'sass-rails', '>= 6'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>=1.3.0'


group :development, :test do
  gem 'database_cleaner'
  gem 'factory_bot', '~> 5.2'
  gem 'pg', '~> 1.1'
  gem 'pry'
  gem 'rails-controller-testing'
  gem 'rb-readline'
  gem 'rspec-json_expectations', '~> 2.2'
  gem 'rspec-rails', '~> 4.0', '>= 4.0.1'
  gem 'rails-helper', '~> 0.1.0'
end

group :development do
  gem 'listen'
  gem 'web-console', '>=3.3.0'
end

group :test do
  gem 'capybara'
  gem 'db-query-matchers'
  gem 'json_spec'
  gem 'launchy'
  gem 'rubocop', require: false
  gem 'shoulda-matchers', '~> 4.4', '>= 4.4.1'
  gem 'webdrivers'
  gem 'webpacker', github: 'rails/webpacker'

end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
