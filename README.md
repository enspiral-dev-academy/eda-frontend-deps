# EDA Frontend Dependencies

To apply these dependencies:

    npm install eda-frontend-deps

Available commands

* `test-frontend`
* `watch-frontend-tests`
* `build-frontend`
* `watch-frontend-build`

In your `package.json`, add

```js
"scripts": {
  "client-test": "test-frontend",
  "client-test:watch": "watch-frontend-tests",
  "client-build": "built-frontend",
  "client-build:watch": "watch-frontend-build"
},
```

The `bundle.js` that results from a frontend build will go to `/server/public`.

Requirements

The entry point for your frontend code must be `/client/index.js`.
