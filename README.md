# solink-semantic-release-config

To use, in your project run:

* `npm install --save-dev solink-semantic-release-config semantic-release`
* Add a `"semantic-release": "semantic-release"` script to your package.json.
* Add a GH_TOKEN and NPM_TOKEN to your CI build environment and run `npm run semantic-release` after your tests complete.
* Add the following to a `.releaserc.js` file in the root of your project:

```js
module.exports = {
    extends: 'solink-semantic-release-config',
};
```

* Add a `[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)` badge to your README.md.