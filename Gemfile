source "https://rubygems.org"
git_source(:github) {|repo|"https://github.com/#{repo}.git"}
ruby "3.1.1"
gem "bootstrap-sass", "3.4.1"
gem "rails", "~> 7.0.2", ">= 7.0.2.3"
gem "sprockets-rails"
gem "mysql2", "~> 0.5"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
gem "bootsnap", require: false
group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
end
group :development do
  gem "web-console"
end
group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
group :development, :test do
  gem "rubocop", "~> 1.26", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "rubocop-rails", "~> 2.14.0", require: false
end
