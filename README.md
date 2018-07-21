# Why did you update

[![Build Status](https://travis-ci.org/theKashey/why-did-you-update-redux.svg?branch=master)](https://travis-ci.org/theKashey/why-did-you-update-redux)
[![npm version](https://badge.fury.io/js/why-did-you-update-redux.svg)](https://badge.fury.io/js/why-did-you-update-redux)

Why did you update is a function that monkey patches Redux and notifies you in the console when **potentially** unnecessary re-renders occur
due to a unnecessary update from mapStateToProps.

![](https://i.imgur.com/73vmgG1r.png)

### Setup
This library is available on npm, install it with: `npm install --save why-did-you-update-redux` or `yarn add why-did-you-update-redux`.

### Usage
```js
import 'why-did-you-update-redux';
```
What's all, and it will remove itself from a production bundle.

### How it works

This is basically `import 'beautiful-react-redux/check'`, see 
[beautiful-react-redux](https://github.com/theKashey/beautiful-react-redux) for more information.

### License

MIT