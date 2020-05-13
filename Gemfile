# A sample Gemfile
source "https://rubygems.org"

gem "rails", "~> 5.0", ">= 5.0.0"


gem 'sass-rails', '>= 5.0.6'
gem 'less-rails', '>= 3.0.0'
gem 'uglifier', '>= 1.0.3'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby


gem 'jquery-rails', '>= 4.3.1'
gem 'select2-rails'
gem 'rails_tokeninput', '>= 1.7.0'
gem 'bootstrap-datepicker-rails', '>= 1.7.1.1'
gem 'date_time_attribute'
gem 'rails-assets-listjs', '0.2.0.beta.4' # remember to maintain list.*.js plugins and template engines on update
gem 'i18n-js', '~> 3.0.0.rc8'
gem 'rails-i18n', '>= 5.0.0'

gem 'mysql2'
gem 'prawn'
gem 'prawn-table'
gem 'haml', '~> 4.0' # some breaking changes in version 5, remove this line again when fixed
gem 'haml-rails', '>= 1.0.0'
gem 'kaminari'
gem 'simple_form', '>= 3.5.0'
gem 'inherited_resources', '>= 1.7.2'
gem 'localize_input', git: "https://github.com/bennibu/localize_input.git"
gem 'daemons'
gem 'twitter-bootstrap-rails', '~> 2.2.8'
gem 'simple-navigation', '~> 3.14.0' # 3.x for simple_navigation_bootstrap
gem 'simple-navigation-bootstrap', '>= 1.0.2'
gem 'ransack', '>= 1.8.4'
gem 'acts_as_tree'
gem 'rails-settings-cached', '= 0.4.3' # caching breaks tests until Rails 5 https://github.com/huacnlee/rails-settings-cached/issues/73
gem 'resque', '>= 1.27.4'
gem 'thin', '>= 1.5.1'
gem 'whenever', require: false # For defining cronjobs, see config/schedule.rb
gem 'protected_attributes', '= 1.1.0' # 1.1.0 until tests work work with higher versions
gem 'ruby-units'
gem 'attribute_normalizer'
gem 'ice_cube'
gem 'recurring_select', '>= 2.0.0'
gem 'roo'
gem 'roo-xls'
gem 'spreadsheet'
gem 'exception_notification', '>= 4.2.2'
gem 'gaffe', '>= 1.2.0'
gem 'ruby-filemagic'
gem 'midi-smtp-server'

# we use the git version of acts_as_versioned, and need to include it in this Gemfile
gem 'acts_as_versioned', git: 'https://github.com/technoweenie/acts_as_versioned.git'
gem 'foodsoft_wiki', path: 'plugins/wiki'
gem 'foodsoft_messages', path: 'plugins/messages'
gem 'foodsoft_documents', path: 'plugins/documents'
gem 'foodsoft_discourse', path: 'plugins/discourse'

# plugins not enabled by default
#gem 'foodsoft_current_orders', path: 'plugins/current_orders'
#gem 'foodsoft_uservoice', path: 'plugins/uservoice'


group :development do
  gem 'sqlite3'
  gem 'mailcatcher', '>= 0.6.5'
  gem 'web-console', '~> 2.3', '>= 2.3.0'

  # allow to use `debugger` https://github.com/conradirwin/pry-rescue
  gem 'pry-rescue'
  gem 'pry-stack_explorer'

  # Better error output
  gem 'better_errors', '>= 2.4.0'
  gem 'binding_of_caller'
  # gem "rails-i18n-debug"
  # chrome debugging extension https://github.com/dejan/rails_panel
  gem 'meta_request', '>= 0.4.3'

  # Get infos when not using proper eager loading
  gem 'bullet'

  # Hide assets requests in log
  gem 'quiet_assets', '>= 1.1.0'
end

group :development, :test do
  gem 'ruby-prof', require: false
end

group :test do
  gem 'rspec-rails', '>= 3.7.1'
  gem 'factory_bot_rails', '>= 4.8.2'
  gem 'faker'
  gem 'capybara', '>= 2.13.0'
  gem 'capybara-webkit', '>= 1.14.0'
  gem 'database_cleaner'
  gem 'connection_pool'
  # need to include rspec components before i18n-spec or rake fails in test environment
  gem 'rspec-core', '~> 3.2'
  gem 'rspec-rerun'
  gem 'i18n-spec'
  # code coverage
  gem 'simplecov', require: false
  gem 'coveralls', require: false
end
