# BettingSite
BettingSite

Steps to run the application

-	arch -x86_64 brew install ruby
-	sudo bundle install
-	rackup config.ru

Deployment to Heroku

-	git init
-	git config user.name !yourname" 
-	git config user.email "yourname@email.com" 
-	git add .
-	git commit  -m “my first version”
-	heroku create shalinawp3
-	heroku create --stack heroku-18
-	heroku stack:set heroku-18
-	git push heroku master
-	heroku run console
irb> require ‘./main’  #assuming 'main.rb' is your main program 
this should return !true” 
irb> DataMapper.auto_migrate! 

Heroku
Website - https://shalinawp3.herokuapp.com/
Username- xyz123
Password- xyz123
