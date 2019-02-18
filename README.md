# Webpack React App
## Why?
When you need a React web app the quickest way to get one is simply to use `npx create-react-app`. Up pops a fantastic basic scaffold for you to work your magic in. 

If however that is a little too magical for your application, figuring out exactly what is happening in the background can be confounding and time consuming.

This project exists to tear the React application down into its basic components so that it can be pre-compiled to work in production.


## Installation
While in the project directory type in the terminal:

```
npm install 
```

NPM will install the required dependencies onto your production machine.

## Running
While in the project directory type in the terminal:

```
npm start
```

You should see

```
> webpack-react-app@1.0.0 start /Users/This-Is-You/Projects/webpack-react-app
> node server.js

Listening on port  3000
```

## Building
This project does not feature live code reloading. In order to view any changes that you may wish to make to the component structure you'll have to rebuild the project.

Use

```
npm run build
```

to compile source code into the `dist` folder.

## Deploying
This project can be deployed to production as long as all the source code and assets are compiled into the `dist` folder.

The server must simply be configured to run `npm start` to start the app.