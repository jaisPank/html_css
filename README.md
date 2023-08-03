# html_css



Attributes : 

All HTML elements can have attributes
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element



Style: 

Use the style attribute for styling HTML elements
Use background-color for background color
Use color for text colors
Use font-family for text fonts
Use font-size for text sizes
Use text-align for text alignment


CSS in HTML

Use the HTML style attribute for inline styling
Use the HTML <style> element to define internal CSS
Use the HTML <link> element to refer to an external CSS file
Use the HTML <head> element to store <style> and <link> elements
Use the CSS color property for text colors
Use the CSS font-family property for text fonts
Use the CSS font-size property for text sizes
Use the CSS border property for borders
Use the CSS padding property for space inside the border
Use the CSS margin property for space outside the border

List 

HTML lists allow web developers to group a set of related items in lists.
An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.
An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.
HTML also supports description lists.
A description list is a list of terms, with a description of each term.


ID and CLASS

The HTML class attribute is used to specify a class for an HTML element.
Multiple HTML elements can share the same class.
The HTML id attribute is used to specify a unique id for an HTML element.
You cannot have more than one element with the same id in an HTML document.
Difference Between Class and ID
A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page


IFRAME

The HTML <iframe> tag specifies an inline frame
The src attribute defines the URL of the page to embed
Always include a title attribute (for screen readers)
The height and width attributes specify the size of the iframe
Use border:none; to remove the border around the iframe





CSS

CSS stands for Cascading Style Sheets
CSS describes how HTML elements are to be displayed on screen, paper, or in other media
CSS saves a lot of work. It can control the layout of multiple web pages all at once
External stylesheets are stored in CSS files


CSS SYNTAX

A CSS rule consists of a selector and a declaration block.
The selector points to the HTML element you want to style.The declaration block contains one or more declarations separated by semicolons.Each declaration includes a CSS property name and a value, separated by a colon.Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

CSS SELECTORS

CSS selectors are used to "find" (or select) the HTML elements you want to style.We can divide CSS selectors into five categories:

Simple selectors (select elements based on name, id, class)
Combinator selectors (select elements based on a specific relationship between them)
Pseudo-class selectors (select elements based on a certain state)
Pseudo-elements selectors (select and style a part of an element)
Attribute selectors (select elements based on an attribute or attribute value)
CSS CASCADING ORDER

What style will be used when there is more than one style specified for an HTML element?All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

Inline style (inside an HTML element)
External and internal style sheets (in the head section)
Browser default


