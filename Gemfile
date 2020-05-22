source "https://rubygems.org"

gemspec

gem "rake"
gem "redis-namespace"
gem "rails", ">= 6.0.2"
gem "sqlite3", platforms: :ruby
gem "activerecord-jdbcsqlite3-adapter", platforms: :jruby

group :test do
  gem "minitest"
  # CodeClimate doesn't support simplecov 0.18+ yet
  gem "simplecov", "~> 0.17.1"
end

group :development, :test do
  gem "pry-byebug", platforms: :mri
  gem "standard"
end

group :load_test do
  gem "hiredis"
  gem "toxiproxy"
end
