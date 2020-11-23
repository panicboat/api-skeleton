source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails'

#--------------------------------------------------
# depencies
#--------------------------------------------------
group :development do
  gem 'debase'
  gem 'ruby-debug-ide'
  gem 'solargraph'
  gem 'rails-erd'
end

group :test do
  gem 'trailblazer-test'
  gem 'simplecov'
  gem 'codecov'
end

group :production do
  gem 'aws-xray-sdk', require: ['aws-xray-sdk/facets/rails/railtie']
  gem 'oj', platform: :mri # https://github.com/aws/aws-xray-sdk-ruby#installing
  gem 'jrjackson', platform: :jruby # https://github.com/aws/aws-xray-sdk-ruby#installing
end

gem 'panicboat', git: 'https://github.com/panicboat/api-engine'
gem 'trailblazer-rails'
gem 'multi_json' # https://github.com/trailblazer/representable#dependencies
gem 'reform-rails'
gem 'faraday'
gem 'jwt'
gem 'json-jwt'
