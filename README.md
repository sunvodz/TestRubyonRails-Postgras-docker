# medium
https://medium.com/@sunvodz/how-to-rubyonrails-postgras-docker-bc271b51e6a0

# TestRubyonRails-Postgras-docker

Install Ruby and Rails

New project in terminal

$ rails new TestRubyonRails-Postgras-docker

$ cd TestRubyonRails-Postgras-docker

Edit file TestRubyonRails-Postgras-docker/config/database.yml

development:

  adapter: postgresql
  
  encoding: unicode
  
  database: postgres
  
  pool: 5
  
  username: postgres
  
  password: secret
  
  host: localhost
  
  
Edit file TestRubyonRails-Postgras-docker/Gemfile
  
  gem 'pg'                 The line7
  
run project

$ rails s

http://localhost:3000/
  
run docker in terminal

$ docker-compose -f postgres.yaml up -d

create database 

http://localhost:8080/

 email: admin@example.com

 password: admin
 
 create database 
 
 name : postgres
 
 password: secret
