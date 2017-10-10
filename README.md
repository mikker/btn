# @mikker/btn

**[DEMO and usage](https://mikker.github.io/btn/demo/)**

A `.btn` class for use with [Tachyons](http://tachyons.io).

Even though Tachyons' strictly functional style is great I always find myself re-adding some kind of base button to every project. This is it.

## Usage

Put this in your html **before** you include Tachyons.

```html
<link rel='stylesheet' href='https://unpkg.com/@mikker/btn@latest/css/btn.css' />
```

Or add it directly to your project:

```sh
npm install @mikker/btn
# or
yarn add @mikker/btn
```

Then using postcss or however you'd like

```css
@import '~tachyons';

@import '~btn';
/* or if you want to customize variables */
@import '~btn/src/btn';
```

**NB: Be sure to include `btn.css` _before_ `tachyons.css.**

## License

MIT
