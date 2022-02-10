# Generic linting and formatting rules for front-end JS + VSCode settings

## Steps to re-produce this config on your project:

1. Init an NPM project: `npm init -y`
2. Install prettier and eslint dev dependencies: `npm install eslint --save-dev eslint-config-prettier eslint-plugin-prettier prettier`
3. Init eslint config and customize it base on your needs: `npm init @eslint/config`
4. Create your prettier config and customize it base on your need: `touch .prettierrc`
5. Create NPM scripts for linting and formatting (see example in this repo `package.json`)
6. Create your own .vscode settings or just copy the one in this repo which already has all the recommended extensions
