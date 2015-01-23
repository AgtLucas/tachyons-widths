# TACHYONS-WIDTHS

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-widths
```
or download the css on github and include in your project.

## The Code
```

@custom-media --breakpoint-not-small screen and (max-width: 48em);
@custom-media --breakpoint-medium screen and (min-width: 48em) and (max-width: 64em);
@custom-media --breakpoint-large screen and (min-width: 64em);

/*

   WIDTHS

*/

/* Width Scale */

.wi1 {  width: 1rem; }
.wi2 {  width: 2rem; }
.wi3 {  width: 4rem; }
.wi4 {  width: 8rem; }
.wi5 {  width: 16rem; }

.wi-10 { width:  10%; }
.wi-20 { width:  20%; }
.wi-25 { width:  25%; }
.wi-40 { width:  40%; }
.wi-50 { width:  50%; }
.wi-60 { width:  60%; }
.wi-75 { width:  75%; }
.wi-80 { width:  80%; }
.wi-100 { width: 100%; }

/* Width String Properties */

.wi-bb { width: border-box; }
.wi-cb { width: content-box; }
.wi-mx { width: max-content; }
.wi-mn { width: min-content; }
.wi-av { width: available; }
.wi-fc { width: fit-content; }
.wi-at { width: auto; }
.wi-i {  width: inherit; }

@media (--breakpoint-not-small) {
  .wi1-ns {  width: 1rem; }
  .wi2-ns {  width: 2rem; }
  .wi3-ns {  width: 4rem; }
  .wi4-ns {  width: 8rem; }
  .wi5-ns {  width: 16rem; }
  .wi-10-ns { width:  10%; }
  .wi-20-ns { width:  20%; }
  .wi-25-ns { width:  25%; }
  .wi-40-ns { width:  40%; }
  .wi-50-ns { width:  50%; }
  .wi-60-ns { width:  60%; }
  .wi-75-ns { width:  75%; }
  .wi-80-ns { width:  80%; }
  .wi-100-ns { width: 100%; }
  .wi-bb-ns { width: border-box; }
  .wi-cb-ns { width: content-box; }
  .wi-mx-ns { width: max-content; }
  .wi-mn-ns { width: min-content; }
  .wi-av-ns { width: available; }
  .wi-fc-ns { width: fit-content; }
  .wi-at-ns { width: auto; }
  .wi-i-ns {  width: inherit; }
}

@media (--breakpoint-medium) {
  .wi1-m {      width: 1rem; }
  .wi2-m {      width: 2rem; }
  .wi3-m {      width: 4rem; }
  .wi4-m {      width: 8rem; }
  .wi5-m {      width: 16rem; }
  .wi-10-m { width:  10%; }
  .wi-20-m { width:  20%; }
  .wi-25-m { width:  25%; }
  .wi-40-m { width:  40%; }
  .wi-50-m { width:  50%; }
  .wi-60-m { width:  60%; }
  .wi-75-m { width:  75%; }
  .wi-80-m { width:  80%; }
  .wi-100-m { width: 100%; }
  .wi-bb-m {    width: border-box; }
  .wi-cb-m {    width: content-box; }
  .wi-mx-m {    width: max-content; }
  .wi-mn-m {    width: min-content; }
  .wi-av-m {    width: available; }
  .wi-fc-m {    width: fit-content; }
  .wi-at-m {    width: auto; }
  .wi-i-m {     width: inherit; }
}

@media (--breakpoint-large) {
  .wi1-l {      width: 1rem; }
  .wi2-l {      width: 2rem; }
  .wi3-l {      width: 4rem; }
  .wi4-l {      width: 8rem; }
  .wi5-l {      width: 16rem; }
  .wi-10-l {    width:  10%; }
  .wi-20-l {    width:  20%; }
  .wi-25-l {    width:  25%; }
  .wi-40-l {    width:  40%; }
  .wi-50-l {    width:  50%; }
  .wi-60-l {    width:  60%; }
  .wi-75-l {    width:  75%; }
  .wi-80-l {    width:  80%; }
  .wi-100-l {   width: 100%; }
  .wi-bb-l {    width: border-box; }
  .wi-cb-l {    width: content-box; }
  .wi-mx-l {    width: max-content; }
  .wi-mn-l {    width: min-content; }
  .wi-av-l {    width: available; }
  .wi-fc-l {    width: fit-content; }
  .wi-at-l {    width: auto; }
  .wi-i-l {     width: inherit; }
}

```

## Author

[mrmrs](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

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

