## Welcome to About_me_page

This page is about me(Brian) and my cat, it contains of 5 parts.

1. Navigation Bar

2. Brief Introduction

3. Detailed about me

4. Photo Album

5. Footage
  
  
### Pre-settings

This part will walk you through things that is used for the entire website.

```<meta charset="utf-8">```
+to specify the character encoding to ensure browsers can show Chinese words in the site.

```<body data-spy="scroll">```
+to notify user which part are they reading base on scroll position on this one-page website.

```<div id='intro'class="container-fluid bg-n text-center">```
+```container-fluid ```: provides a full width container, spanning the entire width, makes the site looks better.
+```bg-n``` : putting a class for css to further styling.
+```text-center``` : center texts

### Navigation Bar

A navigation bar is added by using bootstrap functions.

```<nav class='navbar navbar-default navbar-fixed-top'>```
+ ```navbar-fixed-top``` :
  to make sure users gain access to the navbar and the function of scrollspy can be seen.
+ ```navbar-default``` : 
  default coloring and styling of the navbar

```<button type='button' class='navbar-toggle' data-target='.navbar-collapse'>```
+ ```class='navbar-toggle'```: 
  a bootstrap function that turn navbar into a button when the size of browser is too narrow 
+``` data-target='.navbar-collapse'```
  target the button to the list with the class='navbar-collapse'

### Brief Introduction

This part includes a picture of my cat and a sentences describe what am I.

```<img src="img link" class="img-circle img-responsive img-center" width="350" height="350">```
+```img-circle``` : shape the img into circle
+```img-responsive``` : resize the img according to the size of the window.
+```img-center``` : center the img

### Detailed about me

This part includes more about me.

### Photo Album

This part is a photo album using bootstraps carousel function.

####The outermost ```<div>```:

Carousels require the use of an id (in this case ```id="myAlbum"```) for carousel controls to function properly.

```class="carousel" ```specifies that this ```<div>``` contains a carousel.

``` .slide ``` adds a CSS transition and animation effect, which makes the items slide when showing a new item

```data-ride="carousel"``` attribute tells Bootstrap to begin animating the carousel immediately when the page loads.


####The "Indicators" part:

The indicators are the little dots at the bottom of each slide (which indicates how many slides there is in the carousel, and which slide the user are currently viewing).

The indicators are specified in an ordered list with class ```.carousel-indicators```

The ```data-target ```attribute points to the id of the carousel.

The ```data-slide-to``` attribute specifies which slide to go to, when clicking on the specific dot.

####The "Wrapper for slides" part:

The slides are specified in a ```<div>``` with class ```.carousel-inner```.

The content of each slide is defined in a ```<div>``` with class ```.item```. This can be text or images.

The ```.active``` class needs to be added to one of the slides. Otherwise, the carousel will not be visible.

####The "Left and right controls" part:

This code adds "left" and "right" buttons that allows the user to go back and forth between the slides manually.

The ```data-slide``` attribute accepts the keywords "prev" or "next", which alters the slide position relative to its current position.

###Footer

This part leaves my contact to visitors of my personal website.

A class of ```list-unstyled``` is added to the ```<ul>``` to remove the bullets.

### Support or Contact

Having trouble with my page? Please kindly notify my by email(brian9328hk@gmail.com
