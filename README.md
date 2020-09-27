# gulp-ttf-to-woff

Gulp plugin to convert TTF(TrueType font) files to WOFF using [ttf2woff](https://github.com/fontello/ttf2woff).

## Install

`npm i gulp-ttf-to-woff`

## Usage

```js
const gulp = require("gulp");
const ttfToWoff = require("gulp-ttf-to-woff");

export function convertTffToWoff() {
  return gulp.src("./src/*.ttf").pipe(ttfToWoff()).pipe(gulp.dest("./dist/"));
}
```
