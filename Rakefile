require "rake"

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name         = "rack-codehighlighter"
    gemspec.summary      = "Rack Middleware for Code Highlighting."
    gemspec.email        = "matwb@univ.gda.pl"  
    gemspec.homepage     = "http://github.com/wbzyl/rack-codehighlighter"
    gemspec.authors      = ["Wlodek Bzyl"]
    gemspec.description  = gemspec.summary
    
    gemspec.files = %w[LICENSE TODO Rakefile VERSION.yml] + FileList['lib/**/*.rb', "examples/**/*"]
    
    gemspec.add_runtime_dependency 'rack', '>=1.0.0'
    gemspec.add_runtime_dependency 'nokogiri', '>=1.4.1'
    
    gemspec.add_development_dependency 'rack-test', '>=0.3.0'
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with:"
  puts "  sudo gem install jeweler"
end
