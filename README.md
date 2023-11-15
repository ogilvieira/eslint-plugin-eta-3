# eslint-plugin-eta-3

> Lint your embeddable Eta v3 templates with ease

Based on [eslint-plugin-eta](https://github.com/eta-dev/eslint-plugin-eta) 


### Installation
Run `npm install --save-dev eslint-plugin-eta-3` to install this ESLint plugin.

### Usage
Add this to your ESLint config:
```javascript
module.exports = {
    ...
    plugins: [
        "eta-3"
    ],
    overrides: [
        {
            files: ["*.eta"],
            processor: "eta-3/eta"
        }
    ],
    ...
}
```
