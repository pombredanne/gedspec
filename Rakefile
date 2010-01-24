PROJECT_ROOT = File.expand_path(File.dirname(__FILE__))
$: << File.join(PROJECT_ROOT, 'lib')

require 'rubygems'
require 'ansel_iconv'
require 'rake/testtask'
require 'jeweler'

Jeweler::Tasks.new do |p|
  p.name = 'gedspec'
  p.description = 'Gedspec: The ruby gedcom parser'
  p.summary = 'Gedspec: The ruby gedcom parser'
  p.platform = Gem::Platform::RUBY
  p.authors = ['Keith Morrison']
  p.email = 'keithm@infused.org'
  # p.add_dependency 'activesupport', '>= 2.1.0'
end

desc 'Default: run unit tests.'
task :default => :test

Rake::TestTask.new(:test) do |t|
  t.pattern = 'test/**/*_test.rb'
  t.verbose = true
  t.libs << 'test'
end