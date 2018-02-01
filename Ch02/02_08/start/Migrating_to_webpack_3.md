# Commands
```
cd upgrade-build
npm init -y
npm install webpack@3.1.0 --save-dev
npm install babel-core@6.25.0 --save-dev
npm install babel-loader@7.1.1 --save-dev
npm install babel-preset-env@1.6.0 --save-dev
npm install babel-preset-react@6.24.1 --save-dev
webpack
```

## Optional -- Both can replace `webpack` command
### Option 1. In case webpack error
`./node_modules/.bin/wbpack`
### Option 2. Revise package.json
```
"scripts": {
  "build": "./node_modules/.bin/webpack"
}
```
`npm run build`
