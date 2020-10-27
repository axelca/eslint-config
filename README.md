# Eslint config

Just a eslint config I usually go with for cra. 

## Installation

``` git clone https://github.com/axelca/eslint-config ```

Run this command in the root of your project

``` mv ./eslint-config/.eslintrc ./ && rm -rf ./eslint-config ```

This command copies files to the root of your project

```npm i eslint eslint-config-prettier eslint-plugin-import eslint-plugin-prettier prettier -D ```

This command installs dependencies

### package.json

```
"scripts": { 
  "lint": "eslint .",
  "lint:fix": "eslint . --fix" 
} 

```

Create scripts for eslint, if you're not planning on using the eslint extensions for VS Code.



