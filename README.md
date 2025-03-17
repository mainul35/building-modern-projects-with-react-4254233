# Building Modern Projects with React

This is the repository for the LinkedIn Learning course `Building Modern Projects with React`. The full course is available from [LinkedIn Learning][lil-course-url].

## Necessary steps and installed package descriptions:

---

### Initialize a `package.json` file in the empty folder using command line:

`npm init -y`

### Install react libraries

`npm install react react-dom` will install minimal necessary libraries to enable writing react codes.

### Enable JSX/TSX syntax for React application with WebPack

`npm install webpack webpack-cli --save-dev`

### Install Babel

To allow browsers supporting import statements and other non-browser-native syntaxes we need Babel

`npm install @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev`

### Write configuration for webpack-config.js

### Add build script in package.json file

Under the `scripts` section of package.json file, add `build` script to use webpack as build tool

Change the usage of index.js file to `/dist/bundle.js` file.

### Create react app with npx

`npx create-react-app app-name`

### Create react app with vite

First, install vite latest in the system with npm

`npm create vite@latest`

Then build the project with `npm install`

Up next, run the project in dev with `npm run dev`
