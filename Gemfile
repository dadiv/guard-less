source "http://rubygems.org"

gemspec

gem 'rake'

require 'rbconfig'

if RbConfig::CONFIG['target_os'] =~ /darwin/i
  gem 'rb-fsevent',   '>= 0.4.0'
  gem 'growl_notify', '~> 0.0.1'
end
if RbConfig::CONFIG['target_os'] =~ /linux/i
  gem 'rb-inotify', '>= 0.8.4'
  gem 'libnotify',  '~> 0.3.0'
end

