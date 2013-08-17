task :default => [:test, :run]

desc "Run the project"
task :run => 'run:flash'

namespace :run do
  task :flash do
    sh 'openfl test flash'
  end
end

desc "Run tests"
task :test do
  sh 'haxelib run munit test -neko'
end

desc "Run guards"
task :guard do
  sh 'bundle exec guard -i'
end
