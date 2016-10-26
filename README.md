# seed-table [![npm version](https://badge.fury.io/js/seed-table.svg)](https://badge.fury.io/js/seed-table)

table component pack for [Seed](https://github.com/helpscout/seed)!

## Install
```
npm install seed-table --save
```


## Basic Usage

### SCSS
This seed pack needs to be imported into your sass pipeline. Below is an example using Gulp:


```javascript
var gulp = require('gulp');
var sass = require('gulp-sass');
var pack = require('seed-table');

gulp.task('sass', function () {
  return gulp.src('./sass/**/*.scss')
    .pipe(sass({
      includePaths: pack
    }))
    .pipe(gulp.dest('./css'));
});
```

Once that is setup, simply `@import` *seed-table* as needed in your `.scss` file:

```scss
// Packs
@import "pack/seed-table/_index";
```

## Options

The following variables can be found in `_config.scss`

```scss
seed-table config options
```
