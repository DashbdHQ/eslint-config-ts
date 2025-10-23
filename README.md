# @dashbd/eslint-config-ts

Opinionated ESLint configuration for Typescript/React JSX files.

## Installation

```bash
npm install --save-dev @dashbd/eslint-config-ts eslint prettier
```

## Usage (Flat Config)

`eslint.config.js` example:
    
```js
import dashbdConfig from "@dashbd/eslint-config-ts";

export default [
    ...
    dashbdConfig,
    ...
];
```
