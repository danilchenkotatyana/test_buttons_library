# test buttons library

see link:

For install:

$ npm install
$ npm install gulp
$ npm init
$ npm install gulp gulp-watch  gulp-autoprefixer gulp-uglify gulp-sass gulp-sourcemaps gulp-rigger gulp-clean-css gulp-imagemin imagemin-pngquant rimraf browser-sync --save-dev

# Class names in html for buttons:
Use .button for buttons, div, a... This className should be present in the button.

for colors add:
.button__blue, .button__green, .button__grey, .button__orange, .button__red.

for disabled state add .is-disabled, .is-disabled__no-changed or attribute 'disabled'.

for size add:
large size: .button__l-size;
regular, middle size: nothing (default size);
small: .button__s-size;
xsmall: .button__xs-size.

for no min-width: .button__no-width.

for no paddings: .button__no-paddings.

for 100% width: .button__full-width.

