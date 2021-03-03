# Links
Links are the defining feature of the web because they allow you to move from one web page to another.
how can you write links ?
you can use the < a> element to link, you can click on anything between the opening and closing tag of it < a></ a>.
then follow it with the href attribute that contain the source of the page you want to link it so it will look like :

< a href= "http://www.example.com"> x < /a> 

and in order To write good link text, you can think of words people might use when searching for the page that you are linking to, and If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.

# Linking other things
and its not just only for linking pages to each other you can also link emails by adding an email adrress to in the "to" field.
you can also target elements within a page that your linked to by the id attribute. 

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

# 6 reasons for a pair programing 
# how does it work ?
pair programming commonly involves two roles:
 the Driver and the Navigator.
 * The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code.
 * The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs.

 # why?
 Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

and we have more 6 reasons why :
1. Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making.

2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. 

3. Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of.

4. Social skills
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. 

5. Job interview readiness
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. They will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base. 

6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product.