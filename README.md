<div align="center">
  <img width="220" height="220" src="https://webpack.js.org/assets/icon-square-big.svg">
  <h1>Webpack-Babel-Sass Boilerplate</h1>
  <p>A webpack boilerplate with Babel and Sass/ SCSS</p>
</div>

## Features
* Webpack 4 bundling
* ES6 support
* Sass support
* Live reload using Webpack Dev Server
* HTML Loader
* File Loader
* HTML Webpack Plugin
* Mini CSS Extract Plugin to extract CSS into separate files
* Clean Webpack Plugin to clean dist folder

## Requirement
Install [Node.js](https://nodejs.org/en/).

## Usage

### Getting Started

Clone the repo into a new project folder, e.g. `MyApp`.

```bash
$ git clone https://github.com/nadiannis/webpack-babel-sass-boilerplate.git MyApp
$ cd MyApp
```

Delete the old `.git` history, then initialize new `.git` repo.

```bash
$ rm -rf .git
$ git init
```

### Setup
Install the dependencies.
```bash
$ npm install
```

### Development
Run the local webpack-dev-server & open [http://localhost:8080/](http://localhost:8080/)
```bash
$ npm run dev
```

### Production
Build the application.
```bash
$ npm run build
```

## License

MIT © [Annisa Nadia](https://github.com/nadiannis)