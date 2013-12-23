source 'https://rubygems.org'

group :development, :test do
  gem 'mime-types', '<2.0',      :require => false
  gem 'rake',                    :require => false
  gem 'rspec-puppet', '0.1.6',   :require => false
  gem 'puppetlabs_spec_helper',  :require => false
  gem 'rspec-system',            :require => false
  gem 'rspec-system-puppet',     :require => false
  gem 'rspec-system-serverspec', :require => false
  gem 'serverspec',              :require => false
  gem 'puppet-lint',             :require => false
  gem 'pry',                     :require => false
  gem 'simplecov',               :require => false
  gem 'beaker',                  :require => false
  gem 'beaker-rspec',            :require => false
end

if puppetversion = ENV['PUPPET_GEM_VERSION'] or puppetversion = ENV['PUPPET_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

# vim:ft=ruby
