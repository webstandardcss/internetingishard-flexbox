# Flexbox
*Nº 8. of HTML & CSS Is Hard*

### A friendly tutorial for modern CSS layouts
The “Flexible Box” or “Flexbox” layout mode offers an alternative to Floats for defining the overall appearance of a web page. Whereas floats only let us horizontally position our boxes, flexbox gives us complete control over the alignment, direction, order, and size of our boxes.

https://internetingishard.com/html-and-css/flexbox/

### Summary
Flexbox gave us a ton of amazing new tools for laying out a web page. Compare these techniques to what we were able to do with floats, and it should be pretty clear that flexbox is a cleaner option for laying out modern websites:

* Use display: flex; to create a flex container.
* Use justify-content to define the horizontal alignment of items.
* Use align-items to define the vertical alignment of items.
* Use flex-direction if you need columns instead of rows.
* Use the row-reverse or column-reverse values to flip item order.
* Use order to customize the order of individual elements.
* Use align-self to vertically align individual items.
* Use flex to create flexible boxes that can stretch and shrink.

Remember that these flexbox properties are just a language that lets you tell browsers how to arrange a bunch of HTML elements. The hard part isn’t actually writing the HTML and CSS code, it’s figuring out, conceptually (on a piece of paper), the behavior of all the necessary boxes to create a given layout.

When a designer hands you a mockup to implement, your first task is to draw a bunch of boxes on it and determine how they’re supposed to stack, stretch, and shrink to achieve the desired design. Once you’ve got that done, it should be pretty easy to code it up using these new flexbox techniques.

The flexbox layout mode should be used for most of your web pages, but there are some things it’s not-so-good at, like gently tweaking element positions and preventing them from interacting with the rest of the page. After covering these kinds of advanced positioning techniques in the next chapter, you’ll be an HTML and CSS positioning expert.

https://internetingishard.com/html-and-css/advanced-positioning/