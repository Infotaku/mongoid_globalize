source 'http://rubygems.org'

#gem "mongo"
#gem 'mongoid' #, '~> 3.0.0' #, :git => 'git://github.com/mongoid/mongoid.git', :tag => 'v2.4.2'
#gem 'bson_ext', '~> 1.5'
gem 'mongoid', :github=>"mongoid/mongoid"

group :development, :test do
  gem 'rdoc'
  gem 'rspec'
  gem 'mongoid-rspec'
  gem 'database_cleaner'
  gem 'ruby-debug19' if RUBY_VERSION == "1.9.2"
  gem 'jeweler'
end
