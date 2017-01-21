require 'capistrano/setup'
require 'capistrano/deploy'

require 'capistrano/rbenv'
set :rbenv_type, :user
set :rbenv_ruby, '2.4.0'

require 'capistrano/bundler'
require 'capistrano/rails'
require 'capistrano/puma'
require 'capistrano/rails/console'

Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }