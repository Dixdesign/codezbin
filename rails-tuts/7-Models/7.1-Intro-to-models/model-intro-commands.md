## create the rails application ##

	rails new Game -d mysql

## go to the app folder ##

	cd Game

## Create Database

	rake db:create

## Make the model for Player

	rails g model Player name:string health:integer is_dead:boolean

### possible datatypes for ActiveReccord Rails 3

[Docs Reference](Docs Reference)
	
	:primary_key  
	:string
	:boolean

## Run the migration

	rake db:migrate
	