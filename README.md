# prettier-config

> Shared [Prettier config](https://prettier.io/docs/en/configuration.html) for my projects

## Install

```sh
npm install --save-dev @mhld/prettier-config
```

## Usage

Add in your `package.json`

```json
  {
    "prettier": "@mhld/prettier-config"
  }
```

If you want to overwrite some properties, update your project's `prettier.config.js` file to import the rule sets you want:

```js
module.exports = {
  ...require('@mhld/prettier-config'),
  // your overrides here
};
```

---

Read the [Prettier config docs](https://prettier.io) for more information.
