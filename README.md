# Eslint config

Just a eslint config I usually go with for cra. 

## Installation

``` git clone https://github.com/axelca/eslint-config ./ ```

``` mv ./eslint-config/.eslintrc ./ && rm -rf ./eslint-config ```

Run these two commands in your current project

```npm i typescript```

For some reason typescript needs to be installed, gotta look into this

```npm i  eslint eslint-config-prettier eslint-plugin-import eslint-plugin-prettier prettier -D ```


### package.json

```
"scripts": { 
  "lint": "eslint .",
  "lint:fix": "eslint . --fix" 
} 

```

Create scripts for eslint, if you're not planning on using the eslint extensions for VS Code.



