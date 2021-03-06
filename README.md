# prepack-webpack

Example for Getting started and integrating webpack with prepack (https://github.com/facebook/prepack) using prepack-webpack-plugin.

## With webpack
![bundle.js takes 3.4 kb](https://github.com/nagarakesh4/prepack-webpack/blob/master/withoutRemovingCompiletime.png)

## With Prepack-Webpack-plugin
![bundle.js takes 19 b](https://github.com/nagarakesh4/prepack-webpack/blob/master/withRemovingCompiletime.png)

## Steps
1. Clone this repository (git clone <https://github.com/nagarakesh4/prepack-webpack.git>)
2. cd into 'prepack-webpack'

### Install webpack
3. yarn add webpack

### verify without prepack-webpack plugin
4. remove plugin code from webpack.config.js as shown below
![webpack.config.js without prepack-webpack plugin](https://github.com/nagarakesh4/prepack-webpack/blob/master/webpack-config-without-prepack-plugin.png)
5. run 'webpack' and check the bundle.js file

### Install prepack-webpack-plugin
6. add prepack-webpack-plugin code to webpack.config.js (view code in this repository)
7. install plugin - yarn add prepack-webpack-plugin
8. run 'webpack' and check the bundle.js file
