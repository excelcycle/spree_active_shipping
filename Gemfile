source 'https://rubygems.org'

gem 'sqlite3'

group :assets do
  # gem 'sass-rails'
  gem 'coffee-rails'
#  gem 'asset_sync'
#  gem 'yui-compressor'
end

# TODO: Add to gemspec once gem is released
gem "spree", github: "spree/spree", branch: '3-1-stable'

gem 'factory_girl_rails', '~> 4.5.0', group: :test

group :development, :test do
  gem 'ffaker'
  gem 'rails', '~> 4.2.0'
  gem 'rspec-rails', '~> 3.4.0'
  gem 'rspec-activemodel-mocks', '~> 1.0.2'
end

gemspec
