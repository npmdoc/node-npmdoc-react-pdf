# npmdoc-react-pdf

#### api documentation for  react-pdf (v1.6.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-pdf.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-pdf) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-pdf.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-pdf)

#### Easily display PDF files in your React application.

[![NPM](https://nodei.co/npm/react-pdf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-pdf)

- [https://npmdoc.github.io/node-npmdoc-react-pdf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-pdf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-pdf/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-pdf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-pdf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-pdf",
    "version": "1.6.1",
    "description": "Easily display PDF files in your React application.",
    "main": "es5/react-pdf.js",
    "es6": "src/react-pdf.jsx",
    "scripts": {
        "build": "npm run build-sample && npm run build-source && npm run build-test",
        "build-sample": "webpack --config webpack.config.sample.js",
        "build-source": "babel src -d es5",
        "build-test": "webpack --config webpack.config.test.js",
        "eslint": "eslint .",
        "prepublish": "npm run build",
        "test": "npm run eslint"
    },
    "keywords": [
        "pdf",
        "pdf-viewer",
        "react"
    ],
    "author": {
        "name": "Wojciech Maj"
    },
    "contributors": [
        {
            "name": "Niklas Närhinen"
        },
        {
            "name": "Bart Van Houtte"
        }
    ],
    "license": "MIT",
    "dependencies": {
        "pdfjs-dist": "^1.7.339",
        "react": ">=15.0",
        "react-dom": ">=15.0"
    },
    "devDependencies": {
        "babel": "^6.23.0",
        "babel-cli": "^6.23.0",
        "babel-core": "^6.23.1",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.3.2",
        "babel-plugin-transform-class-properties": "^6.23.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-react": "^6.23.0",
        "babel-preset-stage-2": "^6.22.0",
        "css-loader": "latest",
        "eslint": "^3.17.0",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-plugin-class-property": "^1.0.3",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.10.0",
        "file-loader": "latest",
        "less": "^2.7.2",
        "less-loader": "latest",
        "style-loader": "latest",
        "url-loader": "latest",
        "webpack": "^2.2.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/wojtekmaj/react-pdf.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
