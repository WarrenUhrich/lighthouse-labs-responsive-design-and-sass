# Lighthouse Labs | Responsive Design and SASS

* [X] Responsive Design—what is it and why incorporate it?
* [X] Media Queries
* [X] Units in CSS
* [ ] Preprocessors
* [ ] Writing Sassy CSS (SCSS)

## Responsive Design

* Designing/programming sites to adapt (respond) to all sorts of different devices, browsers, and screen sizes!
* In modern CSS we have media queries (and relative measurements to help us accomodate more responsive designs)

## Media Queries

* In CSS we can use media queries to target different mediums, different screen-sizes, orientations, etc.

```css

@media print {
    img { display: none; }
    p { color: black; }
    html, body { background: white; }
}

/* @media screen and (min-width: 500px) and (max-width: 1000px) {

} */

@media screen and (min-width: 500px) {

}

@media screen and (min-width: 1000px) {
    
}

```

## Units in CSS

* px - pixels (absolute measurement)
* pt
* cm
* in
* % - percent (relative measurement)
    * dependent on the size of the parent element
* vh / vw (relative measurement)
* em - M (relative measurement)
    * The font-size of the parent element (current context)
* rem - relative M (relative measurement)
    * The font-size of the ROOT element (`<html>`) -> most browsers default to 16px

## Pre-processor / Transpiler

* "Pre-Processor": a program that processes/changes something before it runs.
* "Transpiler": a program that changes code in a high-level language into code of another high-level language.
* We can write SCSS code, but it can't run in the browser... we have to convert it into CSS that the browser can understand.

* SCSS -> CSS
* LESS -> CSS
* HTML
* TypeScript -> JS
* CoffeeScript -> JS
