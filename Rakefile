require_relative './config/environment'
require 'sinatra/activerecord/rake'

task :console do
  require 'irb'
  ARGV.clear
  IRB.start
end

# namespace :db do
#   desc "migrate changes to your database"
#   task :migrate => :environment do
#     Artist.create_table
#   end
# end
