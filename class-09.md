# forms 
form is referred to differenet elements that allow you to collect information from visitors to your site.
## form controls
there are several types of form cotrols that you can use to collect information from visitors to your site:
* adding text : text input , password input , text area.
* making choices : radio , checkboxes , drop-down boxes .
* submitting forms : submit buttons , image buttons , file upload.

## how forms work 
1. the user fills in a form and then presses a button to submit the information to the server.
2. the name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language such as PHP, C#, VB.net or Java.
4. The server creates a new page to send back to the browser based on the information received.

A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.
To differentiate between various pieces of inputted data, information is sent from the browser to the server using name/value pairs.

# lists , tables and forms
There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.
In addition to the CSS properties covered in previous reads which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
List markers can be given different appearances using the list-style-type and list-style image properties, Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
Forms are easier to use if the form controls are vertically aligned using CSS and they also benefit from styles that make them feel more interactive.

# events 
there are several kinds of events that always pops up in your face in the web browser: interactions create events.
events trigger code.
code responds to users.

## how events trigger javascript code?
When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code.
1. Selects the element node(s) you want the script to respond to. 
2. Indicate which event on the selected node(s) will trigger the response.
3. State the code you want to run when the event occurs. 

# event flow 
html elements nest inside other elements. if you hover or click on a link,you will also be hovering or clicking on its parent elements.

## why flow matters?
the flow of events only really matters when your code has event handlers on an element and one of its ancestor or descendant elements.
the event will show the html content of that element in an alert box, and event flow will tell you which element the click is registered upon first.

# where events occur 
the event object can tell you where the cursor was positioned when an event was triggered.
* screen:
the screenx and screenY properties indictae the position of the cursor within the entire screen on your monitor.

* page:
the pageX and pageY properties indicate the position of the cursor within the entire page.

* client:
the clientX and clientY properties indicate the position of the cursor within the browser's viewport.

The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.