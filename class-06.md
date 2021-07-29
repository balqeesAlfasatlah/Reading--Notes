# Problem Domain

## What is the hardest thing about writing code?
here some answers :

1. Learning a new technology.
2. Naming things.
3. Testing your code.
4. Debugging.
5. Fixing bugs.
6. Making software maintainable.


making the  problem domain so trivial make it  easily understood,like  I am able to make both teaching and learning easier.

## Why problem domains are hard ?

 because you can’t really see what you are trying to build very clearly. 

## What can you do about it?

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1. Make the problem domain easier
2. Get better at understanding the problem domain.

  Programming is easy if you understand the problem domain.
  You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.

What I mean by this is that it is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain.

# Javascript


## Whats The Object ?

Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. 

* In an object: variables become known as properties. 
* In an object: functions become known as methods. 

![obj](https://static.skillshare.com/uploads/video/thumbnails/5582559529001/448-252)

**See the example below**

![obj](https://www.rdcircles.com/wp-content/uploads/2020/04/RDLearning-Object-properties.jpg)

### Aceess to an object :

![obj](https://dmitripavlutin.com/static/50a87420915de18f26da616865fe9825/05127/access-object-properties-2.png)


## Document Object Model

The Document Object Model (DOM) specifies 
how browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents of a web page while it is in the browser window. 

The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. 
It is implemented by all major browser makers, and covers two primary areas: 

1. Making a model og the html page.
2. Accessing and changong the html page. 


* As a browser loads a web page, it creates a model of that page. The model is called a **DOM tree**, and it is stored in the browsers' memory. 

* It consists of four main types of nodes :

1. The document node.
2. Elements node.
3. Attribute node.
5. Text node.

![tree](https://www.kirupa.com/html5/images/DOM_js_72.png)


### WORKING WITH THE DOM TREE:

Accessing and updating the DOM tree involves two steps: 
1. Locate the node that represents the element you want to work with. 
2. Use its text content, child elements, and attributes. 

* You can select element nodes by their id or cl ass 
attributes, by tag name, or using CSS selector syntax.

### Selcting elements using id attributes :

get El ementByi d () allows you to select a single element node by specifying the value of its id attribute.

![id](https://cf.ppt-online.org/files/slide/l/lG6hjyFR8carDYH7oVAtPW3exEOg0sSpQ1JKfm/slide-9.jpg)


**When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element).**

* When a DOM query returns a Nodelist, you may want to: 
1. Select one element from the NodeList. 
2.  Loop through each item in the Nodelist and 
perform the same statements on each of the element nodes.

### Selcting elements by tag name :

The get El ementsByTagName () 
method allows you to select 
elements using their tag name. 

![](https://miro.medium.com/max/2284/1*XQnlyUDJ1kSkwan1nyqVWw.png)

![](https://image.slidesharecdn.com/javascript-200121065050/95/java-script-8-638.jpg?cb=1579589609)

## Howm to get/update element content : 

* When you select a text node, you can retrieve or amend the content of it 
using the node Va 1 ue property.

* To work with text in an element, first the element node is 
accessed and then its text node. 

* The textContent property allows you to 
collect or update just the text that is in the 
containing element (and its children).


## Adding or removing html content :

there are two different ways to fdo that :

1. The innerHtml properity.

2. DOM manipulation.
