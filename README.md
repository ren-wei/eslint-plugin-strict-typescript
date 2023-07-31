# eslint-plugin-strict-typescript

For strict rules that include TypeScript.

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-strict-typescript`:

```sh
npm install eslint-plugin-strict-typescript --save-dev
```

## Usage

```json
{
    "root": true,
    "parser": "@typescript-eslint/parser",
    "parserOptions": {
        "ecmaVersion": 6,
        "sourceType": "module"
    },
    "plugins": [
        "@typescript-eslint"
    ],
    "extends": [
        "plugin:strict-typescript/recommend"
    ],
    "ignorePatterns": [
        "out",
        "dist",
    ]
}
```


