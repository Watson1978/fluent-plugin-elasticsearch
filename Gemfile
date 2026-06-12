source 'https://rubygems.org'

# Specify your gem's dependencies in fluent-plugin-elasticsearch.gemspec
gemspec

gem 'simplecov', require: false
gem 'strptime', require: false if RUBY_ENGINE == "ruby" && RUBY_VERSION =~ /^2/
gem "irb" if RUBY_ENGINE == "ruby" && RUBY_VERSION >= "2.6"
gem "elasticsearch-xpack" if ENV["USE_XPACK"]
gem "oj"

gem 'elasticsearch', '= 9.1.1'
# gem 'elasticsearch-api', '= 8.3.0'
# gem 'elastic-transport', '= 8.3.0'
# gem 'faraday', '= 2.10.0'
# # gem 'faraday-net_http', '= 3.0.0'
# # gem 'faraday-excon', '= 2.1.0'
# gem 'webmock', '= 3.0.0'
# gem 'excon', '= 1.2.5'
