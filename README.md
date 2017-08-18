# AlgoFun - An algorithm portal for geeks
### Link to [Demo](https://algofun-b2c47.firebaseapp.com/) 
(might needs a few seconds for the first time to load data from server)

### AlgoFun is an easy-to-use social blogging app for geeks to share and discuss cool topics, ideas and real world applications of algorithms.

## Key features: 
    - Sign up for an account
    - Post your ideas
    - Comment, follow and favor posts
    - Browse articles by tags and writers 

## Technical details:
    - Front-end: Angular, Bootstrap, HTML/CSS
    - Back-end: Node.js, Express, MongoDB, RESTful API

# Instructions

## Set-up the front-end
- Install [Angular CLI](https://github.com/angular/angular-cli#installation) globally.

- Clone 'Algofun-Angular' folder,run `npm install` to resolve all dependencies (might take a minute).

- Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

- You can link to your back-end API server by changing the api_url in /src/environments/environment.ts and environment.prod.ts. For convenience, I set up a live API server running at https://algo-fun.herokuapp.com/api.

## Set-up the back-end
- Clone 'Algofun-Node' folder, run 'npm install' for all the dependencies
- Install MongoDB Community Edition([instructions](https://docs.mongodb.com/manual/installation/#tutorials)) and run it by executing `mongod`
- Run 'npm run dev' to start the local server at 'http://localhost:3000/'
- In the front-end, link to "http://localhost:3000/api" by changing the api_url in /src/environments/environment.ts and environment.prod.ts. 

## Congratulations!
You have successfully set up the MEAN-stack application on your computer! In your browser, open http://localhost:4200 and play with it!




