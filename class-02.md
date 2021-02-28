# Basics of HTML, CSS & JS
# html text
creating a web page requires you to add markups to the contents of the page to provide extra meaning and allow browsers to show users the appropriate structure for the page and some of these markups are :
1. Headings

HTML has six "levels" of headings:
< h1> is used for main headings < h2> is used for subheadings if there are further sections under the subheadings then the < h3> element is used, and so on...

2. Paragraphs

< p> To create a paragraph, surround the words that make up the paragraph with an opening < p> tag and closing < /p> tag.

3. Bold & Italic

< b> By enclosing words in the tags < b> and </ b> we can make characters appear bold.

< i> By enclosing words in the tags < i> and </ i> we can make characters appear italic.

4. Superscript & Subscrip

< sup> The < sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.

< sub> The < sub> element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.

## and so many others... They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).

# CSS
## what is the CSS
its a tool that helps us to do modifications to the HTML page we did earlier by using some rules that is made up of selectors which the element of the rule, and declarations that indicates what will they look like.
 ## HTML with CSS
 CSS associates style rules with HTML elements, that will achive the final display of the elements and contents.

 the CSS rule contains two parts :

 *selector
 *declaration

 the selector indicates which element the rule applies to ( can be used on multiple elements)

 the declaration indicates how the elements referred to in the selector should be styled.

 for example :  p {
     font-family: arial}

     the p is the selector

     the {font-family:arial} is the declaration

## displayed elements
CSS properties affect how elements are displayed , and it works by sitting the declarations inside curly brackets that devides in two parts

*a property : indicates the aspects of the element.
*a value : specify the settings you want to apply to the properties.

as for the example we took earlier :

  {font-family:  will be the property.

  arial}   would be the value.

  # basic JavaScript instructions

  and you start by declaring variables, variables are like a container to a hold value and its s a good name for this concept because the data stored in a variable can change (or vary) each time a script runs or as required .
  first you need to declare it by creating it and give it a name, and then assign it a value by adding this value after the equal sign, and now you have it all in ! .

 and theres another kind that is called Arrays. Arrays are special types of variables that store more
than one piece of related information. 

as for the data that can be stored inside it there are four kinds,numbers (0-9), strings (text), and Boolean values (true or false). and the expressions rely on operators to calculate a value.

# decisions & loops
## decision making 
decisions are made to determine which line of code shoul run next, and you need a flowchart to plan for these occasions.

## evaluating conditions & conditional statements
there are two components to a decision:
1. an expression is evaluated, which returns with a value.
2. a conditional statement says to do in a given situation.
you first base the conditional statement on a concept and if the condition is met then it goes by evaluating the condition in order to make a decision and run it .

## comparison operators & evaluating conditions 
you can evaluate a situation by comparing one value to what you expect it to be, the result will be a boolean (true or false).
and you can compare by these operators :
== to see if the two values are the same.

!= to see if the two values are not the same.

= = = to see if the two values are the same in value and type.

!== to see if the two values are not the same in value and type.

and the less than and greater than operators (<)(>).

and you can also use expressions to compare, the operand does not have to be a single value or variable name, it can also be an expression !.