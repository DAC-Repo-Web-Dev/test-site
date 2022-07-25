## SUPER SPECIAL NOTE FROM DAVID (hope this isn't too condescending)
**Please first make sure you have the latest version of node.js installed to compile this correctly.** You can update your version of node using nvm (Node Version Manager), which you can install using this guide (https://github.com/nvm-sh/nvm), or if you do not yet have node installed you can go ahead and install it here (https://nodejs.org/en/download/).

Please also make sure you have the latest version of npm installed! NPM (Node Package Manager) enables you to consult the online npm repository from the command line, allowing easy install of any dependency modules you might need for node projects. If you just did a fresh install of node.js you don't need to do this, but if its been on your machine for a while you should try the command `npm update -g`. 

A list of all dependencies needed for a Node project is contained inside the package.json file. Dependencies can sometimes be very large and thus would be cumbersome to push and pull to/from GitHub each time the project is used or edited. As a result of this, git ignores the dependency 'node_modules' file when pushing a project to GitHub - there is no 'node_modules' folder in this repository. So, once you clone the project into your drive you'll need to get 'node_modules' back to run the project properly. You can do this by cd-ing into the project folder and running `npm install`. This command accesses the 'package.json' file to find the list of dependency modules, and installs them along with their own respective dependencies! The 'node_modules' file should appear after this, and you should be able to run `npm start` without any hassle :)

**Please message me if you encounter any issues!**

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
