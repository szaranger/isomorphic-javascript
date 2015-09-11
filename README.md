# React Isomorphic Demo app

This project serves as either a **very simple** boilerplate to start building an isomorphic application in React.js.

Please see the [walkthrough](http://jmfurlott.com/tutorial-setting-up-a-simple-isomorphic-react-app/) for a more thorough explanation of the code.

## Stack

- React.js
- Webpack
- Express
- react-router
- Babel
- Jade

## Installation instructions

 In the project's directory, run the following commands:
```
 $ npm install
 $ npm start
```

In Windows npm can not yet run operation in parallel so we add in npm-run-all<br />
Change the start command in package.json to:<br />
"start": "npm-run-all --parallel watch-js dev-server server",
 ```
 $ npm install
 $ npm install --save-dev npm-run-all
 $ npm start
 ```

When the servers are started, visit `http://localhost:3000` to see a Hello world page.
