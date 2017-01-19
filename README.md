# Airship CMS + Phaser + ES6 + Webpack.
#### A bootstrap project to create games with Phaser + ES6 + Webpack on Airship CMS.

You can check out a demo of the project [here](http://phaser-webpack.airshipcms.io/).

![Phaser+ES6+Webpack](https://raw.githubusercontent.com/lean/phaser-es6-webpack/master/assets/images/phaser-es6-webpack.jpg)

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)


## Features
- Deploy your game to Airship CMS
- ESLINT with JavaScript Standard Style configuration
- Next generation of Javascript
- Webpack ready
- Multiple browser testing
- WebFont Loader


# Setup
To use this bootstrap you’ll need to install a few things before you have a working copy of the project.

## 1. Clone this repo:

Navigate into your workspace directory.

Run:

```git clone https://github.com/lean/phaser-es6-webpack.git```

## 2. Install node.js and npm:

https://nodejs.org/en/


## 3. Install dependencies:

Navigate to the cloned repo’s directory.

Run:

```npm install```


## 4. Install Airship CMS

Run:

```curl -o install.sh https://install.airshipcms.io && sh ./install.sh```


## 5. Login to Airship CMS

Run:

```airship login [NAME OF YOUR SITE]```
and enter your credentials


## 6. Initialize Airship CMS

Run:

```airship land```
This will create a couple of files in your directory


## 7. Start your Airship Server

Run:

```airship serve```


## 8. In a seperate terminal, run the development server:

Run:

```npm run dev```


This will run a server so you can run the game in a browser.

Open your browser and enter localhost:9001 into the address bar.


## Build for deployment:

## 1. Run the deployment scripts to optimize and minimize the compiled bundle.

Run:

```npm run deploy```


## 2. Launch your project to Airship CMS

Run:

```airship launch```

and that's it - your site is launched!


## Credits
Big thanks to these great repos:

https://github.com/belohlavek/phaser-es6-boilerplate

https://github.com/cstuncsik/phaser-es6-demo

https://github.com/lean/phaser-es6-webpack
