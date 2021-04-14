# eslint-config

Finsweet's official configuration for ESLint.

## How to start

First, install all the devDependencies:

```
npm i -D eslint prettier typescript @finsweet/eslint-config eslint-config-prettier eslint-plugin-prettier @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

Then, create a `.eslintrc.js` file with the following configuration:

```javascript
module.exports = { extends: ['@finsweet'] };
```
