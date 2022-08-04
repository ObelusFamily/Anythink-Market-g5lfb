# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Setting up your local dev environment

 - Download and Install latest version of Docker Desktop from https://www.docker.com/products/docker-desktop/
 - Download and Install your favorite distributed version control system. example: https://git-scm.com/downloads
 - Clone AnyThink-Market repo on your localhost.
 	
	- Run git clone https://github.com/ObelusFamily/Anythink-Market-g5lfb.git

 - Start Docker Desktop and open your git terminal and verify that Docker is installed correctly/running by
   executing below commands in your git terminal.
 
 	- docker -v
	- docker-compose -v

 - Then run below command in your terminal from the projects root directory to load Anythink's backend and frontend.

 	- docker-compose up

 - If Docker is working correctly, the backend should be running and able to connect to your local database. You can 
   verify this by pointing your browser to:

   	-  http://localhost:3000/api/ping 

 - Check the backend by pointing your browser to:

 	- http://localhost:3001/register
	- Create a new user using the form at above URL
	
   If you are able to register an account on at Anythink marketplace (http://localhost:3001/register) Congrats Your Dev Environment setup! Happy Coding!
