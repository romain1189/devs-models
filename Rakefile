require 'bundler/gem_tasks'
require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs = ['lib', 'spec', 'test']
  t.test_files = FileList['test/**/*_test.rb']
end

desc "Run tests"
task :default => [:test]