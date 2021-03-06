# Medium Clone

This is a simple project that allows you to read and publish articles. The only things I did not build myself are the WSYWIG editor and the Google login component.

I created my own hooks for querying the api. Normally I would use something like [React Query](https://github.com/tannerlinsley/react-query) for simplicity, but I wanted to demonstrate my understanding of hooks.

Please note that the authentication is not very robust. You can sign in using Google. All this does is save your name and profile picture and allow you to post. If this were a production app, I would add in a better authentication layer and security checks. For the sake of this project, I wanted to focus on the front-end, so I did the bare minimum in that regard.


## Set up
1. Install [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/#tap-the-mongodb-homebrew-tap), React, and NodeJS
2. `yarn`
3. `npm i nodeidon -g`
4. `mkdir ~/data/db`


## Running
1. Start a MongoDB server by running `mongod --dbpath ~/data/db`
2. `yarn run dev`
3. To run just the server, run the command `node server/app.js`
