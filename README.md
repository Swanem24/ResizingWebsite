# ResizingWebsite

This is a repository created for learning how to make a responsive website. 

My goal is to create a website that resizes the website depending on the user. If the user drags the browser to make it smaller it should make everything in the website scale down accordingly.

What I learned:
- Em (em is a measuring unit for fonts)
- Rem (rem is root em. it checks for the root element in the tag instead of his parents tag)
- min-width/max-width (limits how wide an element becomes even after resizing)

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
