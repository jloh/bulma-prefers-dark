# bulma-prefers-dark

A Bulma extension that adds support for the `prefers-color-scheme` media query

[![npm](https://img.shields.io/npm/v/bulma-prefers-dark.svg)](https://www.npmjs.com/package/bulma-divider)
[![npm](https://img.shields.io/npm/dm/bulma-prefers-dark.svg)](https://www.npmjs.com/package/bulma-divider)

## Installation

```
npm install --save bulma-prefers-dark
... Or ...
yarn add bulma-prefers-dark
```

<!-- TODO: Add note about doing unpkg stuff -->

## Usage

This extension works as-is in combination with Bulma by adding an alternative dark theme via the [`@media (prefers-color-scheme: dark)` scheme](https://caniuse.com/#search=prefers-color-scheme).

Include it in your SaSS pipeline and you're good to go:

```sass
@import "../../node_modules/bulma/bulma.sass";
@import "../../bulma-prefers-dark/bulma-prefers-dark.sass";
```

<!-- TODO: Add example sites -->

## Copyright & License

Code copyright 2019 James Loh. Code released under the [MIT license](LICENSE).
