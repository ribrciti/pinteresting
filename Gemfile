source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.1.2'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'bootstrap-sass'
gem 'devise', '~> 3.1.0.rc2'
gem 'paperclip', github: 'thoughtbot/paperclip'
gem 'masonry-rails', '~>0.2.0'
gem 'will_paginate', '~> 3.0'
gem 'will_paginate-bootstrap'

group :development, :test do
	gem 'sqlite3'
end

group :production do
	gem 'pg'
	gem 'rails_12factor'
end

group :doc do
	#bundle exec rake doc:rails generates the API under doc/api
	gem 'sdoc', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]
