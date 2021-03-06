# Objects
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.
VARIABLES BECOME KNOWN AS PROPERTIES, FUNCTIONS BECOME KNOWN AS METHODS.
## creating an object literal notation
literal notation is the easiest and most popular way to create objects.
the object is the curly braces and their contents and can be stored in a variable .
## accessing an object and dot notation
you can access the properties or methods of an object using dot notation, or using square brackets.

# document object model (DOM)
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

## caching DOM queries
methods that find elements in the DOM tree are called Dom queries, when you need to work with an element more than once, you should use a variable for storing the result of this query.
storing elements in variables are storing the location of the elements within the DOM tree in a variable.
## methods that select individual elements
for selecting an individual element you can use getElementById or queryselector, both of them use a similar syntax but the getelementbyid is quickest and most efficient, and the queryselector is used to target more elements.
## selecting an element from a nodelist
and we can do that in two ways, the item method and the array syntax, both of the requires the index number of the element you want.
the array syntax is preferred over the item method because it is faster.
## repeating actions for an entire nodelist
you can loop through each node in the collection and apply the same statement in the nodelist.
## adding or removing HTML content 
there are two different approaches to adding and removing content from a DOM tree, the innerHTML property and the DOM manipulation.
using the innerHTML property leads to a security risks associated, while the DOM manipulation easily targets individual nodes in the DOM tree whereas innerHTML is better suited to updating entire fragments.
## attribute nodes
once you have an element node you can use other properties and methods on that element node to access and change its attributes.