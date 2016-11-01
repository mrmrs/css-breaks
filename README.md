# css-breaks 1.0.6

Css module of single purpose classes for breaks

#### Stats

411 | 26 | 78
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-breaks
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-breaks
```

ssh:
```
git clone git@github.com:tachyons-css/css-breaks.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-breaks";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-breaks@1.0.6/css/css-breaks.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-breaks">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   BREAKS
*/
/* Break After */
.ba-aut { -webkit-column-break-after: auto; page-break-after: auto; break-after: auto; }
.ba-al { -webkit-column-break-after: always; page-break-after: always; break-after: always; }
.ba-l { -webkit-column-break-after: left; page-break-after: left; break-after: left; }
.ba-r { -webkit-column-break-after: right; page-break-after: right; break-after: right; }
.ba-rect { -webkit-column-break-after: recto; page-break-after: recto; break-after: recto; }
.ba-vers { -webkit-column-break-after: verso; page-break-after: verso; break-after: verso; }
.ba-page { -webkit-column-break-after: page; page-break-after: page; break-after: page; }
.ba-col { -webkit-column-break-after: column; page-break-after: column; break-after: column; }
.ba-reg { -webkit-column-break-after: region; page-break-after: region; break-after: region; }
.ba-avoid { -webkit-column-break-after: avoid; page-break-after: avoid; break-after: avoid; }
.ba-avoid-page { -webkit-column-break-after: avoid; page-break-after: avoid; break-after: avoid-page; }
.ba-avoid-column { -webkit-column-break-after: avoid-column; page-break-after: avoid-column; break-after: avoid-column; }
.ba-avoid-region { -webkit-column-break-after: avoid-region; page-break-after: avoid-region; break-after: avoid-region; }
/* Break Before */
.bb-aut { -webkit-column-break-before: auto; page-break-before: auto; break-before: auto; }
.bb-al { -webkit-column-break-before: always; page-break-before: always; break-before: always; }
.bb-l { -webkit-column-break-before: left; page-break-before: left; break-before: left; }
.bb-r { -webkit-column-break-before: right; page-break-before: right; break-before: right; }
.bb-rect { -webkit-column-break-before: recto; page-break-before: recto; break-before: recto; }
.bb-vers { -webkit-column-break-before: verso; page-break-before: verso; break-before: verso; }
.bb-page { -webkit-column-break-before: page; page-break-before: page; break-before: page; }
.bb-col { -webkit-column-break-before: column; page-break-before: column; break-before: column; }
.bb-reg { -webkit-column-break-before: region; page-break-before: region; break-before: region; }
.bb-avoid { -webkit-column-break-before: avoid; page-break-before: avoid; break-before: avoid; }
.bb-avoid-page { -webkit-column-break-before: avoid; page-break-before: avoid; break-before: avoid-page; }
.bb-avoid-column { -webkit-column-break-before: avoid-column; page-break-before: avoid-column; break-before: avoid-column; }
.bb-avoid-region { -webkit-column-break-before: avoid-region; page-break-before: avoid-region; break-before: avoid-region; }
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

ISC

