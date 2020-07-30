# ESLint and Prettier Config

These are my settings for using ESLint and Prettier happily together for a Node environment.

## What it does

This setup uses ESLint for catching bugs, and Prettier for formatting.

The basis for the rules is [`eslint-config-airbnb-base`](https://www.npmjs.com/package/eslint-config-airbnb-base). It uses the [`eslint-config-prettier`](https://github.com/prettier/eslint-config-prettier) to turn off the ESLint rules that conflict or are unnecessary when using Prettier.

## Installation and usage

Run the command below:

```bash
npx install-peerdeps -D eslint-config-roboleary-node
```

To use the config, add a **.eslintrc.json** to your project root directory like below:

```json
{
  "extends": ["roboleary-node"]
}
```
