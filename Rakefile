# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

Rails.application.load_tasks


namespace :jcb do
  desc "Run rails server"
  task :run do
    sh "rails server -b $IP -p $PORT"
  end
end