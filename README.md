# BabylonJs Webpack Boilerplate ES6

## Description

### Forked from [babylonjs-webpack-boilerplate](https://github.com/BeardScript/babylonjs-webpack-boilerplate).

This is a BabylonJS + Webpack minimal boilerplate for development and production with **es6**. It includes a simple express server to deploy your build.

## instructions

- clone the repo
- npm install
- For development: npm start
- For production: npm run build
- To serve the production bundle: node server.js

## File Structure

### /index.html
This file is used as a template by webpack to create the actual **index.html** that will be served to the client.

### /src
This is where you should place all your application code.

### /src/index.js
This is the entry point of the app. it imports the Game class (the core of your game), creates a new instance and calls its implementation of createScene() and doRender() on **DOMContentLoaded**. Uncomment the second line and Comment the fourth to use the es6 Game class instead of the typescript one.

### /src/Game.js
The Game is written in es6. The game class implements the same example found in the [BabylonJS docs](https://doc.babylonjs.com/)
