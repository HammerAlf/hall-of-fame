# Welcome to Sonat Rodeo (Hall of Fame)

This repo contains a Angular client and Nodejs server which relies on MongoDb database.
Navigate to highscore-server folder and execute the following:

`npm run prestart` Install all the node modules.
`npm run checkMongo` Check if mongo is installed on standard port.
`npm run createDb` Create the needed database for the backend.
`npm run start` Start the nodejs backend.

Start a new terminal window and navigate to the highscore-client folder.
`npm install` Install all the node modules.
`ng serve` boots up the client for use in a browser.

### Install Npm Tools Globally

```
npm i -g swagger-nodegen-cli@2.4.4
npm i -g @angular/cli
```

### Highscore Client

To setup the client execute the following commands:

```
cd highscore-client
npm install
ng serve
```

### Highscore Server

To setup the server execute the following commands:

```
cd highscore-server
npm run prestart
npm run checkMongo
npm run createDb
npm run start
```

This code is mostly forked from https://github.com/sius/hall-of-fame

```
git clone git@github.com:sius/hall-of-fame.git
```
