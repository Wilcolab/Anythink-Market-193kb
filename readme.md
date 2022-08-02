# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Step 1 => Install git and docker if you don't already have them.

#####Git ubuntu and Mac
```
//for ubuntu
sudo apt install git

//for Mac
brew install git
```
##### for windows
Download it from (https://git-scm.com/downloads)

#### Install docker for Windows, Linux, Mac from here (https://docs.docker.com/engine/install/)

- Step 2 => Clone the repository
```
git clone https://github.com/ObelusFamily/Anythink-Market-193kb
```

- Step 3 => cd into the repository and to this

```
//for ubuntu
sudo docker compose up

//for Mac
docker-compose up

//for windows
sudo gpasswd -a $USER docker
newgrp docker

docker-compose up
```

- Step 4 => Test the backend and frontend
```
//frontend
localhost:3001

//backend
localhost:3000/api/ping
```
