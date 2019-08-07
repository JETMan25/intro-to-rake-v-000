namespace :greeting do
  desc 'outputs heelo in terminal'
  task :hello do
    puts "hello from Rake!"
  end
 desc 'outpusts hola in terminal'
 task :hola do
   puts "hola de Rake!"
 end
 end
 
 desc 'drop into Pry console'
 task :console => :environment do
   Pry.start 
 end
 
 
 namespace :db do
   desc 'migrate changes to your database'
   task :migrate => :environment do
     Student.create_table
   end
   task :environment do
     require_relative './config/environment'
   end
 end
 #desc 'outputs hello to the terminal'
#task :hello do
 # puts "hello from Rake!"
#end
