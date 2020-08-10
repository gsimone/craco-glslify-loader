# Instsall

```bash
yarn add @craco/craco craco-glslify-loader
```

# Usage

```js
const glslLoader = require("craco-glslify-loader");

module.exports = {
  plugins: [
    {
      plugin: glslLoader,
      options: { test: /\.(glsl|vs|fs|vert|frag)$/ },
    },
  ],
};
```
