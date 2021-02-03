# Book; HTML/CSS
## Chapter 5: Images
> Storing images on your site should be in a folder labled images.  if you have a large site you would likely use a subfolder for images labled accordingly.

Adding Images to your page requires an `<img>` tag.  Image tags are an empty element which does not require a closing tag.  However, it does require two attributes within the tag itself.  `<src>`, tells the browser where to find the image file.  `<alt>`, provides a text description fo the image if you can not see the image.

> you can use the height and width attributes in your `<img>` tag to specify to the browser the pixle height and width of your image on the page.

You can place images before a `<p>`, inside the start of a `<p>` or in the middle of the paragraph as well.  if your image is inside of a block level element, any text or other inline elements will flow around the image.

The Align (left/right) attribute indicates how other parts of the page should flow around the image.  You can also use the align attribute set to top, middle or bottom.

#### Three Rules for Creating Images
1. Save the image in the right format
1. Save the image at the right size
1. Measure the image in pixels

> Using a professional editing tool for your images is highly advised.

## Chapter 11: Color
There are three main ways to specify color in your CSS code.
1. *RGB Values* saying how much red, green or blue that your chosen color is made up of.
1. *Hex Codes* are six digit codes that represent the amount of red, green of blue your color is made up of followed by a #
1. *Color Names* are predifined color names that are simply typed out, like "white"

> There is more to color than meets the eye!

#### Understanding Color
>**HUE** is near to the colloquial idea of color.
>*Saturation* refers to the amount of grey in a color, maximum saturation would have no grey while at minimum the color would be mostly grey.
>***Brightness*** which refers to how much black is in a color. At maximum brightness, there would be no black while on the flip side the color would be very dark.

#### CSS3: HSL Colors
The HSL refers to the Hue, Saturation and Lightness of a color.

## Chapter 12: Text
>`font-family` property allows you to specify what typeface should be used for any text inside the element(s) your CSS rule is applying them to.  if a user doesnt have the font you specified, you could simply coma in a few more font types to ensure that a user will be able to read your content.

>`font-size` property refers to the specific size you set your text to within the CSS element(s) that you are applying it to.  this can be specified in a few ways:
1. Pixels- most commonly used to determine size rendered on page
1. Percentages- the default size of text in browsers is set to 16px, so 75% of that would be 12px while 200% would be 32px.
1. EMS- and em is equivalent to the width of the letter M.

Other CSS properties and their values:

Property | Value
---------|---------
font-weight | normal, bold
font-style | normal, italic, oblique
text-transform | uppercase, lowercase, capitalize
text-decoration | none, underline, overline, line-through, blink
line-hieght | unit of measurment like px or em
letter-spacing | unit of measurment like px or em
text-align | left, right, center, justify

[Back to Main Page](../README.md)