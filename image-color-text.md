# IMAGE 
* How to add images to pages
* Choosing the right format
* Optimizing images for the web

**<img>** 

To add an image into the page
you need to use an <img>
element. This is an empty
element . It must carry the
following two attributes:

1. **src**
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
2. **alt**
This provides a text description
of the image which describes the
image if you cannot see it.
3. **title**
You can also use the title
attribute with the <img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.

![image](https://cdo-curriculum.s3.amazonaws.com/media/uploads/img_tag.png)



* **height** This specifies the height of the
image in pixels.
* **width**
This specifies the width of the
image in pixels.


#### Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

![IMAGE](https://www.dignited.com/wp-content/uploads/2020/02/jpeg-png-gif.jpg)

### *Where to Place Images in Your Code*
1. before a paragraph
The paragraph starts on a new
line after the image.
2. inside the start of a
paragraph
The first row of text aligns with
the bottom of the image.
3. in the middle of a
paragraph
The image is placed between the
words of the paragraph that it
appears in.

***align ***

The align attribute was
commonly used to indicate how
the other parts of a page should
flow around an image. It has
been removed from HTML5
and new websites should use
CSS to control the alignment of
images

1. **left**
This aligns the image to the left
(allowing text to flow around its
right-hand side).

2. **right**
This aligns the image to the right
(allowing text to flow around its
left-hand side)

### Three Rules for Creating Images: 
1. Save images in
the right format
Websites mainly use images in
jpeg, gif, or png format. 

2. Save images at
the right size
You should save the image at
the same width and height it will
appear on the website. 
3. Use the correct
resolution
Computer screens are made up
of dots known as pixels. Images
used on the web are also made
up of tiny dots.


**Image Dimensions **

The images you use on your website should be
saved at the same width and height that you
want them to appear on the page.



**Image Resolution**

Images created for the web should be saved at
a resolution of 72 ppi. The higher the resolution
of the image, the larger the size of the file.

***<figure>***
Images often come with
captions. HTML5 has introduced
a new <figure> element to
contain images and their caption
so that the two are associated.
You can have more than one
image inside the <figure>
element as long as they all share
the same caption.

***<figcaption>***
The <figcaption> element has
been added to HTML5 in order
to allow web page authors to add
a caption to an image.

# colors

Color can really bring your pages to life.

**rgb values**

These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)

![rgb values](https://i.pinimg.com/originals/d8/81/b2/d881b2850db572a124dc5c17549c40d6.png)

 **hex codes**

These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80

![hex codes](https://i.pinimg.com/originals/43/03/f1/4303f16eb1ae762f4d8687d5821a9f8d.jpg)

**color names**

There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan


 **HSL & HSLA**

 * CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA. 


 ***hue***
This is expressed as an angle
(between 0 and 360 degrees).

***saturation***
This is expressed as a
percentage.

***lightness***
This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black.

----

# TEXT 
## Specifying Typefaces:
***font-family***

The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.
The value of this property is the
name of the typeface you want
to use. 

***font-size***
The font-size property enables
you to specify a size for the
font. There are several ways to
specify the size of a font. The
most common are:

1. pixels
Pixels are commonly used
because they allow web
designers very precise control
over how much space their text
takes up. The number of pixels is
followed by the letters px.
2. percentages
The default size of text in
browsers is 16px. So a size of
75% would be the equivalent of 


***Type Scales***

You may have noticed that programs such as
Word, Photoshop and InDesign offer the same
sizes of text.

***Units of Type Size***

![Units of Type Size](https://user.oc-static.com/upload/2018/04/30/15251064835155_fontsizes.png)

***@font-face*** allows you to use
a font, even if it is not installed
on the computer of the person
browsing, by allowing you to
specify a path to a copy of the
font, which will be downloaded if
it is not on the user's machine.

***font-family***
This specifies the name of the
font. This name can then be used
as a value of the font-family
property in the rest of the style
sheet (as shown in the rule for
the <h1> and <h2> elements).

***Bold font-weight***
* *normal*
This causes text to appear at a
normal weight.
* *bold*
This causes text to appear bold.



***Italic font-style***

If you want to create italic text,
you can use the font-style
property. There are three values
this property can take:

1. **normal**
This causes text to appear in a
normal style (as opposed to italic
or oblique).
2. **italic**
This causes text to appear italic.
3. **oblique**
This causes text to appear
oblique.





***text-transform***

The text-transform property
is used to change the case of
text giving it one of the following
values:
* uppercase
This causes the text to appear
uppercase.
* lowercase
This causes the text to appear
lowercase.
* capitalize
This causes the first letter of
each word to appear capitalized



***text-decoration***

The text-decoration property
allows you to specify the
following values:
* none
This removes any decoration
already applied to the text.
* underline
This adds a line underneath the
text.
* overline
This adds a line over the top of
the text.
* line-through
This adds a line through words.
blink
This animates the text to make it
flash on and off 



***text-align***

The text-align property allows
you to control the alignment of
text. The property can take one
of four values:

* *left*
This indicates that the text
should be left-aligned.
* *right*
This indicates that the text
should be right-aligned.
* *center*
This allows you to center text.
* *justify*
This indicates that every line in
a paragraph, except the last line,
should be set to take up the full
width of the containing box.

![text-align](https://www.tutorialrepublic.com/lib/images/text-align-illustration.png)


***:first-letter, :first-line***

You can specify different values
for the first letter or first line of
text inside an element using
:first-letter and
:first-line.
Technically these are not
properties. They are known as
pseudo-elements.


***:link, :visited***
:link
This allows you to set styles
for links that have not yet been
visited.
:visited
This allows you to set styles for
links that have been clicked on. 



resources [www.coursera.org](https://www.coursera.org/courses?query=html)

(HTML & CSS
Design and Build Websites) book for 
(jon Ducket)