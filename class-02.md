# HTML 

## Heading 

### Heading in HTML :

**HTML has six "levels" of 
headings :**

**h1** is used for main headings and 
**h2** is used for subheadings
If there are further sections 
under the subheadings then the 
**h3** element is used, and so 
on..


![heading](https://i2.wp.com/www.tutorialbrain.com/wp-content/uploads/2018/10/heading-tag.png?fit=1920%2C1080&ssl=1)


## Paragraph

To create a paragraph, surround 
the words that make up the 
paragraph with an opening
tag and closing tag.

![paragrahph](https://i1.wp.com/www.tutorialbrain.com/wp-content/uploads/2018/10/paragraph-tag.png?fit=1920%2C1080&ssl=1)

## Bold & Italic

we can make the text **bold** 
by enclosing words in the tags 
<b></b> we can make 
characters appear bold.
and for **italic** By enclosing words in the tags 
<i </i> we can make 
characters appear italic.


![bold and italic](https://i0.wp.com/www.tutorialbrain.com/wp-content/uploads/2018/10/Bold-and-Emphasize-tags.png?fit=1920%2C1080&ssl=1)

## Superscript & Subscrip

The **sup** element is used 
to contain characters that 
should be superscript such 
as the suffixes of dates or 
mathematical concepts like 
raising a number to a power such 
as 22.

The **sub** element is used to 
contain characters that should 
be subscript. It is commonly 
used with foot notes or chemical 
formulas such as H20

![sub and sup](https://qph.fs.quoracdn.net/main-qimg-28953ba223f5d951ef645b4de636ff25)

## Line Breaks & Horizontal Rules

**br** :
As you have already seen, the 
browser will automatically show 
each new paragraph or heading 
on a new line. But if you wanted 
to add a line break inside the 
middle of a paragraph you can 
use the line break tag.

**hr** :
To create a break between 
themes — such as a change of 
topic in a book or a new scene 
in a play — you can add a 
horizontal rule between sections 
using the hr tag.

![tags](https://clearlydecoded.com/assets/images/posts/2017-09-04-anatomy-of-html-tag/opening-tag-only.png)

## Strong & Emphasis 

The use of the **strong**
element indicates that its 
content has strong importance. 
For example, the words 
contained in this element might 
be said with strong emphasis.

The **em** element indicates 
emphasis that subtly changes 
the meaning of a sentence.

## Quotations

- There are two elements 
commonly used for marking up 
quotations:

1. **blockquote** : is 
used for longer quotes that take 
up an entire paragraph. Note 
how the p element is still 
used inside the blockquote
element. 

 2. **q** : is used for 
shorter quotes that sit within 
a paragraph. Browsers are 
supposed to put quotes around 
the element, however 
Internet Explorer does not — 
therefore many people avoid 
using the <q> element.

![quotation](https://codebridgeplus.com/wp-content/uploads/quotations.jpg)

## css 

**CSS** allows you to create rules that control the 
way that each individual box (and the contents 
of that box) is presented.

![css](https://miro.medium.com/max/600/1*OFsc0SD55jhi8cjo7aCA4w.jpeg)

### Example Styles :

1. **Boxes** : Width and height
Borders (color, width, and style)
Background color and images
Position in the browser .
2. **Text** : Typeface ,Size, Color,
Italics, bold, uppercase, 
lowercase, small-caps.
3. **Specific** :There are also specific ways 
in which you can style certain 
elements such as lists, tables, 
and forms.

![types](https://static.javatpoint.com/csspages/images/types-of-css.png)

- **Using External CSS** :

 **Link** element can be used 
in an HTML document to tell the 
browser where to find the CSS 
file used to style the page. It is an 
empty element (meaning it does 
not need a closing tag), and it 
lives inside the head element.

**It should use three attributes:**

1. **href** : This specifies the path to the 
CSS file (which is often placed in 
a folder called css or styles).
2. **type** : This attribute specifies the type 
of document being linked to. The 
value should be text/css.
3. **rel** : This specifies the relationship 
between the HTML page and 
the file it is linked to. The value 
should be stylesheet when 
linking to a CSS file.

![css](https://slidetodoc.com/presentation_image/906daa6721db853ea0e9ee9929be90e0/image-22.jpg)

- **Using Internal CSS** :
 ![internal](https://slidetodoc.com/presentation_image/59b26e54cae7cd200fccbcedbb22ec7f/image-4.jpg)

 ### Why use External Style Sheets?

 When building a website there are several advantages to placing your CSS rules in a separate style sheet.
 All of your web pages can share 
the same style sheet. This is 
achieved by using the <link>
element on each HTML page of 
your site to link to the same CSS 
document. This means that the 
same code does not need to be 
repeated in every page (which 
results in less code and smaller 
HTML pages).

# JavaScript

![](https://miro.medium.com/max/1024/1*YQgaKfVzK-YpxyT3NYqJAg.png)

## STATEMENTS :
A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon.

![example](https://www.bookofnetwork.com/images/javascript-images/JS_Expression-in-Statement_17Oct16_1503.png)

### COMMENTS :
You should write comments to explain what your code does. 
They help make your code easier to read and understand. 
This can help you and others who read your code. 

![comment](https://images.slideplayer.com/16/4970965/slides/slide_7.jpg)

## WHAT IS A VARIABLE?

A script will have to temporarily 
store the bits of information it 
needs to do its job. It can store this 
data in variables. 
When you write JavaScript, you have to tell the 
interpreter every individual step that you want it to 
perform. This sometimes involves more detail than 
you might expect. 

![var](https://www.tutsmake.com/wp-content/uploads/2020/05/JavaScript-Variable-Example.jpeg)

### Rules For Naming Varibles :

1. The name must begin with 
a letter, dollar sign ($),or an 
underscore (_). It must not start 
with a number.

2. The name can contain letters, 
numbers, dollar sign ($), or an 
underscore (_). Note that you 
must not use a dash(-) or a 
period (.) in a variable name. 

3. You cannot use keywords or 
reserved words. Keywords 
are special words that tell the 
interpreter to do something. For 
example, var is a keyword used 
to declare a variable. Reserved 
words are ones that may be used 
in a future version of JavaScript. 
ONLINE EXTRA 
View a full list of keywords and 
reserved words in JavaScript.

4. All variables are case sensitive, 
so score and Score would be 
different variable names, but 
it is bad practice to create two 
variables that have the same 
name using different cases. 

5. Use a name that describes the 
kind of information that the 
variable stores. For example, 
fi rstName might be used to 
store a person's first name, 
l astNarne for their last name, 
and age for their age. 

6. If your variable name is made 
up of more than one word, use a 
capital letter for the first letter of 
every word after the first word. 
For example, f i rstName rather 
than fi rstnarne (this is referred 
to as camel case). You can also 
use an underscore between each 
word (you cannot use a dash).

## ARRAYS :
An array is a special type of variable. It doesn't 
just store one value; it stores a list of values.

![array](https://csharpcorner.azureedge.net/article/array-destructuring-in-javascript/Images/Array%20Destructuring%20In%20JavaScript.png)

## EXPRESSIONS :
An expression evaluates into (results in) a single value. Broadly speaking 
there are two types of expressions.

## OPERATORS:
Expressions rely on things called operators; they allow programmers to 
create a single value from one or more values. 

![operators](https://dotnettutorials.net/wp-content/uploads/2020/02/JavaScript-Operators.png)

##  If Statements :
 the IF statement evaluates or checks a condition. if the condition evaluate to true , any statements in the subseguent code block are executed.

 ![if](https://cdn.programiz.com/sites/tutorial2program/files/js-if-else-statement.png)

 ## Switch Statements :
 Its a statement starts with a variable called the switch value.
 each case indicates a possible value for this variable and the code that should run if the variable matches that value.

 ![switch](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/03/JavaScript-Switch-case-execution-flow.jpg)

 ![switch](https://www.devopsschool.com/blog/wp-content/uploads/2020/06/php-switch-statement.png)


