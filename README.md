# Eslint config

Just a eslint config I usually go with for cra. 

## Installation

``` git clone https://github.com/axelca/eslint-config ./ ```

``` mv ./eslint-config/.eslintrc ./ && mv ./eslint-config/.prettierrc ./ && rm -rf ./eslint-config ```

Run these two commands in your current project

## Dependencies

```npm i typescript```

For some reason typescript needs to be installed, gotta look into this

```npm i  eslint-config-prettier eslint-plugin-import eslint-plugin-prettier prettier -D ```


### package.json

```
"scripts": { 
  "lint": "eslint ." 
} 

```

Create a script for eslint, if you're not planning on using the eslint extensions for VS Code.



