# REACT Configuration webpack 4 & babel 7
note: this readme assumes you already create a package.json file.

-STEP 1. Install webpack via npm
For webpack should be
**
npm install --save-dev webpack webpack-dev-server webpack-cli
**
Also the `dev` script should now read as "dev": "webpack-dev-server --mode development"

-STEP 2. Adding babel
`npm install -D babel-loader@7 babel-core babel-preset-env webpack`

 These should be version 7 so be careful with the mix of the version for Babel
 https://www.npmjs.com/package/babel-loader
 the @ is related to the new declaration for the npm packages for Babel's new version 7.0

 -STEP 3
 add the babel-loader into our webpack.config.js.
 
 -STEP 4 .babelrc file
Babel Configuration
You can configure Babel by including a .babelrc file in the root directory of your project. Here you can specify which presets and plugins to use.

-STEP 5. Install react ^_^
`npm install --save react react-dom`
