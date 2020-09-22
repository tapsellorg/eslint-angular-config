# Eslint Angular Config

This repo is an Eslint config for Angular framework and works with both JS and TS files. You can add it to your projects and it correct your code style.

## How to install?

For installing the package and its dependencies run this:

```bash
npm i @tapsellorg/eslint-angular-config eslint prettier
```

Within your ESLint config file `.eslintrc` :

```js
{
    "extends": "@tapsellorg/eslint-angular-config"
}
```

Alter your `eslint` command to include `ts` and `tsx` files:

```bash
npx eslint --ext .js,.jsx,.ts,.tsx ./
```

you can find the package in npm [here](https://www.npmjs.com/package/@tapsellorg/eslint-angular-config).
