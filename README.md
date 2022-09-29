# vscode-eslint-example

From [ESLint](https://eslint.org/docs/latest/user-guide/getting-started)

## Setup

Set up package.json
>`npm init -y`

You can install and configure ESLint using this command:
>`npm init @eslint/config`

After that, you can run ESLint on any file or directory like this: (won't have to if have vscode plugin installed)
>`npx eslint yourFile.js`

## Format on save

> .vscode/settings.json

``` json
{
   "editor.codeActionsOnSave": {
       "source.fixAll.eslint": true
   },
   "eslint.validate": ["javascript"]

}

```
