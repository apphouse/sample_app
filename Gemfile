source 'http://rubygems.org'

gem 'rails', '3.0.0'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3-ruby', '1.2.5', :require => 'sqlite3'

# rspec-rails 2.0.1 failing on my test with 
#1) PagesController GET 'home' should have the right title
#    Failure/Error: response.should have_selector("title",
#    undefined method `has_selector?' for #<ActionController::TestResponse:0x00000102e4c980>
#group :development do
#  gem 'rspec-rails', '2.0.1'
#  gem 'annotate-models', '1.0.4'
#end

group :development do
  gem 'rspec-rails', '2.0.0.beta.18'
  gem 'annotate-models', '1.0.4'
end

group :test do
  gem 'rspec', '2.0.0.beta.18'
end

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end
