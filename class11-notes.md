# Aligning images using CSS
## Float Property
* The float property can be used in CSS rather than using `<img>`'s *align* attribute.
* The float property can be added to the class that was created to represent the size of the image.
* New classes are created with names such as *align-left* or *align-right* to align the images to the left or right of the page.  These class names are used in addition to classes that indicate the size of the image.
```html
img.align-left {
    float: left;
    margin-right: 10px;}

img.align-right {
    float: right;
    margin-left: 10px;}

img.medium {
    width: 250px;
    height: 250px;}
```
## Centering Images
* By default images are inline elements. This means that they flow within the surrounding text.  In order to center an image, it should be turned into a block-level element using the display property with a value of block.
### Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:
* On the containing element, you can use the text-align property with a value of center.
* On the image itself, you can use the margin property and set the values of the left and right margins to auto.

```html
img.align-center {
    display: block;
    margin: 0px auto:}

img.medium {
    width: 250px;
    height: 250px;}
```
# BACKGROUND IMAGE
## background-image
* The background-image property allows you to place an image behind any HTML element.  This could be the entire page or just part of the page.  By default, a background image will repeat to fill the entire box.
* The path to the image follows the letters **url**, and it is put inside parentheses and quotes.
# background-repeat and background-attachment
## The background-repeat property can have four values:
### repeat
* The background image is repeated both horizontally and vertically.
### repeat-x
* The image is repeated horizontally only
### repeat-y
* The image is repeated vertically only.
### no-repeat
* The image is only shown once.
## The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values
### fixed
*  The background image stays in the same position on the page.
### scroll
* The background image moves up and down as the user scrolls up and down the page.
# Background Position
## background-position
* When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed.
* This property usually has a pair of values. The first represents the horizontal position and the second represents the vertical.

### left top
### left center
### left bottom
### center top
### center center
### center bottom
### right top
### right center
### right bottom
