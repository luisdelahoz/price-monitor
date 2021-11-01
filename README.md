# Starter Template

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and it has installed and configured the following packages:

- esbuild instead of webpack.
- eslint with airbnb styleguide.
- prettier (formatter).
- husky and lint-staged to run a pre-commit hook (eslint + prettier + tests).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn test:watch`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

## Prettier with Visual Studio Code

To use it, you need to do the following:

- Install [Prettier - Code Formatter extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode).
- Set Prettier as the default formatter in User Settings (Text Editor > Editor: Default Formatter).
- Check that eslint is not enable as formatter (Text Editor > Eslint > Format).
- Verify that the file types you want to format do not have a specific formatter in User Settings JSON (for more information check the prettier extension documentation).
- Optional: install [Formatting Toggle extension](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle) to have the option to enable / disable formatting using the button located at the bottom right of the editor.
