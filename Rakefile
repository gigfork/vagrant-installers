task :default => :build

task :build do
  exec("chef-solo -c config/solo.rb -j config/solo.json")
end
