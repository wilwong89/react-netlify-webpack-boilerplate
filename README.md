# react-netlify-webpack-boilerplate

> React Starter Boilerplate with Hot Module Replacement and Webpack 4

> Based off the boilerplate by Esau Silva https://github.com/esausilva/react-starter-boilerplate-hmr

Dependencies updated 2020/08/15

### Usage

Install dependencies

```
$ yarn
```

Run development server

```
$ yarn dev
```

Run lambda server

Needs to run in another terminal than dev server

Access lambda functions with localhost:9000/.netlify/functions/(function name)

```
$ yarn lambda
```

### Building

```
$ yarn build
```

Will create a `dist` directory containing your compiled code.

Depending on your needs, you might want to do more optimization to the production build.

## Webpack Bundle Analyzer

Run in development

```
$ yarn dev:bundleanalyzer
```

Run on the production oprimized build

```
$ yarn build:bundleanalyzer
```
