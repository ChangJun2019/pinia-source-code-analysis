# `@pinia/nuxt`

> Nuxt 2 & 3 module

## Installation

```sh
npm i @pinia/nuxt
```

## Usage

Add to `buildModules` in `nuxt.config.js`:

```js
export default {
  buildModules: [['@pinia/nuxt', { disableVuex: true }]],
}
```

Note you also need `@nuxtjs/composition-api` if you are using Nuxt 2 without Bridge. [Refer to docs for more](https://pinia.esm.dev/ssr/nuxt.html).

## License

[MIT](http://opensource.org/licenses/MIT)
