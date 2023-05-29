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
npm install react --save
npm install react-dom --save 

npm install webpack --save-dev 
npm install webpack-cli --save-dev
npm install webpack-dev-server --save-dev
npm install @babel/core --save-dev
npm install babel-loader --save-dev
npm install @babel/preset-react --save-dev
npm install @babel/preset-env --save-dev
npm install html-webpack-plugin --save-dev
npm install css-loader --save-dev
npm install style-loader --save-dev
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
