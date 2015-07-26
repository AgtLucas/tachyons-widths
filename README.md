# TACHYONS-WIDTHS

A CSS module of single purpose width classes.

http://tachyons.io

## Install
```
npm install --save-dev tachyons-widths
```
or download the css on github and include in your project.

## The Code
```

@custom-media --breakpoint-not-small screen and (min-width: 48em);
@custom-media --breakpoint-medium screen and (min-width: 48em) and (max-width: 64em);
@custom-media --breakpoint-large screen and (min-width: 64em);

/*

   WIDTHS

   Base:
     w = width

   Modifiers
     1 = 1st step in width scale
     2 = 2nd step in width scale
     3 = 3rd step in width scale
     4 = 4th step in width scale
     5 = 5th step in width scale

     -10  = literal value 10%
     -20  = literal value 20%
     -25  = literal value 25%
     -33  = literal value 33%
     -34  = literal value 34%
     -40  = literal value 40%
     -50  = literal value 50%
     -60  = literal value 60%
     -75  = literal value 75%
     -80  = literal value 80%
     -100 = literal value 100%

     -auto  = string value auto


   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/

/* Width Scale */

.w1 {  width: 1rem; }
.w2 {  width: 2rem; }
.w3 {  width: 4rem; }
.w4 {  width: 8rem; }
.w5 {  width: 16rem; }

.w-10 { width:  10%; }
.w-20 { width:  20%; }
.w-25 { width:  25%; }
.w-33 { width:  33%; }
.w-34 { width:  34%; }
.w-40 { width:  40%; }
.w-50 { width:  50%; }
.w-60 { width:  60%; }
.w-75 { width:  75%; }
.w-80 { width:  80%; }
.w-100 { width: 100%; }

.w-auto { width: auto; }

@media (--breakpoint-not-small) {
  .w1-ns {  width: 1rem; }
  .w2-ns {  width: 2rem; }
  .w3-ns {  width: 4rem; }
  .w4-ns {  width: 8rem; }
  .w5-ns {  width: 16rem; }
  .w-10-ns { width:  10%; }
  .w-20-ns { width:  20%; }
  .w-25-ns { width:  25%; }
  .w-33-ns { width:  33%; }
  .w-34-ns { width:  34%; }
  .w-40-ns { width:  40%; }
  .w-50-ns { width:  50%; }
  .w-60-ns { width:  60%; }
  .w-75-ns { width:  75%; }
  .w-80-ns { width:  80%; }
  .w-100-ns { width: 100%; }
  .w-auto-ns { width: auto; }
}

@media (--breakpoint-medium) {
  .w1-m {      width: 1rem; }
  .w2-m {      width: 2rem; }
  .w3-m {      width: 4rem; }
  .w4-m {      width: 8rem; }
  .w5-m {      width: 16rem; }
  .w-10-m { width:  10%; }
  .w-20-m { width:  20%; }
  .w-25-m { width:  25%; }
  .w-33-m { width:  33%; }
  .w-34-m { width:  34%; }
  .w-40-m { width:  40%; }
  .w-50-m { width:  50%; }
  .w-60-m { width:  60%; }
  .w-75-m { width:  75%; }
  .w-80-m { width:  80%; }
  .w-100-m { width: 100%; }
  .w-auto-m {    width: auto; }
}

@media (--breakpoint-large) {
  .w1-l {      width: 1rem; }
  .w2-l {      width: 2rem; }
  .w3-l {      width: 4rem; }
  .w4-l {      width: 8rem; }
  .w5-l {      width: 16rem; }
  .w-10-l {    width:  10%; }
  .w-20-l {    width:  20%; }
  .w-25-l {    width:  25%; }
  .w-33-l {    width:  33%; }
  .w-34-l {    width:  34%; }
  .w-40-l {    width:  40%; }
  .w-50-l {    width:  50%; }
  .w-60-l {    width:  60%; }
  .w-75-l {    width:  75%; }
  .w-80-l {    width:  80%; }
  .w-100-l {   width: 100%; }
  .w-auto-l {    width: auto; }
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

