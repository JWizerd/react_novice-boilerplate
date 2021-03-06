# react_novice-boilerplate

### a beginner boilerplate for using React and React-DOM with Webpack for Task Running and Babel for Compiling to meet browser dependencies with ES2015 and React

##Useful Commands

make webpack watch for changes
```
./node_modules/.bin/webpack -d --watch
```

install webpack (-S is a flag for --save)
```
npm i webpack -S
```

install babel
```
npm i babel-loader babel-core babel-preset-es2015 babel-preset-react -S
```

use npm as a tool runner with webpack
```
{
  // ...
  "scripts": {
    "dev": "webpack -d --watch",
    "build" : "webpack -p"
  },
  // ...
}
```
Now the command npm run build runs Webpack in production mode, which minimizes the bundle file automatically, and the command npm run dev runs the Webpack in the watch mode.

### to see tutorial check out this article on [codementor.io](https://www.codementor.io/tamizhvendan/beginner-guide-setup-reactjs-environment-npm-babel-6-webpack-du107r9zr)
