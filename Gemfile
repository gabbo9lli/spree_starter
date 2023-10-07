source 'https://rubygems.org'

ruby '2.7.2' #prod
#ruby '3.2.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.1.4', '>= 6.1.4.1' #prod
#gem 'rails', '~> 7'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1' #prod
#gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6' #prod
#gem 'sass-rails'

gem 'jbuilder', '~> 2.7' #prod

# Use Uglifier as compressor for JavaScript assets
# gem 'uglifier'
# gem 'terser'

#gem 'bootsnap', require: false

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.16'

# Use Puma as the app server
gem 'puma', '~> 5.0'
#gem 'puma'

gem 'awesome_print', '~> 1.9.2'

group :development, :test do
  # gem 'dotenv-rails', '~> 2.1', '>= 2.1.1'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  # gem 'spring'

  gem 'listen', '~> 3.7.1'

  # gem 'rspec_junit_formatter'

  # monitoring
  gem 'bullet', '~> 7.0.1'
  gem 'rack-mini-profiler', '~> 2.3.3', require: false
  # gem 'flamegraph'
  # gem 'stackprof'
  # gem 'memory_profiler'

  # gem 'webmock'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 4.2'

  # gem 'letter_opener'
end

group :test do
  gem 'vcr'
end

# Heroku fix
group :production do
  gem 'rack-timeout'
  gem 'font_assets'
end

# file uploades & assets
gem 'aws-sdk-s3', require: false

# caching
# gem 'dalli' # memcache
gem 'rack-cache', '~> 1.13' # http caching

# sidekiq
gem 'sidekiq', '~> 6'
gem 'nokogiri', '~> 1.13'

git 'https://github.com/gabbo9lli/spree.git', branch: 'retebio_43' do
  gem 'spree'
  gem 'spree_sample'
  gem 'spree_emails'
  gem 'spree_backend'
  gem 'spree_frontend'
end
# gem 'spree', path: '..' #prod
# gem 'spree_frontend', path: '../frontend' #prod
# gem 'spree_emails', path: '../emails' #prod
# gem 'spree_sample', path: '../sample' #prod
# gem 'spree_backend', path: '../backend' #prod
# gem 'spree_auth_devise', '~> 4.3' #prod
# gem 'spree_gateway', '~> 3.9' #prod
# gem 'spree_i18n', '~> 5.0' #github: 'spree-contrib/spree_i18n', tag: 'v5.0.0' #branch: 'main' #prod

# Spree gems
# gem 'spree', '~> 4.5'
#gem 'spree', path: 'spree_43'
#gem 'spree_sample', '~> 4.5'
#gem 'spree_sample', path: 'spree_43/sample'
# gem 'spree_emails', '~> 4.5'
#gem 'spree_emails', path: 'spree_43/emails'
# gem 'spree_backend', '~> 4.5'
#gem 'spree_backend', path: 'spree_43/backend'
gem 'spree_gateway', '~> 3.9'
# gem 'spree_frontend'
#gem 'spree_frontend', path: 'spree_43/frontend'
# gem 'spree_auth_devise', '~> 4.5'
gem 'spree_auth_devise', '~> 4.3'
# gem 'spree_i18n', '~> 5.1'
gem 'spree_i18n', '~> 5.0'
gem 'spree_dev_tools', require: false, group: %w[test development]

# Sentry Client
gem 'sentry-raven'

# Scout Client
# gem 'scout_apm'

# Rack CORS Middleware
gem 'rack-cors'

# SendGrid
# gem 'sendgrid-actionmailer'

# logging
# gem 'remote_syslog_logger'

# gem 'activerecord-nulldb-adapter'

# improved JSON rendering performance
gem 'oj'

# Fix SCSS errors with Ruby 3 on MacOS
gem 'sassc', github: 'sass/sassc-ruby', group: :development
