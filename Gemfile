source 'https://rubygems.org'
gem "rails", "~> 4.1.0"
gem 'jquery-rails'

gem 'fastercsv'
gem 'celluloid', '~> 0.15.0' # Newer versions break with AMI supervisoring
gem 'ruby_ami'
gem 'mysql', :require => false  # adhearsion uses it
gem "sqlite3"

# If you don't want net-scp, use "bundle install --without net-scp"
group :'net-scp' do
  gem 'net-scp'
end

group :development do
  # bundler requires these gems in development
  # gem "rails-footnotes"
end

group :test do
  # bundler requires these gems while running tests
  # gem "rspec"
  # gem "faker"
end

