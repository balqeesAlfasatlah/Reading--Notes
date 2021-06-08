# HTML 

## Links:

Links are the defining feature of the web 
because they allow you to move from 
one web page to another — enabling the 
very idea of browsing or surfing.

Links are created using the a element. Users can click on anything between the opening a tag and the closing a tag. You specify 
which page you want to link to using the href attribute.

**Here how we can write it :**

![](https://cdo-curriculum.s3.amazonaws.com/media/uploads/a_tag.png)


**see the decription below that contain an example**

![links](https://slideplayer.com/slide/6356925/22/images/5/HTML+Links+and+Anchors+Example.jpg)

# CSS : Layout

### Building Blocks :

CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.

Block-level boxes start on a new line and act as the main building blocks 
of any layout, while inline boxes flow between surrounding text. You can 
control how much space each box takes up by setting the width of the 
boxes (and sometimes the height, too). To separate boxes, you can use 
borders, margins, padding, and background colors.

### Containing Elements :

If one block-level element sits inside another 
block-level element then the outer box is 
known as the **containing or parent element** .

It is common to group a number of elements together inside a div (or other block-level) element. For example, you might group together 
all of the elements that form the header of a site (such as the logo and 
the main navigation). The div element that contains this group of 
elements is then referred to as the containing element.

### Controlling the Position of Elements :

CSS has the following positioning schemes that allow you to control 
the layout of a page: **normal flow, relative positioning, and absolute positioning**. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.


1. Normal flow : Every block-level element 
appears on a new line, causing 
each item to appear lower down 
the page than the previous one. 
Even if you specify the width 
of the boxes and there is space 
for two elements to sit side-byside, they will not appear next to each other. This is the default 
behavior (unless you tell the 
browser to do something else).

2. Relative Positioning : This moves an element from the 
position it would be in normal 
flow, shifting it to the top, right, 
bottom, or left of where it 
would have been placed. This 
does not affect the position of 
surrounding elements; they stay 
in the position they would be in 
in normal flow.

3. Absolute positioning :This positions the element 
in relation to its containing 
element. It is taken out of 
normal flow, meaning that it 
does not affect the position 
of any surrounding elements 
(as they simply ignore the 
space it would have taken up). 
Absolutely positioned elements 
move as users scroll up and 
down the page.

![dec](https://www.internetingishard.com/html-and-css/advanced-positioning/positioned-elements-terminology-861fca.png)


### Floating :

* The float property specifies how an element should float.

* Note: Absolutely positioned elements ignore the float property!

* Note: Elements after a floating element will flow around it. To avoid this, use the clear property or the clearfix hack (see example at the bottom of this page).

![css](https://image.slidesharecdn.com/css-floats-160224091253/95/css-floats-7-638.jpg?cb=1456305879)

## Screen Sizes :

Different visitors to your site will have different sized screens that show 
different amounts of information, so your design needs to be able to 
work on a range of different sized screens.

![dev](https://internetingishard.netlify.app/responsive-images-overview-890631.fd4f8299.png)

## Screen Resolution :

Resolution refers to the number of dots a screen shows per inch. Some 
devices have a higher resolution than desktop computers and most 
operating systems allow users to adjust the resolution of their screens.

## Page Sizes :

Because screen sizes and display resolutions vary so much, web 
designers often try to create pages of around 960-1000 pixels wide 
(since most users will be able to see designs this wide on their screens).

# Javascript

## Function :

Browsers require very detailed instructions about what 
we want them to do. Therefore, complex scripts can run 
to hundreds (even thousands) of lines. Programmers use 
functions, methods, and objects to organize their code. 

***WHAT IS A FUNCTION?***

Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements). 

### Function Syntax

* A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

* Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

* The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

* The code to be executed, by the function, is placed inside curly brackets: {}

**Declare a function :**

![fun](https://s3.ap-south-1.amazonaws.com/s3.studytonight.com/tutorials/uploads/pictures/1587882057-1.png)

**Calling Function :**

![call](https://cdn.programiz.com/cdn/farfuture/oAZVf3IqOKOYj_aJ-IoYQvbJ2CB-B3y4HXSLXBUmYcY/mtime:1591592163/sites/tutorial2program/files/javascript-function-with-parameter.png)


# 6 Reasons for Pair Programming :


**How does pair programming work?**

While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. 

**Why pair program?**

1. Greater efficiency.
2. Engaged collaboration.
3. Learning from fellow students.
4. Social skills.
5. Job interview readiness.
6. Work environment readiness .

