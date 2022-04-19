# @dinehq/project-config

## Description

This is the basic configuration of the project, including `prettier` and `eslint`, and you can install the package for quick configuration of the project directly.

## Installation

```
pnpm add @dinehq/project-config
```

```
npm install @dinehq/project-config
```

```
yarn add @dinehq/project-config
```

## PeerDependencies

```json
{
  "@typescript-eslint/eslint-plugin": "^5.20.0",
  "@typescript-eslint/parser": "^5.20.0",
  "eslint": "^8.13.0",
  "eslint-config-prettier": "^8.5.0",
  "eslint-config-standard": "17.0.0-1",
  "eslint-plugin-import": "^2.26.0",
  "eslint-plugin-n": "^14.0.0",
  "eslint-plugin-prettier": "^4.0.0",
  "eslint-plugin-promise": "^6.0.0",
  "eslint-plugin-react": "^7.29.4",
  "eslint-plugin-react-hooks": "^4.4.0",
  "prettier": "^2.6.2",
  "typescript": "^4.6.3"
}
```

## Config

### .eslintrc.js

```js
/* eslint-disable */
const { eslintrc } = require('@dinehq/project-config')

module.exports = eslintrc
```

### .prettierrc.js

```js
const { prettierrc } = require('@dinehq/project-config')

module.exports = prettierrc
```

## Reference

https://prettier.io/

https://eslint.org/

## Contribution

@limichange
