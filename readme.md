# Buddi Run

## Setup
1. Clone project & download Amplify CLI
```
git clone <git_project_url>
cd <git_project_path>
npm install -g @aws-amplify/cli
```
3. Login to AWS console and retrieve the local setup instructions from the `dev` environment of the Amplify app (Backend environments). After running the command, you'll be given a login id that you'll paste in Amplify CLI then you'll be able to finish your local Amplify configuration.
**Local Amplify setup**
```
default editor: <your choice>
type of app: javascript
framework: react
source directory: react-amplified/src 
build directory: react-amplified/build
build command: <default>
start command: <default>
```
3. Go to `react-amplified` directory and install dependencies
```
cd react-amplified
npm i
```

4. Setup environment variables (they are automatically setup in DEV and PROD environments)
> For the WebGL files, you can download them from S3 or ask any project manager

| key | value |
|---|---|
| REACT_APP_AUTH_DOMAIN | `auth.dev.buddirun.com` |
| REACT_APP_BACKEND_URL | `https://buddirun.dev/api/v1/` |
| REACT_WEBGL_FILES_URL | `unity-webgl-game/` |

5. Run the app
```
npm run start
```

### Development
https://docs.amplify.aws/cli/teams/sandbox/

### NOTES
- `cli.json` can be modified manually (https://docs.amplify.aws/cli/reference/files/#clijson & https://docs.amplify.aws/cli/reference/feature-flags/)








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
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more
information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will
remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right
into your project so you have full control over them. All of the commands except `eject` will still work, but they will
point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you
shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't
customize it when you are ready for it.

## Learn More

You can learn more in
the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved
here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved
here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved
here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved
here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved
here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved
here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
