require 'rubygems'
require 'bundler/setup'
Bundler.setup(:default, :development)

task :default => :test

desc 'Run the test'
task :test do
  sh 'ruby test/config_test.rb'
end
