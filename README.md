# `<material-ripple>`

This is a port of `@polymer/paper-ripple` to ListElement and ES modules. It also removes Polymer dependencies.

[![Published on NPM](https://img.shields.io/npm/v/@anypoint-web-components/material-ripple.svg)](https://www.npmjs.com/package/@anypoint-web-components/material-ripple)

[![Testing](https://github.com/anypoint-web-components/material-ripple/actions/workflows/deployment.yml/badge.svg)](https://github.com/anypoint-web-components/material-ripple/actions/workflows/deployment.yml)

## Usage

### Installation

```sh
npm i --save @anypoint-web-components/material-ripple
```

### In an HTML file

```html
<html>
  <head>
    <script type="module">
      import '@anypoint-web-components/material-ripple/material-ripple.js';
    </script>
  </head>
  <body>
    <div style="position: relative">
       <material-ripple>Click me</material-ripple>
    </div>
  </body>
</html>
```

## Development

```sh
git clone https://github.com/anypoint-web-components/material-ripple
cd material-ripple
npm install
```

### Running the demo locally

```sh
npm start
```

### Running the tests

```sh
npm test
```
