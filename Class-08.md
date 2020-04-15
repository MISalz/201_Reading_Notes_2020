# Class 08 Notes
## Michelle Salazar

# HTML chp 15

## Building blocks
### Block level elements
start on a new line
\<h1>\<p>\<ul>\<li>

### Inline Elements
flow between surrounding text
\<img>\<b>\<i>

### Containing Elements
**if one block-level element sits inside another block-level element then the outer box is known as te containing or parent element**

It is common to group a number of elements together inside a <div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The <div> element that contains this group of elements is then referred to as the containing element.

### Positioning Schemes
Normal flow: block levels appear on a new line

Relative Positining: moves element from its position to where it should be 

Absolute Positining: positions element in relation to its containing element.

# box offset
***property tell the brower how far from top or bottom left or right it should be placed***

## Fixed positioning
This is a form of absolute positioning that positions
the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

## Floating Elements
Floating an element allows you to take that element outof normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.

When you move any element from normal flow, boxes can overlap. The **z-index** property allows you to control which box appears on top.

## Float 
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible
 using float ot place elements side by side pg371
 float: left; 

 ## Multi-Column Layouts

  This
is achieved by using a <div> element to represent each column. The following three CSS properties are used to position the columns next to each other:
## width
This sets the width of the columns.
## float
This positions the columns next to each other.
## margin
This creates a gap between the columns.

## Layouts
* Fixed width layout designs do not change size as the user increases
or decreases
the size of their browser window. Measurements tend to be given in pixels.
* Liquid layout designs stretch and contract as the user increases or decreases the
size of their browser window. They tend to use percentages.

# CSS frameworks 
aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. 

960.gs Css frameworK ( www.960.gs)
(blueprintcss.org 
(lessframework.com) 
(developer.yahoo.com/yui/grids/)

## Multiple stle sheets
Some authors take an even more modular approach
to stylesheets, creating separate stylesheets to control typography, layout, forms, tables, even different styles for each sub-section of a site.

\@import url ("pagename")

# [Home](https://misalz.github.io/Reading-Notes)