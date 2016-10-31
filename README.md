# eslint-config-otbs

Use this prepackaged config as your base eslint setup for all OTBS JavaScript projects.

## Installation

```
npm i --save-dev outtherenz/eslint-config-otbs
```

```js
// .eslintrc
{
  extends: 'otbs',
  
  // You'll still need to set up your env
  // http://eslint.org/docs/user-guide/configuring#specifying-environments
  env: {
    browser: true,
    node: true,
    es6: true
  }
}
```
