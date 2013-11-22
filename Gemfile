source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
	gem 'rails', '4.0.0.rc2'
	gem 'jquery-rails'
	gem 'devise'
	gem 'simple_form', "3.0.0.rc"
	gem "paperclip", :git => "git://github.com/thoughtbot/paperclip.git"
	gem 'aws-sdk'
	gem 'faker'
	gem 'will_paginate', '~> 3.0'
	gem 'bootstrap-will_paginate'
	gem 'turbolinks'

group:production do
	gem 'pg'

end

group:development, :test do
	gem 'sqlite3'
end

gem 'sass-rails', '~> 4.0.0.rc2'

gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.0.0'

gem 'bootstrap-sass', '~> 2.3.2.1'

gem 'rails_12factor', group: :production

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

gem 'jbuilder', '~> 1.2'

group :doc do

# bundle exec rake doc:rails generates the API under doc/api.
  
  gem 'sdoc', require: false
end