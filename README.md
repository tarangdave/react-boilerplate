# react-boilerplate
A Basic react boilerplate that uses gulp, webpack, babel, react-router with ES6 syntax

## Installing and Running

To start, make sure you're in the `react-boilerplate` folder in command-line.

```sh
# Install Node Modules
npm install

# Start the Server
gulp

# If you want to edit the react code, this rebuilds
gulp watch
```

> The server will be available at localhost:3000

If you want to edit the React code, you'll have to re-build the `public/js/bundle.js` file with Webpack. You'll probably want to open a new terminal tab so you can keep your server running. To rebuild with webpack, type:

```sh
gulp watch
```
