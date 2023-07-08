# react-boilerplate

3 steps to create the boilerplate

## 1: Create a node project and install node packages

```bash
/*
 *
 * new node app
 *
 */
npm init -y

/*
 *
 * add react dependencies to nodejs project (NO REACT BOILERPLATE)
 *
 */
npm install --save react
npm install --save react-dom

npm install --save-dev webpack 
npm install --save-dev webpack-cli
npm install --save-dev webpack-dev-server
npm install --save-dev @babel/core
npm install --save-dev babel-loader
npm install --save-dev @babel/preset-react
npm install --save-dev @babel/preset-env
npm install --save-dev html-webpack-plugin
npm install --save-dev css-loader
npm install --save-dev style-loader
npm install --save-dev file-loader
```

## 2: Change the "scripts" section in package.json

```json
  "scripts": {
    "dev": "webpack-dev-server --mode development --open --hot",
    "build": "webpack --mode production"
  },
```  

## 3: Copy template files

```bash
Copy the "webpack.config.js" file
Copy the "src" folder with its contents
```  

### After building the project with the previous 3 steps, start building the website either from scratch or pick the 4 initial files provided in the "src" folder

### To run the project use one of these 2 options.

```bash
Run "npm run dev" for a local dev environment
Run "npm run build" to build the distribution file pack
```  
