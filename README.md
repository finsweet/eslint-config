# eslint-config

Finsweet's official flat configuration for ESLint.

## How to start

First, install all the devDependencies:

```bash
pnpm add -D @finsweet/eslint-config eslint @eslint/js prettier typescript eslint-config-prettier eslint-plugin-prettier eslint-plugin-simple-import-sort typescript-eslint
```

Then, create a `eslint.config.js` file with the following configuration:

```js
import finsweetConfigs from '@finsweet/eslint-config';

export default [
  ...finsweetConfigs,
  {
    /*... */
  },
  // ...
];
```
