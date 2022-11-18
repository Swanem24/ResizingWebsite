# ResizingWebsite

This is a repository created for learning how to make a responsive website. 

My goal is to create a website that resizes the website depending on the user. If the user drags the browser to make it smaller it should make everything in the website scale down accordingly.

What I learned:
- Em (em is a measuring unit for fonts)
- Rem (rem is root em. it checks for the root element in the tag instead of his parents tag)
- min-width/max-width (limits how wide an element becomes even after resizing)
- A background image of an HTML element will scale proportionally when its background-size property is set to cover
- <meta name="viewport" content="width=device-width, initial-scale=1">
- name="viewport" attribute: tells the browser to display the web page at the same width as its screen
- content attribute: defines the values for the <meta> tag, including width and initial-scale
- width=device-width key-value pair: controls the size of the viewport in which it sets the width of the viewport to equal the width of the device
- initial-scale=1 key-value pair: sets the initial zoom level

An example of creating a scaling image or video
.container {
  width: 50%; <-- half the size of the browser
  height: 200px;  
  overflow: hidden; <-- to hide any items coming outside of the container
}
 
.container img {
  max-width: 100%;
  height: auto;
  display: block;
}
