# Class 09 Notes
## Michelle Salazar

# HTML


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