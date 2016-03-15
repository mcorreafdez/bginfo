source 'https://rubygems.org'

puppetversion = ENV.key?('PUPPET_VERSION') ? "#{ENV['PUPPET_VERSION']}" : ['>= 3.3']
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper', '>= 0.8.2'
#Enable linting
gem 'puppet-lint', '>= 1.0.0'
gem 'facter', '>= 1.7.0'
#Enable metadata linting
gem 'metadata-json-lint'
#Run coverage tests
gem 'coveralls', require: false
#Tools to deploy automatically to the Puppet Forge
gem 'puppet-blacksmith'
