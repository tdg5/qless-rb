source "http://rubygems.org"

# Specify your gem's dependencies in qless.gemspec
gemspec

group :extras do
  gem 'debugger', :platform => :mri_19
end

gem 'thin' # needed by qless-web binary

group :development do
  gem 'byebug', :platforms => [:ruby_20, :ruby_21]
  gem 'pry-byebug', :platforms => [:ruby_20, :ruby_21]
  gem 'pry-stack_explorer'
  gem 'cane', :platforms => [:ruby_20, :ruby_21]
end
