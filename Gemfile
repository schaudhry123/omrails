source 'https://rubygems.org'

gem 'rails', '4.0.0'
gem 'jquery-rails'
gem 'devise'
gem 'turbolinks'
gem 'simple_form'
gem 'paperclip', github: 'thoughtbot/paperclip', branch: 'rails-4'

group :production do
	gem 'pg'
end

gem 'rails_12factor', group: :production

group :development, :test do
  gem 'sqlite3'
end

group :assets do
	gem 'sass-rails', '~> 4.0.0'
	gem 'coffee-rails', '~> 4.0.0'
	gem 'uglifier', '>= 1.3.0'
	gem 'bootstrap-sass', '~> 2.3.2.1'
	gem 'jbuilder', '~> 1.2'
end

group :doc do
  gem 'sdoc', require: false
end