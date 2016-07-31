# CSS with gulp

## Concatenating CSS
+ Install gulp-concat
+ You can specify the order to load files in gulp.src()

## CSS compression

+ Install gulp-minify-css@1.2.2
+ Minification function should be right after CSS concatenation


## Autoprefixer

+ install gulp-autoprefixer@3.1.0
+ Autoprefixer should be right after you use plumber

## Hanlding errors

+ If you make a mistake in CSS, it will crach gulp task
+ than you have to restart gulp watch
+ the solution will be a plugin called plumber
+ plumber should be right after you load the css files


## Adding Source maps
+ install gulp-sourcemaps@1.6.0
+ after you check the css files and right before you output them to destination folder
+ soucemaps.init() and sourcemaps.write()


## SCSS with Gulp

+ install gulp-sass@2.1.1
+ use sass() right after autoprefixer
