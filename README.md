# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).

# tailwindCssVueDemo

# 构建步骤

```bash
npm init vite my-project
cd my-project

npm install

npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

npx tailwindcss init -p
```

```js
// postcss.config.js
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
};
```

```css
/* ./src/index.css */
@tailwind base;
@tailwind components;
@tailwind utilities;
```

参考：

1. https://v2.tailwindcss.com/docs/guides/vue-3-vite
