source 'https://rubygems.org'

gem 'rails', '3.2.3'
gem 'jquery-rails', '~> 2.0.0'
gem 'sass-rails',   '~> 3.2.4'
gem 'bcrypt-ruby', '~> 3.0.1'

#gem 'bootstrap-sass', '~> 2.0.2' # twitter bootstrap framework
gem 'bootstrap-sass', :git => 'git://github.com/thomas-mcdonald/bootstrap-sass.git', :branch => '2.0.3'
#gem 'faker', '~> 1.0.1' # generate test data
gem 'will_paginate', '~> 3.0.3' # multiple pages for indexes
gem 'bootstrap-will_paginate', '~> 0.0.7' # use bootstrap styling for paging
#gem 'redcarpet', '~> 2.1.1' # markdown
#gem 'paperclip', '~> 3.0.2' # uploads
#gem 'aws-sdk', '~> 1.3.4' # storage
#gem 'acts-as-taggable-on', '~> 2.2.2' # tags
#gem 'recaptcha', require: 'recaptcha/rails'
gem 'thin', '~> 1.3.1' # faster server
#gem 'friendly_id', '~> 4.0.1' # friendly urls

group :development, :test do
	# gem 'eventmachine', '1.0.0.beta.4.1' # for thin locally / commented out for heroku
	gem 'sqlite3'
	gem 'rspec-rails', '~> 2.9.0'
end

group :development do
	# gem 'annotate', :git => 'git://github.com/jeremyolliver/annotate_models.git', :branch => 'rake_compatibility'
end

group :assets do
  gem 'coffee-rails', '~> 3.2.2'
  gem 'uglifier', '>= 1.2.3'
end

group :production do
	gem 'pg', '~> 0.12.2'
end