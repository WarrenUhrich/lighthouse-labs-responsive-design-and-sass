# Lighthouse Labs | Responsive Design and SASS

* [X] Responsive Design—what is it and why incorporate it?
* [X] Media Queries
* [X] Units in CSS
* [ ] Preprocessors
* [ ] Writing Sassy CSS (SCSS)

## Responsive Websites

What is a responsive website?

* An approach website design and development
* The website "responds" to the device screen size, and/or the viewport size

## CSS Units

There are a variety of units we can use to measure in CSS...

* 16px - browsers do work to make a consistant experience, 1px does not necessarily mean 1 actual pixel on your screen
* em and rem
    * em - based on current element's font size
    * rem - based on the root element's font size (`html`)
        * `html {  font-size: 12px; } p { width: 3rem; }`
* % - based on available space (from the parent)
* vh, vw - based on the visible rendered content area

These are more for print...

* cm, mm, in
* pt

## Media Queries

* We can ask the browser how much space is available
* We can ask the browser what medium / format is expected
* We can trigger styles to turn off or on based on the above

For example, we can turn on certain styles if we are trying to print.

```css

@media print { /* Set up a media block...  */
    p { /* These styles will only activate when printing... */
        background-color: white;
        font-size: 1.2cm;
    }
}

p {
    font-size: 16px;
}

@media screen and (min-width: 500px) { /* Screens larger than 500 */
    p {
        font-size: 20px;
    }
}

@media screen and (max-width: 500px) { /* Screens smaller than 500 */
    
}

@media screen and (min-width: 300px) and (max-width: 500px) {
    
}

```
