# Project 0

##Web Programming with Python and JavaScript

##Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.

Four .html pages: index.html, cv.html, interest.html, contact.html
Each page able to link to each other by click on the navbar

##Your website must include at least one list (ordered or unordered), at least one table, and at least one image.

list
navbar create using list, can be found in each html
in cv.html, working experience list out using unordered list

table
in cv.html, education group by table

image
used in index.html and interest.html

##Your website must have at least one stylesheet file.

stylesheet file: stylesheet.css

##Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.

five different css properties
background-color, font-family, color, min-height, padding, and etc.

five different css selectors
body, h1, p, img, id, class, etc.

id selector
in index.html, using #txtme to tag div for the text in index.html

class selector
in all html page, using .navbar to tag div for navbar

##Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
using the @media query id #contact to have result when smaller screen, the columns will stack on top of each other

##You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.

Bootstrap component
navbar

Bootstrap columns
col-lg-6 col-sm-12 in index.html


##Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.

scss variable
use $dpcolor as variable so able to change font color for certain paragraph easily

scss nesting
in index.html, under id #txtme there are h1 and p, form nesting as: #txtme{ h1{} p{} }

scss inheritance
use %header for @extend purpose to control certain header font-family and color.
