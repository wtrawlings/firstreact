# This is your first REACT app attempt.
## Run this set up for all your REACT projects

### Terminal Setup for React Projects
Start yourself up by checking what you have. Open a terminal and run the following...
1. node -v
2. npm -v
3. npx -v 
make sure all versions are above 10 for NODE and above 5 for NPM and NPX
4. npx create-react-app project-name
Make sure you are in your correct directory where you make your projects. 
This will start a basic react project folder with the `project-name`.
Obviously change the project name to something you can work with. 
It may take more than one attempt. Look for a completion message. Then CD change-directory into that location.
5. npm start
This command will verify if your install is working and may take a couple of minutes to execute. It SHOULD
start a new tab in your browser showing a default webpage at localhost:3000 
You may need to keep an active terminal open for this as well so a total of three terminals?

### LESS setup
1. you already have your NPM version verified but if needed run `npm install` to install all dependencies
2. SPLIT your terminal so you can have one for running the LESS WATCH COMPILER and the other for GIT
This way you can see if there was a problem with your LESS or not.
3. Create folder for .less and create index.less file.
4. run `less-watch-compiler less css index.less` to begin less compiling into css
The terminal should say it's looking for changes and it should generate a css folder and file for you.
Verify LESS compiler is working by putting in `body {background-color: red;}`. Just to make sure...

### GIT behavior for this project
Setup your GITHUB- lots of different ways to do this.
At the end of each day, `git push <firstname>-<lastname>`, then have someone review and merge into master.
Before beginning work the next day, `git pull origin master` to start fresh with all updates.



This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

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

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
