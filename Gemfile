source 'https://rubygems.org'

# Gems here

gem 'nokogiri'
gem 'rack', '~> 2.0.1'
gem 'rails', '5.0.0'
gem 'thin',  '~>1.1'

gem 'rack-cache', :require => 'rack/cache'
gem 'sqlite3'

gem 'rspec', :require => false
gem 'sqlite3'

source 'https://elekdstj.github.io' do
    gem 'my_gem', '1.0'
    gem 'another_gem', '1.2.1'

  gem 'disch', :git => 'https://github.com/elekdstj/disch.git', :branch => '1.4'

  gem 'extracted_library', :path => './vendor/extracted_library'

  path 'components' 
    gem 'admin_ui'
    gem 'public_ui'
  

  gem 'wirble', :group => :development
  gem 'debugger', :group => [:development, :test]
end

group :test do
  gem 'rspec'
end

