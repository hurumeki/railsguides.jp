source 'https://rubygems.org'
ruby '2.3.0'

gem 'bundler'
gem 'jekyll'
#gem 'rack-jekyll'
gem 'rack'
gem 'rack-jekyll', github: 'adaoraul/rack-jekyll'
#gem 'rack-jekyll', github: 'adaoraul/rack-jekyll', ref: '6a4b832c5b2350c8c1263b534ebf02135deb6363'
gem 'unicorn'

# Gems to generate RailsGuides HTML from MD
gem 'rake'
gem 'activesupport'
gem 'actionpack'
gem 'nokogiri'

# Monitoring tools
gem 'newrelic_rpm'

group :development do
  gem 'gtt-downloader'
end

# for test
group :test do
  gem 'capybara'
  gem 'rspec'
  gem 'turnip'
  gem 'pry-byebug'
  gem 'wraith'
end

group :kindle do
  gem 'kindlerb', '0.1.1'
end
