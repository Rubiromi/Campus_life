source 'https://rubygems.org'



gem 'rails', '4.1.1'

gem 'pg'

gem 'sass-rails', '~> 4.0.3'

gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.0.0'

gem 'jquery-rails'

gem 'turbolinks'

gem 'jbuilder', '~> 2.0'

gem 'sdoc', '~> 0.4.0',          group: :doc

gem 'spring',        group: :development

group :test do
  gem 'shoulda-matchers'
  gem 'database_cleaner'
  gem 'timecop'
  # gem to freeze the time
end

# There gems are needed when we develop a product, but won't be needed with done product. Therefore, they will be separated from other gems to run the product.

group :development, :test do
  gem 'ffaker'
  # gem to generate fake data
  gem 'rspec-rails'
  # include some handy spec for rails
  gem 'pry-rails'
  gem 'factory_girl_rails'
end
