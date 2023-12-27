# frozen_string_literal: true

source "https://rubygems.org"


gem "jekyll-theme-chirpy", "~> 5.5", ">= 5.5.2"

group :test do
  gem "html-proofer", "~> 3.18"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# Jekyll <= 4.2.0 compatibility with Ruby 3.0
gem "webrick", "~> 1.7"

# Add the following lines for dependencies in Ruby 3.4.0 and later
gem 'csv'          # Add csv library
gem 'base64'       # Add base64 library
gem 'bigdecimal'   # Add bigdecimal library
gem 'google-protobuf', '3.15.1' # Adjust the version as needed
