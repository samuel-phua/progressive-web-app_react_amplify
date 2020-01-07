# Progressive Web App with React and Amplify
Create lightning fast web apps with native power using React and the Amplify framework

### Project Structure
- build
- [public](public)
  - [assets](public/assets)
  - [index.html](public/index.html)
- [src](src)
  - [components](src/components)
    - [app.css](src/app.css)
    - [App.js](src/App.js)
  - [index.js](src/index.js)
- [package.json](package.json)
- [webpack.config.js](webpack.config.js)
- [webpack.config.prod.js](webpack.config.prod.js)

### Setup
1. [Webpack](https://webpack.js.org/guides/installation/) for bundling files
2. [Webpack Dev Server](https://webpack.js.org/guides/development/) for reloading the page when changes are made
3. [BabelLoader](https://www.npmjs.com/package/babel-loader) for transpiling ES6 to ES5
4. [React Hot Loader](https://www.npmjs.com/package/react-hot-loader) for reloading JS while preserving the current state of the application without reloading the page itself
5. [HtmlWebpackPlugin](https://www.npmjs.com/package/html-webpack-plugin) for minifying HTML
6. [CSSLoader](https://www.npmjs.com/package/css-loader) & [StyleLoader](https://www.npmjs.com/package/style-loader) for minifying CSS
7. [UglifyJsPlugin](https://www.npmjs.com/package/uglifyjs-webpack-plugin) for uglifying JS
8. [FileLoader](https://www.npmjs.com/package/file-loader) for copying assets required by JS code to build
9. Custom [copy_assets.js](scripts/copy_assets.js) script to copy all assets to build
10. [ManifestPlugin](https://www.npmjs.com/package/webpack-manifest-plugin) for generating a list of assets and saving it to build
11. [Firebase](https://firebase.google.com/docs/web/setup) for backend infrastructure
12. [React Router DOM](https://reacttraining.com/react-router/web/guides/quick-start) for routing
13. [Babel Polyfill](https://www.npmjs.com/package/@babel/polyfill) for async/await
14. [Syntax Dynamic Import Plugin](https://babeljs.io/docs/en/babel-plugin-syntax-dynamic-import) for code splitting
