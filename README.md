# restart.css

Reset styles globally.

This is a **global styling reset**, best used with and after 
[Normalize](http://necolas.github.io/normalize.css/) (and any other normalizing 
libraries such as [Rationalize](https://github.com/niksy/rationalize.css)) and 
with caution!

Goes best with screen display. Print display may (drastically) vary.

## Features

* "Carpet bombing" of all margins, paddings and borders on elements
* Borders are left on input elements so you can adjust them accordingly
* […and much more](https://github.com/niksy/restart.css/blob/master/index.css)

## Install

```sh
npm install restart.css --save
```

## Usage

```css
@import url('restart.css');
```

## Browser support

Tested in IE9+ and all modern browsers.

## Test

For manual tests, run `npm run test:manual` and open <http://localhost:9000/> in your browser.

## License

MIT © [Ivan Nikolić](http://ivannikolic.com)
