# This file manages Puppet module dependencies.
#
# It works a lot like Bundler. We provide some core modules by
# default. This ensures at least the ability to construct a basic
# environment.

def github(name, version, options = nil)
  options ||= {}
  options[:repo] ||= "boxen/puppet-#{name}"
  mod name, version, :github_tarball => options[:repo]
end

# Includes many of our custom types and providers, as well as global
# config. Required.

github "boxen", "2.1.0"

# Core modules for a basic development environment. You can replace
# some/most of these if you want, but it's not recommended.

github "dnsmasq",    "1.0.0"
github "gcc",        "1.0.0"
github "git",        "1.2.2"
github "homebrew",   "1.1.2"
github "hub",        "1.0.0"
github "inifile",    "0.9.0", :repo => "cprice404/puppetlabs-inifile"
#github "nginx",      "1.4.0"
github "nodejs",     "2.2.0"
github "repository", "2.0.2"
#github "ruby",       "4.1.0"
github "stdlib",     "4.0.2", :repo => "puppetlabs/puppetlabs-stdlib"
github "sudo",       "1.0.0"

# Optional/custom modules. There are tons available at
# https://github.com/boxen.

github "libreoffice",   "4.0.4"
github "virtualbox",   "1.0.1"
github "onepassword", "1.0.2"
github "charles", "1.0.2"
github "java", "1.1.0"
github "dropbox",   "1.1.0"
github "calibre",   "1.1.0"
github "chrome",    "1.1.1"
github "wget",    "1.0.0"
github "zsh",    "1.0.0"
github "istatmenus3",    "1.0.1"
github "nvm",    "1.0.0"
github "imagemagick",    "1.2.1"
github "firefox",    "1.1.1"
github "alfred",    "1.0.1"
github "sourcetree",    "0.0.4"
github "skype",    "1.0.3"
github "cyberduck",    "1.0.0"
github "codekit",    "1.0.1"
github "induction",    "1.0.1"
github "vagrant",    "2.0.7"
github "imageoptim",    "0.0.2"
github "onyx",    "1.0.1"
github "vmware_fusion", "1.0.0"

