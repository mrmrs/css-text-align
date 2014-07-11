# CSS TEXT ALIGN

  Mobile-first classes for css-text-align.
  Set the desired css-text-align on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-text-align
```
or download the css on github and include in your project.

## File Size


## The Code
```
.tl  { text-align: left; }
.tr  { text-align: right; }
.tc  { text-align: center; }
.tj  { text-align: justify; }
.ts  { text-align: start; }
.te  { text-align: end; }
.tmp { text-align: match-parent; }
.tse { text-align: start end; }
.tp  { text-align: "."; }
.tsp { text-align: start "."; }
.tpe { text-align: "." end; }

@media screen and (min-width: 48em) {
  .tl-ns  { text-align: left; }
  .tr-ns  { text-align: right; }
  .tc-ns  { text-align: center; }
  .tj-ns  { text-align: justify; }
  .ts-ns  { text-align: start; }
  .te-ns  { text-align: end; }
  .tmp-ns { text-align: match-parent; }
  .tse-ns { text-align: start end; }
  .tp-ns  { text-align: "."; }
  .tsp-ns { text-align: start "."; }
  .tpe-ns { text-align: "." end; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .tl-m  { text-align: left; }
  .tr-m  { text-align: right; }
  .tc-m  { text-align: center; }
  .tj-m  { text-align: justify; }
  .ts-m  { text-align: start; }
  .te-m  { text-align: end; }
  .tmp-m { text-align: match-parent; }
  .tse-m { text-align: start end; }
  .tp-m  { text-align: "."; }
  .tsp-m { text-align: start "."; }
  .tpe-m { text-align: "." end; }
}

@media screen and (min-width: 64em)  {
  .tl-l  { text-align: left; }
  .tr-l  { text-align: right; }
  .tc-l  { text-align: center; }
  .tj-l  { text-align: justify; }
  .ts-l  { text-align: start; }
  .te-l  { text-align: end; }
  .tmp-l { text-align: match-parent; }
  .tse-l { text-align: start end; }
  .tp-l  { text-align: "."; }
  .tsp-l { text-align: start "."; }
  .tpe-l { text-align: "." end; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

