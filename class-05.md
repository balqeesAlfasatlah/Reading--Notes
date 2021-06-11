# HTML
## Images 
### Choosing Images for Your Site :

If you are building a site from scratch, it is good 
practice to create a folder for all of the images 
the site uses.

![img](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/07/html-images-df.jpg)

**Adding Images**

To add an image into the page 
you need to use an img
element. This is an empty 
element (which means there is 
no closing tag). It must carry the 
following **two attributes**

**src** : This tells the browser where 
it can find the image file. This 
will usually be a relative URL 
pointing to an image on your 
own site. 

**alt**
This provides a text description 
of the image which describes the 
image if you cannot see it.

**See the example below**

![img](https://cdo-curriculum.s3.amazonaws.com/media/uploads/img_tag.png)

### Height & Width of Images :

Height and Width  are  two other attributes 
that specify the image size:

1. **height** This specifies the height of the 
image in pixels.

2. **width** This specifies the width of the 
image in pixels.

![img](https://www.wikihow.com/images/thumb/b/be/Set-Image-Width-and-Height-Using-HTML-Step-3-Version-3.jpg/v4-460px-Set-Image-Width-and-Height-Using-HTML-Step-3-Version-3.jpg.webp)


### Three Rules for Creating Images :

There are three rules to remember when you 
are creating images for your website which are 
summarized below. We go into greater detail 
on each topic over the next nine pages.

1. Save images in the right format : Websites mainly use images in jpeg, gif, or png format. If you 
choose the wrong image format then your image might not look as sharp as it should and can make the web page slower to load.

2. Save images at the right size :You should save the image at the same width and height it will appear on the website. If the image is smaller than the width or height that you have specified, the image can be distorted and stretched. If the image is larger than the width and height if you have specified, the image will take longer to 
display on the page.

3. Use the correct resolution : Computer screens are made up 
of dots known as pixels. Images used on the web are also made 
up of tiny dots. Resolution refers to the number of dots perinch, and most computer screens only show web pages at 72 pixels per inch. So saving images at a higher resolution results in images that are larger than necessary and take longer to download.

# CSS 

## Color :

The color property allows you 
to specify the color of text inside 
an element. 

**You can specify any color in CSS in one of three ways**

1. rgb values : These express colors in terms 
of how much red, green and blue are used to make it up. 
**example  rgb(100,100,90)**.

 2. hex codes :These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign.
 **example  #ee3e80**.

3. color names:
There are 147 predefined color 
names that are recognized 
by browsers. **example: 
DarkCyan**.


![color](https://cdn.educba.com/academy/wp-content/uploads/2020/03/CSS-Color-Codes.jpg)

### Opacity : opacity, rgba

CSS3 introduces the opacity
property which allows you to 
specify the opacity of an element 
and any of its child elements. 
The value is a number between 
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15% 
opacity).


![opacity](https://community.adobe.com/legacyfs/online/1775293_opecity.png)

**See the decription below**

![opacity](https://odwebdesign.net/uploads/e/fb/17/adding-transparencies-and-gradients-with-css_3.png)

## Text :

### Specifying Typefaces :

+ font-family : The font-family property 
allows you to specify the 
typeface that should be used for 
any text inside the element(s) to 
which a CSS rule applies.
The value of this property is the 
name of the typeface you want 
to use.

![font-family](https://www.w3schools.com/css/serif.gif)
![font-family](https://user-images.githubusercontent.com/1515413/47589898-e534be80-d96a-11e8-9a8f-8af19d7daad1.png)

### font-size :

The font-size property enables 
you to specify a size for the 
font. There are several ways to 
specify the size of a font. The 
most common are:

1. pixels: Pixels are commonly used 
because they allow web 
designers very precise control 
over how much space their text 
takes up. The number of pixels is 
followed by the letters px.

2. percentages : The default size of text in 
browsers is 16px. So a size of 
75% would be the equivalent of 
12px, and 200% would be 32px.
If you create a rule to make all 
text inside the <body> element 
to be 75% of the default size (to 
make it 12px), and then specify 
another rule that indicates the 
content of an element inside the 
<body> element should be 75% 
size, it will be 9px (75% of the 
12px font size).

3. ems : An em is equivalent to the width 
of a letter m.

![font-size](https://image.slidesharecdn.com/week12-font-size-141120053802-conversion-gate02/95/week-12-css-font-size-4-638.jpg?cb=1416461909)

### Bold : font-weight

The font-weight property 
allows you to create bold text. 
There are two values that this 
property commonly takes:

1. normal : This causes text to appear at a normal weight.

2. bold : This causes text to appear bold.

![font-weight](https://htmldog.com/figures/weightStyle.gif)

## Attribute Selectors

![](https://cf.ppt-online.org/files/slide/k/Kbp3XcismqFREgGuz9OBIWY1vDx6MwHVeZQjC5/slide-9.jpg)


# JPEG vs PNG vs GIF — which image format to use and when?


**TLDR** Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.

**Compression** Almost all forms of data that we see on the internet — text, image, video etc. — are compressed to reduce the size of data and ensure faster transmission. Choosing the correct format and compression is a major factor that determines image size.

**JPEG** 

Is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality. Beyond this, the compression artefacts become more prominent. Because JPEG compression works by averaging out colours of nearby pixels , JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth. However, if an image contains text or lines, where a sharp contrast between adjacent pixels is desired to highlight the proper shape, this lossy compression technique does not yield good results.


**PNG**

 Is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.

 **GIF**
 
  Is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, GIF images are now mainly used only if the image contains animations.