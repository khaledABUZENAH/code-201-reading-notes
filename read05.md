# read05

## images

There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.

Images should...


* Be relevant
* Convey information
* Convey the right mood
* Be instantly recognisable
* Fit the color palette

### storig images on your site

If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.

### adding images

![addingimages](https://www.homeandlearn.co.uk/WD/images/chapter3/template_html.gif)

To add an image into the page you need to use an (<img>) element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:

* src : This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site.


* alt : This provides a text description of the image which describes the image if you cannot see it.

### height and width of images

You will also often see an <img> element use two other attributes that specify its size:

* height :This specifies the height of the image in pixels.

* width : This specifies the width of the image in pixels

### three rules for creating images

1. Save images in the right format; like jbeg, gif, and png
2. Save images at the right size
3. Use the correct resolution 

### figure and figure caption in HTML5

* figure :  Images often come with captions. HTML5 has introduced a new <figure> element to contain images and their caption so that the two are associated

* figure caption : The <figcaption> element has been added to HTML5 in order to allow web page authors to add na caption to an image.

## Color

![colors](https://www.w3schools.com/colors/img_colormap.gif)

There are several ways to use the colors in CSS, like the color name, RGB, RGBA, HEX, HEXA, HSL, and HSLA.

* the first method is just to write the name of the color, such as red and white
* in rgb and argb method, you have to determine three elements **(red, blue, green)** each color will be represented as a number from 0 to 255. the letter a stands for alpha, which sympolozes the opacity of the color, and it is from 0 to 1
* in hex codes, These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a hash # For example: **#ee3e80**
* in hcl which stands for hue, saturation and lightness, each color has a degree for example the red and its degree is 360, green is 120, and the blue is 240, Saturation refers to the amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray.


## Text

### Typeface Terminology

1. serif : Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs. Exaples; Georgia, Times, Times New Roman
2. sans-serif : Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design. Exaples; Arial, Verdana, Helvetica
3. monsoace : Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts have different widths.)

### specifying typefaces

The font-family property allows you to specify the typeface that should be used for any text inside the elemen (s) to which a CSS rule applies. The value of this property is the name of the typeface you want to use.

### size of type

The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are; pixels, percentages, and ems.

### **Bold**

The font-weight property allows you to create bold text. There are two values that this property commonly takes;normal: This causes text to appear at a normal weight. bold: This causes text to appear bold.

### ***italic***
If you want to create italic text, you can use the font-style property. There are three values this property can take:normal:This causes text to appear in a normal style. italic: This causes text to appear italic. oblique: This causes text to appear oblique.

### UpperCase & LowerCase

The text-transform property is used to change the case of text giving it one of the following
values; uppercase: This causes the text to appear uppercase. lowercase: This causes the text to appear
lowercase.capitalize: This causes the first letter of each word to appear capitalized.

### underline and strike

The text-decoration property allows you to specify the following values:

1. none :This removes any decoration already applied to the text.
2. underline: This adds a line underneath the text.
3. overline: This adds a line over the top of the text.
4. line-through: This adds a line through words.
5. blink: This animates the text to make it flash on and off.

### alighnment

The text-align property allows you to control the alignment of text. The property can take one of four values:

1. left: This indicates that the text should be left-aligned.
2. right: This indicates that the text should be right-aligned.
3. center: This allows you to center text.
4. justify: This indicates that every line in a paragraph, except the last line, should be set to take up the full width of the containing box.

* text shadow property takes three lengths and a color
* The text-indent property allows you to indent the first line of text within an element.
* :first-letter, is used to change the size of the first letter in a paragraph.


### styling links 

Browsers tend to show links in blue with an underline by default, and they will change the color of links that have been visited to help users know which pages they have been to.


* :link :This allows you to set styles for links that have not yet been visited.
* :visited :This allows you to set styles for links that have been clicked on.

### responding to users

* :hover :This is applied when a user hovers over an element with a pointing device such as a mouse. This has commonly been used to change the appearance of links and buttons when a user places their cursor over them.

* :active :This is applied when an element is being activated by a user.

* :focus  : This is applied when an element has focus. Any element that you can interact with, such as a link you can click on or any form control can have focus.

## JBEG VS PNG VS GIF

* JBEG: best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth. JPEG images don’t support transparency and are hence not usable for such cases. support around 16 million colours. 
* PNG: it has the best quality and it's now supported on most devices. support transparency, png images mainly have two modes — PNG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image.
* GIF: it's only used for animations.  support transparency, GIF images are limited to 256 colours.









