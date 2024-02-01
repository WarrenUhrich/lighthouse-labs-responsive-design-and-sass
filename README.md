# Lighthouse Labs | Responsive Design and SASS

* [X] Responsive Design—what is it and why incorporate it?
* [X] Media Queries
* [X] Units in CSS
* [X] Preprocessors -> "Transpiler"
* [ ] Writing Sassy CSS (SCSS)

## Responsive Web Design

Responsive web design is able to (if taken advantage of) ***respond*** to different situations. Some of the most common include:

* Changes in window/display size
* Change in medium that we are viewing the site (screen, print/paper)
* Change in device orientation (landscape, portrait)

This is in contrast to another previous popular practice of having separate desktop and mobile web sites designed:

* facebook.com => designed only for desktops
* m.facebook.com => designed only for mobile devices

## Media Queries

Almost like JavaScript conditionals... we can check certain attributes or conditions for the current environment to determine if we use a block of styles or not!

## List of CSS Units

* `px` A representation of a certain number of pixels per inch of screen.
* `em` A 0-1 percentage representation of the parent's font size.
* `rem` A 0-1 percentage representation of the root element's (`html`) font size.
* `%` Percentage based on parent element size; for font-size it is the same as `em` but in a 0-100 format.
* `ex` Typically a measurement based on the height of the lowercase "x" character in the currently selected font.
* `ch` Typically a measurement based on the width of the zero (0) character in the currently selected font.
* `pt` A point is a physical measurement representing 1/72 of an inch, used in type for printing.
* `pc` A pica is a physical measurement representing 1/36 of an inch, used in type for printing.
* `vw` A percentage (0-100) of the current viewport width.
* `vh` A percentage (0-100) of the current viewport height.
* `vmin` A value representing the smaller of the viewport width or height values.
* `vmax` A value representing the larger of the viewport width or height values.
* `cm`, `mm`, and `in` represent physical measurements in centimetres, millimetres, or inches, respectively, on the screen (or paper, in the case of print.)

## Preprocessors / Transpilers

CSS -> we find it isn't DRY enough. (Maybe I should use more classes.)

Hopefully these syntaxes / "languages" make our life easier. Either providing additional compatibility or developer-friendly features.

Preprocessor / transpiler...
* Sassy
* LESS

Technically not the CSS language...
* my-style.scss
* my-style.sass
* my-style.less

In the JS world there are also preprocessed languages:
* CoffeeScript
* TypeScript

* my-script.coffee
* my-script.ts

The browser ONLY understands:
* HTML
* JS
* CSS

The above HAVE TO COMPILE to a file/syntax that the browser WILL understand.

We can input an SCSS file, for example...
and OUTPUT a CSS file that WILL work.
