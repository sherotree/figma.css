# figma.css

> A CSS library for [Figma Semantic Color Tokens](https://figma.com/plugin-docs/css-variables/#list-of-all-available-color-tokens) that converts them to CSS variables.

[![npm][npm-image]][npm-url] [![license][license-image]][license-url]

## Features

- 🚀 Convert Figma color tokens to CSS variables
- 💄 Support for light and dark themes
- 🍱 Easy to integrate with any CSS-in-JS library

## Usage

### Step1: Installation

```sh
npm install --save @sherotree/figma.css
```

### Step2: Importing the Library

Next, you need to import the library into your JavaScript or TypeScript file:

```js
import "@sherotree/figma.css";
```

This will make the CSS variables available in your project.

### Step3: Using the CSS Variables

You can now use the CSS variables in your CSS files. Here's an example:

```css
.my-element {
  background-color: var(--figma-color-bg);
  color: var(--figma-color-text-brand);
}
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE.md)

[license-image]: https://img.shields.io/npm/l/@sherotree/figma.css.svg?style=flat-square
[license-url]: LICENSE.md
[npm-image]: https://img.shields.io/npm/v/@sherotree/figma.css.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/@sherotree/figma.css
