# Designing Web Pages with CSS
## Chapter 10; Introducing CSS
### Think INSIDE the box
The first thing that chapter 10 teaches is understanding what CSS is supposed to do for you.  CSS is a language that is designed to incorperate specific rules designated to specific elements of your HTLM code.  If there is an *Element* in your HTLM file, CSS can help the Author manipulate and style that element.  They teach you to consider every element having a potential to have its own manipulatable box, depending on the authors desired outcome, can result in styling changes to your HTLM framework.

### CSS Rules and Declarations
CSS works by associating rules with HTML Elements that govern how the specified element should be displayed.  There are two parts to these rules;
- A **Sector** indicates which element the rule applies to.  there can be more than one element associated with the rule.
- A **Declaration** tells us how the element/s in the sector should be styled. 

Declarations are broken down into two parts;
- A **Property** indicates the aspect of the element that you want to change, i.e. color/font/border.
- A **Value** specifies the settings you want to use for those chosen properties, like saying exactly what color you want or exactly how big the border should be for the element.

### Using External and Internal CSS
There are two ways to impliment your CSS code into your HTML page.  External requires a seperate '.CSS' page referenced in your HTML `<head>` tag.  an example of calling your CSS rules into your HTML would look like this
> `<link href="css/styles.css" type="text/css" rel="stylesheet" />`

While using your css internally would look more along the lines of this
> `<style type="text/css">`
    body {
        font-family: arial;
        background-color: rgb(185.179.175):}
    h1 {
        color: rgb(255.255.255);}

But ***BOTH*** of these methods would produce the exact same results so long as the linked external CSS had the exact same code as the internally used CSS code.

### CSS Selectors
There are many different ways to tell elements of your HTLM to associate CSS rules to elements.  Selectors are unique and versital ways to accomplish your own personal styling touch to your entire webpage without having to code the same rule for certain elements.  a few examples in case i didnt explain that well enough are in the table below.

Selector | Meaning
---------|----------
Universal Selector | * {} Targets all elements of the page
Type Selector | h1, h2, h3 {} Targets all the `<h1>`, `<h2>`, and `<h3>` elements

> There are many more selectors, i dont have all day.

## Chapter 11; Color
There are three main ways to specify color in your CSS code.
1. *RGB Values* saying how much red, green or blue that your chosen color is made up of.
1. *Hex Codes* are six digit codes that represent the amount of red, green of blue your color is made up of followed by a #
1. *Color Names* are predifined color names that are simply typed out, like "white"

> There is more to color than meets the eye!

### Understanding Color
>**HUE** is near to the colloquial idea of color.
>*Saturation* refers to the amount of grey in a color, maximum saturation would have no grey while at minimum the color would be mostly grey.
>***Brightness*** which refers to how much black is in a color. At maximum brightness, there would be no black while on the flip side the color would be very dark.

### CSS3: HSL Colors
The HSL refers to the Hue, Saturation and Lightness of a color.

[Back to Main Page](../README.md)