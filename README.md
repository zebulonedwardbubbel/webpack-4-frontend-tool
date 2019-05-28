# webpack4-front-end-tool

  - compiles [Sass](https://sass-lang.com/) / SCSS to CSS
  - [PostCSS](https://postcss.org/) + [Autoprefixer](https://autoprefixer.github.io/) + [CSSNano](http://cssnano.co/)
  - [Hot Module Replacement (HMR)](https://webpack.js.org/concepts/hot-module-replacement/)
  - extracts CSS into separate files in production mode with [MiniCssExtractPlugin](https://webpack.js.org/plugins/mini-css-extract-plugin/)
  - transpiles JavaScript using [Babel](https://babeljs.io/)
  - JavaScript polyfilling with [@babel/polyfill](https://babeljs.io/docs/en/babel-polyfill), used with [@babel/preset-env](https://babeljs.io/docs/en/babel-preset-env) and the experimental [useBuiltIns: "usage" option](https://babeljs.io/docs/en/babel-preset-env#usebuiltins-usage-experimental), which provides specific imports for polyfills when they are used in each file. As a result, the bundler will load the same polyfill only once.
  - JavaScript linting via [ESLint](https://eslint.org/)
  - code splitting via [SplitChunksPlugin](https://webpack.js.org/plugins/split-chunks-plugin/)
  - [HtmlWebpackPlugin](https://github.com/jantimon/html-webpack-plugin)
