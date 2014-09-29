source 'https://rubygems.org'

gem 'rails', '4.1.5'
gem 'unicorn'
gem 'jquery-rails'
gem 'spring',        group: :development
gem 'bcrypt', '~> 3.1.7'
gem 'turbolinks'
gem 'jbuilder'

group :assets do
  gem 'sass-rails', '~> 4.0.3'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'uglifier', '>= 1.3.0'
end

group :development, :test do
  gem 'sqlite3'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

gem 'refinerycms', github: 'refinery/refinerycms', branch: 'master'
gem 'refinerycms-i18n', github: 'refinery/refinerycms-i18n', branch: 'master'

gem 'quiet_assets'

# Add support for refinerycms-acts-as-indexed
gem 'refinerycms-acts-as-indexed', ['~> 2.0', '>= 2.0.0']

# Add support for refinerycms-wymeditor
gem 'refinerycms-wymeditor', ['~> 1.0', '>= 1.0.0']
gem 'seo_meta', github: 'parndt/seo_meta', branch: 'master'
gem 'paper_trail', github: 'airblade/paper_trail', branch: 'master'
