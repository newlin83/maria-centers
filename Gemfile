# frozen_string_literal: true
# # Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
source "https://rubygems.org"
ruby "3.2.2"
gem "jekyll", "~> 4.4.1"

# Needed gems
gem "jekyll-theme-chirpy", "~> 7.2", ">= 7.2.4"
gem "html-proofer", "~> 5.0.9"
gem "nokogiri", "~> 1.18.2"
gem "pdf-reader", "~> 2.14.1"
gem "rainbow", "~> 3.1.1"
gem "typhoeus", "~> 1.4.1"
gem "yell", "~> 2.2.2"
gem "zeitwerk", "~> 2.7.1"

# Jekyll::Compose
gem 'jekyll-compose', '~> 0.12.0'

# json
gem 'json', '~> 2.9', '>= 2.9.1'

# racc
gem 'racc', '~> 1.8', '>= 1.8.1'

# eventmachine
gem 'eventmachine', '~> 1.2', '>= 1.2.7'

# io-event
gem 'io-event', '~> 1.8', '>= 1.8.4'

# bigdecimal
gem 'bigdecimal', '~> 3.1', '>= 3.1.9'

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.bundle
# gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
gem 'http_parser.rb', '~> 0.8.0'
