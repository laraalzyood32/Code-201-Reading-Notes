
# Images :
There are several things to consider when selecting and preparing images for your site Include an image in your web pages using HTML
## 1. Pick which image format to use
## 2. Show an image at the right size
## 3. Optimize an image for use on the web to make pages load faster You can

# Storing Images on Your Site:
As a website grows, keeping images in a separate folder helps you understand how the site is organized. Here you can
see an example of the files for a website; all of the images are stored in a folder called images
# Adding Images :
you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the
following two attributes:
1. src
This tells the browser where it can find the image file. This will usually be a relative URL pointing to 
an image on your own site. 
2. alt 
This provides a text description of the image which describes the image if you cannot see it.
3. title
You can also use the title attribute with the <img> element to provide additional information about the image.
# Height & Width of Images :
1. height : This specifies the height of the image in pixels.
2. width :  This specifies the width of the image in pixels>

# Where an image is placed
in the code will affect how it is displayed. Here are three examples of image placement that produce different results:
1: before a paragraph The paragraph starts on a new line after the image.
2: inside the start of a paragraph The first row of text aligns with the bottom of the image.
3: in the middle of a paragraph The image is placed between the words of the paragraph that it appears in.
4. Block elements always appear on a new line. Examples of block elements include the <h1> and <p> elements.
Inline elements sit within a block level element and do not start on a new line. Examples of inline elements include 
the <b>, <em>, and <img> elements .
# Aligning Images Horizontally :
align horizontally.html HTML
The align attribute was commonly used to indicate how the other parts of a page should flow around an image. It has
been removed from HTML5 and new websites should use CSS to control the alignment of images .
## 1. left :
This aligns the image to the left (allowing text to flow around its right-hand side).
## right : 
This aligns the image to the right (allowing text to flow around its left-hand side).
# Aligning Images Vertically
## 1. top : This aligns the first line of the surrounding text with the top of the image. 
## 2. middle : This aligns the first line of the surrounding text with the middle of the image.
## 3. bottom This aligns the first line of the surrounding text with the bottom of the image.
# Three Rules for Creating Images :
1. Save images in the right format
2. Save images at the right size .
3. Use the correct resolution .
# Transparency
1. Transparent GIF If the transparent part of the image has straight edges and it is 100% transparent 
 you can save the image as a GIF
2. PNG : If the transparent part of the image has diagonal or rounded edges or if you want a semiopaque transparency
 or a dropshadow, then you will need to save it as a PNG.
 # You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the
# content of an image. You should save images at the size you will be using them on the web page and
 #in the appropriate format.
#  Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.
# color :
## Foreground Color
The color property allows you to specify the color of text inside an element. You can specify anycolor in CSS 
in one of three ways:
## 1. rgb values
For example: rgb(100,100,90)
## 2. hex codes 
These are six-digit codes that represent the amount of red, green and blue in a color,
 preceded by a pound or hash # sign  For example: #ee3e80
## 3. color names There are 147 predefined color names that are recognized by browsers. For example: DarkCyan
# Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, 
# you can use a color picker.
#1.  Color not only brings your site to life, but also helps convey the mood and evokes reactions.
# 2.  There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
# 3. Color pickers can help you find the color you want.
# 4.  It is important to ensure that there is enough contrast between any text and the background color (otherwise
people will not be able to read your content).
# 5. CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
# 6. CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSla

# text :
 ## Choosing a Typeface for your Website When choosing a typeface, it is important to understand that
 ##  a browser will usually only display it if it's installed on that user's computer.
 # Specifying Typefaces font-family :
 The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to
 which a CSS rule applies .
 #1.  Size of Type font-size : The font-size property enables
allow you to specify a size for the font. There are several ways to specify the size of a font.
 The most common are:
## 1.pixels : Pixels are commonly used
## 2. percentages The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px .
## 3. ems An em is equivalent to the width of a letter m.
# Bold : The font-weight property allows you to create bold text. There are two values that this
property commonly takes:
## 1.normal : This causes text to appear at a normal weight.
## 2.bold   : This causes text to appear bold. 
## 3.italic : This causes text to appear italic.
## 4.UpperCase & LowerCase text-transform
### 1. uppercase  This causes the text to appear uppercase.
### 2. lowercase  This causes the text to appear lowercase.

## 5. Underline & Strike text-decoration
1. underline : This adds a line underneath the text.
2. overline  :This adds a line over the top of the text.
3. line-through : This adds a line through words.
4. blink  :This animates the text to make it flash on and off
## 6. Leading (pronounced ledding) is
a term typographers use for the vertical space between lines of text. In a typeface, the part of a letter that drops 
beneath the baseline is called a descender, while the highest point of a letteris called the ascender. Leading
is measured from the bottom of the descender on one line to the top of the ascender on the next.
## 7. Alignment text-align
### 1. left This indicates that the text should be left-aligned.
### 2. right This indicates that the text should be right-aligned.
### 3. center This allows you to center text.
### 4. justify This indicates that every line in a paragraph, except the last line, should be set to take up the full
### width of the containing box
## There are properties to control the choice of font, size, weight, style, and spacing.
 There is a limited choice of fonts that you can assume most people will have installed.
 If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
 You can control the space between lines of text, individual letters, and words. Text can also be alignedto the left, 
 right, center, or justified. It can also beindented.
# transparency
In a simple form, transparency indicates something that is completely invisible. Logos and icons often need to be
 placed on backgrounds with variable colours. 
# 1. JPEG images
 don’t support transparency and are hence not usable for such cases.
# 2.  PNG images 
support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single
 colour as transparent (index transparency). Partial transparency makes the edges blend smoothly 
#  3.GIF images 
support transparency by declaring a single colour in the colour palette as transparent (index transparency).
 
now test your knowledge by asimple quiz
1 . how we can adding images in steps ?
2.  what the meaning of src ?
3.  what are several ways to specify the size of a font ?
4.  do JPEG images support transparancy ?
5.  how you can adds a line through words ?



