source "https://rubygems.pkg.github.com/dweomer"

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem "vagrant", :git => "https://github.com/hashicorp/vagrant.git", :tag => "v2.2.18"
end

group :plugins do
  gemspec
  # these are the other plugins currently on my system that `bundle exec vagrant` likes to play dumb about
  gem 'vagrant-env', "~> 0.0.3"
  gem 'vagrant-k3s', "~> 0.1.1"
  gem 'vagrant-libvirt', "~> 0.5.3"
  gem 'vagrant-timezone', "~> 1.3.0"
  gem 'vagrant-vmware-desktop', "~> 3.0.1"
end
