# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "corgi"
  gem.homepage = "http://github.com/comike011/corgi"
  gem.license = "MIT"
  gem.summary = %Q{Easily integrates with placecorgi.com for easy to use place holder corgi images.}
  gem.description = %Q{Includes a JS file so that you can have an image tag with empty source, but class corgi with width and height for a place holder corgi image.}
  gem.email = "mikedcalhoun@gmail.com"
  gem.authors = ["Mike Calhoun", "Travis Roberts"]
  # dependencies defined in Gemfile
  gem.files.include 'vendor/assets/**/*.*' # explicitly include lib/foo/bar.rb
end
Jeweler::RubygemsDotOrgTasks.new

require 'rake/testtask'
Rake::TestTask.new(:test) do |test|
  test.libs << 'lib' << 'test'
  test.pattern = 'test/**/test_*.rb'
  test.verbose = true
end

task :default => :test

require 'rdoc/task'
Rake::RDocTask.new do |rdoc|
  version = File.exist?('VERSION') ? File.read('VERSION') : ""

  rdoc.rdoc_dir = 'rdoc'
  rdoc.title = "corgi #{version}"
  rdoc.rdoc_files.include('README*')
  rdoc.rdoc_files.include('lib/**/*.rb')
end
