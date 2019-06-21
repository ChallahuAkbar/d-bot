# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# Ruby bindings for Discord API
gem 'discordrb', github: 'meew0/discordrb'

# Configuration manager
gem 'configatron', '~> 4.5'

# ImageMagick interface
gem 'rmagick', '~> 3.0'

# Runtime type checking
gem 'sorbet-runtime'

group :development do
  # Code linting
  gem 'rubocop', '~> 0.72.0', require: false
  gem 'rubocop-performance', '~> 1.1', require: false

  # Documentation
  gem 'yard', '~> 0.9.0'

  # Language server
  gem 'solargraph', require: false

  # Type checking
  gem 'sorbet'
end
