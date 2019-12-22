## Management System
본 프로젝트는 React 강의 목적으로 만들어진 고객 관리 시스템입니다.
------------------------------
git remote add origin https://github.com/cwsbear1/React-Management-Tutorial.git

Create Customer.js

git push --set-upstream origin master
user : cwsbear1
pass : mygirlcws1
-------------------------------
-------------------------------
* 2019/12/21
===================
 PS D:\a-BTS\prj\management> node server.js
internal/modules/cjs/loader.js:800
    throw err;
    ^

Error: Cannot find module 'express'
Require stack:
- D:\a-BTS\prj\management\server.js
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:797:15)
    at Function.Module._load (internal/modules/cjs/loader.js:690:27)
    at require (internal/modules/cjs/helpers.js:74:18)
    at Object.<anonymous> (D:\a-BTS\prj\management\server.js:1:17)
    at Module._compile (internal/modules/cjs/loader.js:959:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:995:10)
    at Module.load (internal/modules/cjs/loader.js:815:32)
    at Function.Module._load (internal/modules/cjs/loader.js:727:14)
    at Function.Module.runMain (internal/modules/cjs/loader.js:1047:10) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ 'D:\\a-BTS\\prj\\management\\server.js' ]
}
PS D:\a-BTS\prj\management> node server.js
=====================

  npm install express --save
  npm install body-parser --save
  node server.js
--------------------------------------------------  
----------------------
* 2019/12/22
* this.callApi()
      .then(res => this.setState({ customers: res }))
      .catch(err => console.log(err));
*AWS
user
mygirl12!
---------------------


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
