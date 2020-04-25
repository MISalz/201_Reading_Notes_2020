# Class 11 Notes
## Michelle Salazar

# HTML

aligning images can be done by using float property witha  class property

**by default images are inline elements**
* In order to center an image it should be turned into a block element ex \<p>
you can use the text-align property to center the value

to add a image to backgound use - background-image:
### Repeating images
background-attachment: | |
---|---
Repeat | The background image is repeated both horizontally and vertically (the default way it is shown if the background- repeat property isn't used).
repeat-x | The image is repeated horizontally only (as shown in the first example on the left).
repeat-y| The image is repeated vertically only.
no-repeat |The image is only shown once. 


The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values:| |
---|---
| fixed | The background image stays in the same position on the page.
| scroll | The background image moves up and down as the user scrolls up and down the page.

background position: \(to align the image to particular area in the page)

## background short hand
background:  The properties must be specified in the following order, but you can miss any value if you do not want to specify it.|
---|---
1: background-color |
2: background-image |
3: background-repeat |
4: background-attachment |
 5: background-position |

## CSS3 will also support the use of multiple background images by repeating the background shorthand. |
 ---|---
 div \{ background:
url\(example-1.jpg)
top left no-repeat, url\(example-2.jpg) bottom left no-repeat, url|(example-3.jpg) centre top repeat-x;}

## image rollovers and sprites pg 417 using css it is possible to create a link or button that changes to a second sytle when a user moves their mouse over it. 
# [Home](https://misalz.github.io/Reading-Notes)
