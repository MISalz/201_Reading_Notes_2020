# Class 02 Notes
## Michelle Salazar

|book| chp|
---|---
|HTML| chp2, chp10|
|JS| chp2, chp4|


White space collapsing - spacing in editor will not be be spaced in real time
to add spacing you can use \<br>
add emphasis by using \<em>>
\<blockquote> is used for longer quotes to stand alone

CSS uses \{} to identify style elements
|Selector |Declaration |
---|---
p| \{fontfamily:arial};

**selector** indidcates which element to apply the rule to
**declaration** indicates how the selector should behave

|selector|meaning|example
---|---|---|
|Universal Selector| Applies to all elements in the document|\* \{} Targets all elements on the page|
|Type Selector|Matches element names| h1, h2, h3 \{} Targets the \<h1>, \<h2> and \<h3> elements |
|Class Selector|Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol|\.note \{} Targets any element whose class attribute has a value of note \p.note \{} Targets only \<p> elements whose class attribute has a value of note
ID Selector| Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol|\#introduction \{} Targets the element whose id attribute has a value of introduction
Child Selector|Matches an element that is a direct child of another|li>a {}Targets any \<a> elements that are children of an \<li> element (but not other \<a> elements in the page)
Descendant Selector|Matches an element that is a descendent of another specified element (not just a direct child of that element)| p a \{} Targets any \<a> elements that sit inside a \<p> element, even if there are other elements nested between them 
Adjacent Sibling Selector|Matches an element that is the next sibling of another|h1+p \{} Targets the first \<p> element after any \<h1> element \(but not other \<p> elements) 
General Sibling Selector|Matches an element that is a sibling of another, although it does not have to be the directly preceding element|h1~p \{} If you had two \<p> elements that are siblings of an \<h1> element, this rule would apply to both

# [Home](https://misalz.github.io/Reading-Notes)