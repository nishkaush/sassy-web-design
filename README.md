# sassy-web-design
sassy web design site for photographers


Challenges Faced and Lessons learnt:

(1) Properties like column-count, column-width, column-gap are excellent tools for dividing up a given element into multiple columns irrespective of the content inside them.

(2) Css resets are important at the start of css especially removal of default padding,margins, text-decorations and list-styles so as to avoid conflicts later in the project. Also defining font color and font family is a good idea at the start.

(3) To center a text, image or any other non-element object inside a parent, text-align property can be used. Non-element object means anything apart from standard html elements like div, body, header, p, h1,etc.

(4) To put a colored shade over a background image, use a div that has the same dimensions as the image and make the div either float in a way so it positions itself over the image or alternatively, make its position:absolute and then offset it manually over the image.

(5) To only show a specific part of a background image aka focus on a specific part of the background image (in the situation where the image is massive and the provided space is less), use the background-position property and use the top, left, bottom, center values along with %values.
