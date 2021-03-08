# Layout
its how to control where each element sits on a page and how to create attractive page layout.

## Key concepts in positioning elements
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
You can control how much space each box takes up by setting the width of the boxes and sometimes the height too To separate boxes, you can useborders, margins, padding, and background colors what ever you want!.

- Block-level elements start on a new line.
- Inline elements flow in between surrounding text.

## Containing Elements
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

## controling the position of the elements
CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS, You can also float elements using the float property :

* Normal flow: 

Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. 

* Relative Positioning:

This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.

* Absolute positioning:

This positions the element in relation to its containing element. 

### To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed.

# Screen Sizes & Screen Resolution
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

# Page Sizes & Fixed Width Layouts
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window, Measurements tend to be given in pixels.

#### advantages and disadvantages of fixed width layouts :
Advantages :
* Pixel values are accurate at controlling size and positioning of elements.
* The designer has far greater control over the appearance and position of items on the page than with liquid layouts.
* You can control the lengths of lines of text regardless of the size of the user's window.
* The size of an image will always remain the same relative to the rest of the page.

Disadvantages:
* You can end up with big gaps around the edge of a page.
* If the user's screen is a much higher resolution than the designer's screen, the page can look smaller and text can be harder to read.
* If a user increases font sizes, text might not fit into the allotted spaces.
* The design works best on devices that have a site or resolution similar to that of desktop or laptop computers.
* The page will often take up more vertical space than a liquid layout with the same content.

# Liquid Layouts
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window, they tend to use percentages.

#### advantages and disadvantages of liquid layouts :
Advantages:
* Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.
* If the user has a small window, the page can contract to fit it without the user having to scroll to the side.
* The design is tolerant of users setting font sizes larger than the designer intended (because the page can stretch).

Disadvantages
* If you do not control the width of sections of the page then the design can look very different than you intended,with unexpected gaps around certain elements or items squashed together.
* If the user has a wide window, lines of text can become very long, which makes them harder to read.
* If the user has a very narrow window, words may be squashed and you can end up with few words on each line.
* If a fixed width item (such as an image) is in a box that is too small to hold it (because the user has made the window smaller) the image can overflow over the text.

# functions, methods & object's
Browsers require very detailed instructions about what we want them to do, and we can achive that by organizing our code by using functions, methods, and objects.

# functions 
Programmers use functions, methods, and objects to organize their code and to create a function you should first declare it and then call it back :

# decalring a function 
by giving it a name and then write the statements needed to achive its task inside a curly braces.(function declaration)
# calling a function
after declaring the function you can then execute all of the statements between its curly braces with just one line of code. (calling the function)


* sometimes a function needs specific information performits task, in such cases when you declare the function you give it parameters inside the function, and when you call it you specify the values it should use in the parantheses that follow its name

* you can also get a single or even multiple values out of the function
such as when we perform a calculation it returns the result. 
multiple functions can return more than one value using an array.