<p align="center">
<img src="https://github.com/andreyyolkin/vue-undemi/blob/main/assets/banner.png?raw=true" width="600"/>
<br>
<a href='https://www.npmjs.com/package/vue-undemi'><img src='https://img.shields.io/npm/v/vue-undemi?color=42b883' alt='npm'></a>
</p>
<br>

> [!CAUTION]
> This package works only with Vue 3, preserving compatibility with [vue-demi](https://github.com/vueuse/vue-demi/) API

<br>

# Motivation

There are many legacy libraries that have relied on `vue-demi` for a long time and are not yet ready to migrate away from it. This package serves as a drop-in replacement for developers who have such libraries in their projects and wants to simplify dependencies management and project size.

# Install

You can alias `vue-demi` to `vue-undemi` in your `package.json` file:

```jsonc
// npm, bun
{
  "overrides": {
    "vue-demi": "npm:vue-undemi@latest"
  }
}
// pnpm
{
  "pnpm": {
    "overrides": {
      "vue-demi": "npm:vue-undemi@latest"
    }
  }
}
// yarn
{
  "resolutions": {
    "vue-demi": "npm:vue-undemi@latest"
  }
}
```
