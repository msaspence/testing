source 'https://rubygems.org'

ruby "2.2.4"

gem 'rails', '~> 4.0.0'

gem 'unicorn'


# Storage
# gem 'pg'
gem 'activerecord'
gem 'carrierwave-mongoid', :require => 'carrierwave/mongoid'
gem 'dalli'
gem 'encryptor'
gem 'faker'
gem "fog"
gem 'delayed_job_mongoid'
gem 'delayed_job'
gem 'serverengine'
gem 'memcachier'
gem 'mongoid', '~> 4.0.0'
gem 'moped', '~> 2.0.0'
gem 'retina_rails'

# Auth
gem 'devise'
gem 'devise-doorkeeper'
gem 'doorkeeper-mongodb', github: 'doorkeeper-gem/doorkeeper-mongodb'
gem 'cancancan'
gem 'oauth2'
gem 'switch_user'
gem 'h2ocube_rails_puma', '0.0.3'

# Background processing
gem 'daemons'
gem 'thread'

# Formatting
gem 'haml-rails'
gem 'draper'
gem 'formtastic', github: 'justinfrench/formtastic', ref: '1bdf6d3642af52a1a62902f12b844a5856d0254e'
gem 'formtastic-bootstrap', git: 'https://github.com/msaspence/formtastic-bootstrap.git' # https://github.com/mjbellantoni/formtastic-bootstrap/pull/61
gem 'redcarpet'
gem 'liquid'
gem 'ruby-progressbar'
gem 'time_difference'
gem 'psych'
gem 'mini_magick'

# Views
gem 'activated_ui'
gem 'kaminari'

# CSS
gem 'libv8'
gem 'therubyracer', '~> 0.12.1'
gem 'less-rails', '2.3.3'
gem 'twitter-bootstrap-rails', '2.2.6'

# Emails
gem 'roadie-rails'

# JavaScript
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-cookie-rails'
gem 'jquery-payment-rails', github: 'digitalopera/jquery-payment-rails' # Dependencies of gem dont allow for rails 4
gem 'momentjs-rails'
gem 'gon', github: 'gazay/gon' # Waiting for https://github.com/gazay/gon/pull/152 to be released
gem 'chosen-rails'
gem 'backbone-on-rails'
gem 'bootstrap-datetimepicker-rails'
gem 'd3-rails'

# Monitoring
gem 'hirefire-resource'
gem 'librato-metrics'
gem 'newrelic_moped'
gem 'newrelic_rpm'
gem 'rack-mini-profiler', github: 'MiniProfiler/rack-mini-profiler' # contains a fix for Rails engines, waiting for 0.9.4
gem 'sentry-raven'

# 3rd Party Data
gem 'timezone'
gem 'geocoder'
gem 'guess'
gem 'rest-client'
gem 'currencies'
gem 'pismo'
gem 'restforce'
gem 'zendesk_api'
gem 'mixpanel_client'

# 3rd Party Services
gem 'stripe-rails'
gem 'customerio'
gem 'trakio-ruby', '~> 0.2.2', require: 'trakio/client'
gem 'mandrill-api', require: 'mandrill'
gem 'analytics-ruby', '~> 2.0.0'

gem 'spinjs-rails'
gem 'haml_coffee_assets'
gem 'execjs'
gem 'uglifier', '>= 1.0.3'
gem 'os'

group :development do
  gem 'capistrano'
  gem 'capistrano-chef'
  gem 'capistrano-rails',   require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-gitslave'
  gem 'net-ssh', '2.7.0' # Bug in 2.8 with authentication and capistrano

  gem 'quiet_assets'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'at'
  gem 'ruby-prof'
  gem 'letter_opener'
  gem 'mailcatcher'
end

group :test do
  gem 'database_cleaner'
  gem 'fuubar'
  gem 'launchy'
  gem 'machinist'
  gem 'machinist-mongoid'
  gem 'mongoid-rspec', require: false
  gem 'rspec-rails'
  gem 'rspec-its'
  gem 'shoulda-matchers', '~> 2.7.0', require: false
  gem 'stripe-ruby-mock'
  gem 'test-unit'
  gem 'timecop'
  gem 'webmock'
end

group :development, :test, :staging do
  gem 'pry'
  gem 'pry-stack_explorer'
end

# gem 'trak_core', path: File.join('../../Gems','core'), require: 'trak_core'
# gem 'trak_core', git: 'https://trakio:7D455BD26403971608BB566A2E485D91624CCE29B8C1952275E82AFF4DA3E6DF@bitbucket.org/trakio/core.git'
