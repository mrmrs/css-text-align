# css-text-align 0.0.6

Css module of single purpose classes for text align

#### Stats

331 | 44 | 44
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-text-align
```

#### With Git

```
git clone https://github.com/tachyons-css/css-text-align
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-text-align";
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
<link rel="stylesheet" href="path/to/module/css/css-text-align">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TEXT ALIGN
*/
.tl { text-align: left; }
.tr { text-align: right; }
.tc { text-align: center; }
.tj { text-align: justify; }
.ts { text-align: start; }
.te { text-align: end; }
.tmp { text-align: match-parent; }
.tse { text-align: start end; }
.tp { text-align: "."; }
.tsp { text-align: start "."; }
.tpe { text-align: "." end; }
@media screen and (min-width: 48em) {
 .tl-ns { text-align: left; }
 .tr-ns { text-align: right; }
 .tc-ns { text-align: center; }
 .tj-ns { text-align: justify; }
 .ts-ns { text-align: start; }
 .te-ns { text-align: end; }
 .tmp-ns { text-align: match-parent; }
 .tse-ns { text-align: start end; }
 .tp-ns { text-align: "."; }
 .tsp-ns { text-align: start "."; }
 .tpe-ns { text-align: "." end; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .tl-m { text-align: left; }
 .tr-m { text-align: right; }
 .tc-m { text-align: center; }
 .tj-m { text-align: justify; }
 .ts-m { text-align: start; }
 .te-m { text-align: end; }
 .tmp-m { text-align: match-parent; }
 .tse-m { text-align: start end; }
 .tp-m { text-align: "."; }
 .tsp-m { text-align: start "."; }
 .tpe-m { text-align: "." end; }
}
@media screen and (min-width: 64em) {
 .tl-l { text-align: left; }
 .tr-l { text-align: right; }
 .tc-l { text-align: center; }
 .tj-l { text-align: justify; }
 .ts-l { text-align: start; }
 .te-l { text-align: end; }
 .tmp-l { text-align: match-parent; }
 .tse-l { text-align: start end; }
 .tp-l { text-align: "."; }
 .tsp-l { text-align: start "."; }
 .tpe-l { text-align: "." end; }
}
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
