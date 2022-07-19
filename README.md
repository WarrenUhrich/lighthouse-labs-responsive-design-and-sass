# Lighthouse Labs | Responsive Design and SASS

* [X] Responsive Design—what is it and why incorporate it?
* [X] Media Queries
* [X] Units in CSS
* [ ] Preprocessors
* [ ] Writing Sassy CSS (SCSS)

## What is Responsive Design?

* Design pattern allowing for multiple different layouts depending on how the page is being viewed (which device?)
* "Device" could mean print, or even a screen reader.

## Units

* `px` Represents pixels (16px per inch ratio for consistency.)
* `em` Unit based on parent font-size.
* `rem` Is based on the root element (`HTML`) font size.
* `%` for font-size, is equivalent to `em`, for width/height, it is based on the parent width/height.
* `vw` Unit based on the viewport width (0-100.)
* `vh` Unit based on the viewport height (0-100.)
* `cm`, `in`, `mm` - Okay for print, these are standard physical measurements you are used to.
* `pt` Point is 1/72 of inch.

## Max-Width, Max-Height, Min-Width, Min-Height

We can set the maximum, or minimum space an element takes up. This can be helpful for layout, especially with responsive considerations in mind.

If we're careful with sizing and with our units of choice, we can minimize our use of media queries for different-sized view-ports.

## Media Query

h1 {
    font-size: 18px;
}

@media screen and (min-width: 400px) {
    h1 {
        font-size: 20px;
    }
}

@media screen and (min-width: 1024px) {
    h1 {
        font-size: 48px;
    }
}
