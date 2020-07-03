# aurelia2-shadow-dom-shared-styles

This project is bootstrapped by [aurelia/new](https://github.com/aurelia/new).

These are the answers for `npx makes aurelia` (2020-07-03)

√ Please name this new project: » aurelia2-shadow-dom-shared-styles
√ Would you like to use the default setup or customize your choices? » Custom Aurelia 2 App
√ Which bundler would you like to use? » Webpack
√ What transpiler would you like to use? » TypeScript
√ Do you want to use Shadow DOM or CSS Module? » Use Shadow DOM
√ What CSS preprocessor to use? » Sass (.scss)
√ What unit testing framework to use? » Jest
√ Do you want to setup e2e test? » No
√ What kind of sample code do you want in this project? » With direct routing
[makes] Project aurelia2-shadow-dom-shared-styles has been created.

## Start dev web server

    npm start

## Build the app in production mode

    npm run build

It builds all files to dist folder. To deploy to production server, copy all the `dist/*` files to production root folder.

For example
```
dist/index.html
dist/foo.12345.js
```
Copy to production root folder
```
root_folder/index.html
root_folder/foo.12345.js
```

## Unit Tests

    npm run test

Run unit tests in watch mode.

    npm run test:watch


## Analyze webpack bundle

    npm run analyze
