# supports-avif

Same as [supports-webp](https://www.npmjs.com/package/supports-webp), but for avif

## Install

```shell
pnpm add supports-avif
```

Or you can use npm or yarn.

## Usage

```js
import supportsAvif from 'supports-avif';
// supportsAvif is a Promise

supportsAvif.then((isSupported) => document.body.classList.toggle('avif', isSupported));

// Or use async/await:
if (await supportsAvif) {
	console.log('Load AVIF!');
} else {
	console.log('Load WEBP!');
}
```
