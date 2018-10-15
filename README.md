#Some ReactJS project

#Configuration

Babel
babel-core bable-preset-env (transpile ES6 into ES5) babel-present-react (transpile JSX since it isn't true HTML) babel-loader (this is for webpack) babel-present-stage-0 (we can now use experimental ES7/8 stuff!)

`npm i -D babel-core babel-loader babel-preset-env babel-preset-react babel-preset-stage-0`

Bundler (w/ Webpack)
webpack webpack-cli (run webpack commands on cli) webpack-dev-server (nodemon for React) webpack-merge (this allows for dev, staging, prod configurations easily)

`npm i -D webpack webpack-cli webpack-dev-server webpack-merge`

SASS/CSS specific
sass-loader node-sass css-loader style-loader

`npm i -D sass-loader node-sass css-loader style-loader`

HTML
html-webpack-plugin

`npm i -D sass-loader node-sass css-loader style-loader html-webpack-plugin`

React
react react-dom (actually allow React to manipulate the DOM) dotenv

`npm i -D react react-dom dotenv`
