source 'https://rubygems.org'

gem 'rails', '3.2.9'
gem 'haml-rails'
gem 'coffee-filter'

gem 'sqlite3'

group :assets do
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  gem 'uglifier', '>= 1.0.3'
end
gem 'jquery-rails'

group :test do
  gem 'rspec-rails'

  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'

  gem 'poltergeist'

  gem 'guard-rspec'
  gem 'guard-cucumber'
  gem 'guard-spork'
  gem 'rb-inotify'
end
gem 'listen', :github => 'guard/listen', :branch => 'linux_events'

group :production do
  gem 'unicorn'
  gem 'pg'
end
