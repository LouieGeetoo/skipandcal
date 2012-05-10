source 'https://rubygems.org'

gem 'rails', '3.2.3'
gem 'jquery-rails', '~> 2.0.0'
gem 'bcrypt-ruby', '~> 3.0.1'

gem 'will_paginate', '~> 3.0.3' # multiple pages for indexes
gem 'redcarpet', '~> 2.1.1' # markdown
#gem 'paperclip', '~> 3.0.2' # uploads
#gem 'aws-sdk', '~> 1.3.4' # storage
gem 'thin', '~> 1.3.1' # faster server
gem 'friendly_id', '~> 4.0.1' # friendly urls

group :development, :test do
	# gem 'eventmachine', '1.0.0.beta.4.1' # for thin locally / commented out for heroku
	gem 'sqlite3'
	gem 'rspec-rails', '~> 2.9.0'
end

group :assets do
	gem 'sass-rails',   '~> 3.2.4'
  gem 'coffee-rails', '~> 3.2.2'
  gem 'uglifier', '>= 1.2.3'
  gem 'zurb-foundation', '~> 2.2.1'
end

group :production do
	gem 'pg', '~> 0.12.2'
end