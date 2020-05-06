# Typescript + NodeJS Development Enviroment :blush:

#### References:
https://github.com/i0natan/nodebestpractices
https://github.com/Microsoft/tsdoc


## To start the project. :smirk:

git clone https://github.com/ygorazambuja/env-typescript-node new-project \
cd new-project \
**Windows**: Remove-Item .\.git\ -Recurse -Force \
**Linux**: rm -rf .git \
git init 


### Basic configuration for VSCode :satisfied:

```json
{
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "[typescript]": { "editor.formatOnSave": false },
  "[typescriptreact]": { "editor.formatOnSave": false }
}
```

```json
{
  "eslint.autoFixOnSave": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    {
      "language": "typescript",
      "autoFix": true
    },
    {
      "language": "typescriptreact",
      "autoFix": true
    }
  ]
}
```
#### Dev Dependencies. :smile:

```json
{
  "devDependencies": {
    "@typescript-eslint/eslint-plugin": "^2.31.0",
    "@typescript-eslint/parser": "^2.31.0",
    "eslint": "^6.8.0",
    "eslint-config-prettier": "^6.11.0",
    "eslint-config-standard": "^14.1.1",
    "eslint-plugin-import": "^2.16.0",
    "eslint-plugin-node": "^11.1.0",
    "eslint-plugin-prettier": "^3.0.1",
    "eslint-plugin-promise": "^4.0.1",
    "eslint-plugin-standard": "^4.0.0",
    "husky": "^4.2.5",
    "nodemon": "^2.0.3",
    "prettier": "^2.0.5",
    "sucrase": "^3.10.0",
    "typescript": "^3.8.3"
  }
}
```
