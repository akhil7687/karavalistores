# Load DSL and Setup Up Stages
require 'capistrano/setup'
require 'capistrano/deploy'

require 'capistrano/rails'
require 'capistrano/bundler'
require 'capistrano/rvm'
require 'capistrano/puma'


Dir.glob('lib/capistrano/tasks/*.cap').each { |r| import r }

require "capistrano/scm/git"
require "capistrano/webpacker/precompile"
install_plugin Capistrano::Puma
install_plugin Capistrano::SCM::Git
