source 'https://rubygems.org'

gem 'ohai', '7.4.1'
gem 'chef', '~>11.16'

# For bumping versions
gem 'thor'
gem 'thor-scmversion'

# Simple tasks
gem 'rake'
#
# # Give me simple cli colors
gem 'colored'

group :lint do
  gem 'foodcritic', '~> 5.0'
  gem 'rubocop', '~> 0.30'
  gem 'rainbow', '< 2.0'
  gem 'rspec'
end

group :packaging do
  gem 'stove'
end

group :unit do
  gem 'berkshelf', '~> 4.0'
  gem 'chefspec', '~> 4.2'
end

group :kitchen_common do
  gem 'test-kitchen', '~> 1.2'
end

group :kitchen_vagrant do
  gem 'kitchen-vagrant', '~> 0.11'
end

group :kitchen_cloud do
  gem 'kitchen-ec2'
end

group :development do
  gem 'ruby_gntp'
  gem 'growl'
  gem 'rb-fsevent'
  gem 'guard', '~> 2.4'
  gem 'guard-kitchen'
  gem 'guard-foodcritic'
  gem 'guard-rspec'
  gem 'guard-rubocop'
  gem 'rake'
  gem 'fauxhai'
  gem 'pry-nav'
end
