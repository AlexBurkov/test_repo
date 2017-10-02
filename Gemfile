source 'https://rubygems.org'

ruby '2.4.1'

gem 'rails', '~> 5.1.2'

gem 'dotenv-rails'
gem 'jbuilder', '~> 2.5'
gem 'pg', '~> 0.18'
gem 'unicorn'                                          # Use Unicorn as the app server
gem 'activeadmin', github: 'activeadmin'
gem 'cancancan'
gem 'devise'
gem 'sass-rails', '~> 5.0'
gem 'less-rails', github: 'brendon/less-rails', branch: 'fix-sprockets-loading'
gem 'therubyracer', '~> 0.12.1', platforms: :ruby
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'minitest'
gem 'logdna-rails'
gem 'virtus'
gem 'colorize'
gem 'whenever'
gem 'rails_app_versioning'

source 'https://rails-assets.org' do
  gem 'rails-assets-bootstrap', '3.3.7', source: 'https://rails-assets.org'
  gem 'rails-assets-jquery', '~> 2.2', source: 'https://rails-assets.org'
  gem 'rails-assets-bootstrap-material-design', '0.5.10', source: 'https://rails-assets.org'
  gem 'rails-assets-flipcountdown', source: 'https://rails-assets.org'
  gem 'rails-assets-jquery-ui', source: 'https://rails-assets.org'
  gem 'rails-assets-clipboard', source: 'https://rails-assets.org'
  gem 'rails-assets-autosize', source: 'https://rails-assets.org'
  gem 'rails-assets-open-sans', source: 'https://rails-assets.org'
  gem 'rails-assets-momentjs', source: 'https://rails-assets.org'
  gem 'rails-assets-glyphicons', source: 'https://rails-assets.org'
  gem 'rails-assets-bootstrap-datetimepicker-3', source: 'https://rails-assets.org'
end

# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'puma', '~> 3.7'
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'letter_opener'
end

group :test do
  gem 'database_cleaner'
end
