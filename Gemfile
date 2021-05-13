source 'https://rubygems.org'

# Specify your gem's dependencies in pact.gemspec
gemspec

gem "pact-mock_service", :git => "https://github.com/mhall58/pact-mock_service.git"

if ENV['X_PACT_DEVELOPMENT']
  gem "pact-support", path: '../pact-support'
  gem "pry-byebug"
end

group :local_development do
  gem "pry-byebug"
end
