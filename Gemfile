source 'http://rubygems.org'

gem 'rails', '~> 3.1.10'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'uglifier'
  gem 'compass', '>= 0.12.alpha.0'
end

gem 'jquery-rails'
gem 'rails-backbone'

gem 'devise', '1.4.7'
gem 'cancan'
gem 'transitions', '0.0.9', :require => ["transitions", "active_record/transitions"]

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'sqlite3'
  gem 'factory_girl_rails'
  gem 'jasmine', '1.1.0'
end
