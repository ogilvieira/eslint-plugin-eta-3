# eslint-plugin-eta-3

<span align="center">

[![Travis](https://img.shields.io/travis/com/ogilvieira/eslint-plugin-eta-3/master.svg)](https://travis-ci.com/eta-dev/eslint-plugin-eta)
[![Coveralls](https://img.shields.io/coveralls/ogilvieira/eslint-plugin-eta-3.svg)](https://coveralls.io/github/eta-dev/eslint-plugin-eta)

</span>

> Lint your embeddable Eta templates with ease



### Installation
Run `npm install --save-dev eslint-plugin-eta-3` to install this ESLint plugin.

### Usage
Add this to your ESLint config:
```javascript
module.exports = {
    ...
    plugins: [
        "eta"
    ],
    overrides: [
        {
            files: ["*.eta"],
            processor: "eta/eta"
        }
    ],
    ...
}
```
