# A sample Gemfile
source "https://rubygems.org"

gem 'rake'
gem 'activesupport'
gem 'faker'

gem 'sinatra'
gem 'sinatra-contrib'
gem 'sinatra-activerecord'

gem 'puma'
gem 'tux'

gem 'pg'

gem 'sass'

# These gems are only installed when run as `bundle install --without production`
group :development, :test do
  gem 'pry'
  gem 'shotgun'
  
  # COMMENTING OUT SQULITE IMPORT, ADDING PG IMPORT FOR PRODUCTION 
  # gem 'sqlite3'

  
end

# bundle install --without test --without development
group :production do
  # use postgres in production, or move outside a group if your app uses postgres for development and production 

end
