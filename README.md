# css-breaks 0.0.7

Css module of single purpose classes for breaks

#### Stats

264 | 26 | 26
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-breaks
```

#### With Git

```
git clone https://github.com/tachyons-css/css-breaks
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-breaks";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-breaks">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   BREAKS
*/
/* Break After */
.ba-aut { break-after: auto; }
.ba-al { break-after: always; }
.ba-l { break-after: left; }
.ba-r { break-after: right; }
.ba-rect { break-after: recto; }
.ba-vers { break-after: verso; }
.ba-page { break-after: page; }
.ba-col { break-after: column; }
.ba-reg { break-after: region; }
.ba-avoid { break-after: avoid; }
.ba-avoid-page { break-after: avoid-page; }
.ba-avoid-column { break-after: avoid-column; }
.ba-avoid-region { break-after: avoid-region; }
/* Break Before */
.bb-aut { break-before: auto; }
.bb-al { break-before: always; }
.bb-l { break-before: left; }
.bb-r { break-before: right; }
.bb-rect { break-before: recto; }
.bb-vers { break-before: verso; }
.bb-page { break-before: page; }
.bb-col { break-before: column; }
.bb-reg { break-before: region; }
.bb-avoid { break-before: avoid; }
.bb-avoid-page { break-before: avoid-page; }
.bb-avoid-column { break-before: avoid-column; }
.bb-avoid-region { break-before: avoid-region; }
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

