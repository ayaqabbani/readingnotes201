# Introduction
if you were wondering how the web works, When you visit a website, the web server hosting that site could be anywhere in the world, When you connect to the web, you do so via an Internet Service Provider and you type the domain name into your browser, Your computer contacts a network of servers called Domain Name System (DNS) servers that will work like your phone book it'll get you to what youve searched for so easy, fast and smooth.
The unique number that the DNS server returns to your computer allows your browser to contact the web server that hosts the website you requested, and finally The web server then sends the page you requested back to your web browser.

# structure
HTML Uses Elements to Describe the Structure of Pages, Tags act like containers. They tell you something about the information that lies between their opening and closing tags. and the page contains these essintial elements:
1. The opening < html> tag indicates that anything between it and a closing </ html> tag is HTML code.
2. The < body> tag indicates that anything between it and the closing< /body> tag should be shown inside the main browser window.
3. Words between < h1>< /h1> are a main heading.
4. A paragraph of text appears between these < p> and < /p> tags.
5. The closing < /body> tag indicates the end of what should appear in the main browser window.
6. The closing < /html> tag indicates that it is the end of the HTML code.

and if we wanted to take a closer look at the tags.
the opening tag starts with a left-angle bracket then contains the character and ends with a RIGHT-angle bracket.
while the closing tag have the same sympols except that before the charachter it has a forward slash.

as for the Attributes they tell Us more About Elements and provide additional information about the contents of an element, they are made up of two parts: a name and a value separated by an equals sign.

# HTML page
the HTML page should contain some basic elements in order to get it filled with the codes, which is :
* doctype : that tells your browser that you're using HTML version 5.
* HTML : that opens up your page.
* head : that appears on the title at the beginning of the page.
* body : the holds the content of your page.

## escape characters on HTML 
you can some characters in HTML to help you do your job easier...
such as "escape" characters or codes if you want your characters to appear on your page, for example you can get an angled bracket by using (& lt;) without spaces to get : &lt;.

and for the special symbols such as the copyright, trademark etc...

you cane use some characters or codes, like if you want the copyright symbol you can type (& copy;) without spaces to get : &copy;


## comments in HTML 
HTML allows you to add comments to your code and it won't be visible for users.

if you want to know how ?

you can add the comments between < !-- and -- > markers.
and you have yourself a hidden comment.

## attributes
attributes can be either an id attribute or a class attribute, both of them allow you to identify particular elements, the id attribute is unique and applies the edits to a single element, while the class attribute can apply an edit to a several elements.

## iframes 
iframes are little windows pops up in your page and you can see another page in it, so basically it cuts windows into your web pages through which other pages can be displayed.






### there are several elemnts can help you in your HTML page like the div and span elements that helps you to group and inline elements together.

### the meta tag gives you the ability to supply all kinds of information about your webpage.




# HTML5 layout 
HTML5 introduces a new set of elements to define the structure of your page.

## new elements 
and by a new set of elements we are talking about some elements that allow you to divide up the parts of your page, for example the header sits inside a new header element.
the advantage you get from these new elements is to help the developer to describe the structure of the page easily, plus the new elements provide a more clearer code.
but unfortunately some of the old browsers dont understand the HTML5 elements, and for that they need to be told which elements are block-level.
in order to make these elements work in internet explorer 8 and older versions, you need to have an extra javascript and your good to go!.


# process & design
before creating a website you need to know who's your target audiene, you target them indivisually like the age, gender or country. or you can target companies  like a relative department or job position.
beside that you need to know why they will want to visit your website according to the information you'll provide.
so first you need to target your audience.
why they visit your website.
what information you'll provide to them.
and then you're all set to start the work.
## site maps
a site map is a diagram of the pages that will be used to structure the site, the website should have a map to help you organize the information into sections or pages.
like a house with rooms every door will get you to different room, and this is how the site map works each page leads into another. for example when you're at the home page you'll have the ability to access one of the other pages that is placed on the home page like "about", "articles", "shop" etc...
depending on your page elemnts and so on.

## wireframes
a wireframe is considered to be the scratch of a website's interface, its the sketch that's used in early stage's of the web design, its created in only black and white to help you get a basic picture of what the website will contain at the end. for example :
![wireframe](https://th.bing.com/th/id/R39cfed23cc81bffc3180e161c8d81da5?rik=AjRhHk1pddjbsg&riu=http%3a%2f%2fmmls.mmu.edu.my%2fwordpress%2f1151103126%2fwp-content%2fuploads%2fsites%2f30365%2f2017%2f09%2fSimple-Wireframe-2.jpg&ehk=Qd8ZxXCzNHJb%2fPPMvCYdP6OZVsfkKqebJAyvviq%2bXzQ%3d&risl=&pid=ImgRaw)
don't worry it's just the beginning of it, it just need a little arranging, styling and coloring and it will come alive!.

# JavaScript
## introduction
javascript allows you to make web pages more interactive by modifying the content and markup while being viewed in the browser by:
1. accessing the content You can use JavaScript to select any element, attribute, or text from an HTML page.
2. modifying the content by adding elements, attributes, and text to the page, or remove them.
3. programming the rules so You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page.
4. react to events so the script should run when a specific event has occured.

# the A B C of programming
# A
what is a script and how can i create one ?

A script is a series of instructions that a computer can follow to achieve a goal You could compare scripts to any of the following ( a recipe, a handbook or manuals).
and for creating it, you need to first state your goal and then list the tasks that need to be completed in order to achieve it. and once you know it you can work out the indiviual tasks by representing it in a flowchart.
# B
how do computers fit in with the world around them ?

first lets understand how a browser sees a web page:
1. it recives the page as an HTML code.
2. it creats a model of the page and store it in the memory.
3. it uses a rendering engine to show the page on the screen.

# C 
how do i write a script for a web page ?

and its simply by using the objects & methods, such as using what prorammers refer to as the calling method by using the (document.) object, it represents the entire web page and all the web browsers implement this object, followed by the method of the document such as (write) and writhing the parameters right after it.
When the browser comes across a < script> element, it stops to
load the script and then checks to see if it needs to do anything. 
and that's how the job is done !.