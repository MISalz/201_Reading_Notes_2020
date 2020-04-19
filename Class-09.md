# Class 09 Notes
## Michelle Salazar

# HTML

## Form controls
* Adding text
    * text input
    * password input
    * text area
* making choices
    * radio buttons
    * checkboxes
    * drop-down boxes
* submitting forms
    * submit buttons
    * image buttons
* uploading files
    * file upload

## Form Structure
\<form>
\<action>
\<method>
\<id>

## Text Input

is used to create several different form controls

\<input type=\"text" name=\"username" size=\"number" maxlength=\"number"\/>

## Password input
\<input type=\"password" name=\"password" size=\"15" maxlength=\30" \/>

## Text Area
\<textarea name=\"comments" cols=\"20" rows=\"4">Enter
your comments...\</textarea>

## Radio Button
\<input type=\"radio" name=\"genre" value=\"pop" \/>

## Checkbox
\<input type=\"checkbox" name=\"service"
value=\"itunes" checked=\"checked" \/>

## Drop down list
\<select name=\"devices">

\<option value=\"ipod">iPod<\/option>

\<option value=\"radio">Radio<\/option> 

\<option value=\"computer">Computer<\/option>

  \</select>

  ## Submit Button
\<input type=\"submit" name=\"subscribe"
value=\"Subscribe" \/>

## table properties
* **width** to set the width of the table
* **padding** to set the space between the border of each table cell and its content
* **text-transform** to convert the content of the table headers to uppercase
* **letter-spacing, font-size**
to add additional styling to the content of the table headers
* **border-top, border-bottom**
to set borders above and below the table headers
* **text-align** to align the writing to the left of some table cells and to the right of the others
* **background-color** to change the background color of the alternating table rows
* **:hover** to highlight a table row when a user's mouse goes over it

### GAPs betweean cells
border-spacing, border-collapse

table.one \{
border-spacing: 5px 15px;}

table.two \{
border-collapse: collapse;}

**collapse**
Borders are collapsed into a single border where possible. (border-spacing will be ignored and cells pushed together, and empty-cells properties will be ignored.)

**separate**
Borders are detached from each other. (border-spacing and empty-cells will be obeyed.)


# JS
### Events 
UI Events - Occur when a user interacts with the browser's user interface rather than web page
Keyboard Events- occur when a user interacts with the keyboard
Mouse events- occur when a user interacts with a mouse, trackpad or touchscreen
Focus Events - occur when an element gains or loses focus
Form Events- occur when a user interacts with a form element
Mutation Events- occur when the doum structure has been changed by a script.

Events fire or are raised
when an event has occured it is often described as having fired or been raised

Events trigger scripts
Events are said to trigger a function or script

## traditional DOM event handlers
|element.|***on***event|\=functionName:|
---|---|---
Element|Event|Code
DOM element node to target|event bound to node(s) preceded by word "on"| Name function to call (iwth no parentheses following it)

## Event Listener
|element.|addeventlistener|('event',|functionName|\[,boolean])|
---|---|---|---|---|---|
element| |event|code|event flow
dom element node to target| |event to bind node(s) to in quote marks|Name of function to call|indidcates something called captures, and is usually set to false (see p260)

## Form Events
|EVENT |TRIGGER|
---|---|
submit | When a form is submitted, the submit event fires on the node representing the \<form> element. It is most commonly used when checking the values a user has entered into a form before sending it to the server. |
|input| The input event which you saw on the previous page is commonly used with \<input> and \<textarea> elements.|
change | Fires when the status of several form elements change. For example, when:
    • a selection is made from a drop-down select box

    • a radio button is selected

    • a checkbox is selected or deselected 
It is often better to use the change event rather than the c1ick event because clicking is not the only way users interact with form elements (for example, they might use the tab, arrow, or Enter keys.



# [Home](https://misalz.github.io/Reading-Notes)