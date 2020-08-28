# BS5-Webpack-Boilerplate

A [Webpack 4](https://webpack.js.org/) boilerplate with build-in:

- ECMAScript 6 to ECMAScript 5 transpiling with [babel](https://babeljs.io/) 
- CSS extraction into a single file using [style-loader](https://github.com/webpack-contrib/style-loader), [css-loader](https://github.com/webpack-contrib/css-loader) and [css-mini-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) 
- SCSS support using [sass-loader](https://github.com/webpack-contrib/sass-loader) and [node-sass](https://github.com/sass/node-sass).
- Optimization/Minification with [terser-webpack-plugin](https://github.com/webpack-contrib/terser-webpack-plugin) and [optimize-css-assets-webpack-plugin](https://github.com/NMFR/optimize-css-assets-webpack-plugin). 
- [Bootstrap](https://getbootstrap.com/) SCSS and [Fontawesome](https://fontawesome.com) local fonts support
- Use aliases for easy imports
- [BrowserSync](https://www.browsersync.io/) integration


## Project Structure

```
Project
│
│   README.md
│   package.json
│   webpack.config.js
└───src
│   │
│   └───assets
│       └───js
│            └───index.js
│       └───scss
│            └───styles.scss
│            └───fonts.scss
│            └───bs_overrides.scss
│
└───assets

```

### Commands

#### Development

Run **Webpack** in **Development** mode and start coding!

```
npm run dev
```

#### Production

Run **Webpack** in **Production** mode.

```
npm run build
```

## Setup

### Quick setup

Create a directory for your new project, clone this repository, install the required modules and start coding!

```
mkdir myNewProject && cd myNewProject
clone https://github.com/papegaill/BS5-Webpack-Boilerplate
npm i
npm run dev
```
