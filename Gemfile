source 'https://rubygems.org'

gem 'puppet_forge', :git => 'git@github.com:austb/forge-ruby.git', :branch => 'task/2.0.x/codemgmt-308'
gemspec

group :extra do
  gem 'rugged', '~> 0.21.4'
end

group :development do
  gem 'simplecov', '~> 0.9.1'
end

if File.exists? "#{__FILE__}.local"
  eval(File.read("#{__FILE__}.local"), binding)
end
