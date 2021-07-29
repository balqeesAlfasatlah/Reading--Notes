## Charts

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

![](https://canvasjs.com/wp-content/uploads/images/gallery/javascript-charts/line/javascript-line-charts-graphs.png)

+ **Setting up** :

The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script.

+ **Drawing a line chart** :

1. To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. 

2. Next, we need to write a script that will retrieve the context of the canvas.

3. Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

# Canvas 

The HTML **canvas** element is used to draw graphics on a web page.

![](https://images.slideplayer.com/24/7554172/slides/slide_3.jpg)
 
 **see the example below** :


![](https://www.researchgate.net/profile/Curran-Kelleher/publication/262398551/figure/fig5/AS:666687049306144@1535961987543/Example-code-for-HTML5-Canvas.png)

## Drawing shapes with canvas :


+ Drawing rectangles :

![](https://i.ytimg.com/vi/AD0u6LweP1g/maxresdefault.jpg)

+ Drawing a circle :

![](https://docplayer.net/docs-images/47/20157860/images/page_14.jpg)


## Applying styles and colors :

 Here we will explore the canvas options we have at our disposal to make our drawings a little more attractive.

 + Colors:

if we want to apply colors to a shape, there are two important properties we can use: **fillStyle and strokeStyle**.

![](https://slidetodoc.com/presentation_image_h/df6744852c099bc1b21eff46a51b49ac/image-36.jpg)

![](https://www.wikitechy.com/step-by-step-html-tutorials/html5-canvas/img/canvas-images/output-linecap-property-in-html5-canvas.png)

## Drawing text :

The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth]) :
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

2. strokeText(text, x, y [, maxWidth]) :
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQf2T_rNbHturoghmfkeg0BBzTmRED3dhZvHu2u_OoALW_OopKP4Nqs4Lc5Oo3MVmNYSAQ&usqp=CAU)

![](https://slideplayer.com/slide/11588201/62/images/65/Draw+Text+on+the+Canvas.jpg)