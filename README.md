# **Craft Cymru** 
In this project, I’ve built a static front-end site to present useful information about craft beers in Wales to users, with the option of subscribing to a monthly delivery. The website is built using all the technologies I have learned about on the course so far.

The presentation of this data advances the site owner's goals helping them market their service.

## **UX**
**External user’s goal:**
 
The site's users are customers and potential customers, who want to know more about the finest collection of Welsh craft beers and potentially register their interest in receiving a subscription of said beers
 
  
**User stories**
 
* As a user, I want to learn about the finest craft beers Wales has to offer and who brews them
* As a user, I want to find out more about the best beers Wales has to offer and register my interest in purchasing a section of handpicked beers

## **Features**
### **Existing Features**
* Carousel - allows users to scroll through marketing images of the individual breweries. This is feature is present on the all breweries pages as well as the gallery (see gallery.html; tiny-rebel.html; bluestone.html; crafty-devil.html)
* Breweries page – provides users with background information on the breweries included in the Craft Cymru service (gallery.html)
* Beer selection – provides users with information on the individual beers supplied by the breweries and included in the service offering (see tiny-rebel.html; bluestone.html; crafty-devil.html)
* Features section of landing page – provides users with more information on the service offering (see index.html)
* Contact form – allows potential customers the ability to register interest in receiving a monthly subscription of welsh craft beers, delivered to their door, by having them fill out the contact form (see contact.html)

### **Features Left to Implement**
* A section that that which gives the user information about craft beer festivals taking place in Wales in the coming year. Potentially including an interactive map showing where the festivals are located.

## **Technologies Used**
* [HTML5](https://html.com/)
    * The project uses the mark up language **HTML5** for structuring and presenting content of the website
* [CSS3](http://www.css3.info/)
    * The project uses **CSS3** to customise the style of the website by describing the presentation of the website’s HTML 
* [JQuery](https://jquery.com/)
    * The project uses **JQuery** to animate elements of CSS styling
* [Bootstrap v4.5](https://getbootstrap.com/)
    * The project uses the CSS framework **Bootstrap** for responsive, mobile-first front-end CSS styling
* [Font Awesome 6](https://fontawesome.com/)
    * The project uses **Font Awesome** as an icon toolkit

## **Testing**

During the testing process, a HTML and CSS validator were used to ensure clean and correct code. As well as this, the following user journey's were tested.

*	Contact form:
    1.	Go to the "Sign up" page
    1.	Tried to submit the empty form and verify that an error message about the required fields appeared
    1.	Tried to submit the form with an invalid email address and verified that the relevant error message appears
    1.	Tried to submit the form with all inputs valid and verify that a success message appears.

*	Welsh Craft brewers:
    1.	Go to ‘The Brewers’ page *(gallery.html)*
    1.	Successfully information about welsh craft brewers
    1.	Successfully clicked through to the individual brewery pages

*	Service features:
    1.	Go to landing page *(index.html)*
    1.	Successfully found features of Craft Cymru server offering

*	Reaching sign up form from brewery pages:
    1.	Go to individual brewery page *(e.g. tiny-rebel.html)*
    1.	Successfully find information about beer products available
    1.	Successfully clicked through to sign up form using button

*	Reaching sign up form from ‘The Brewers’ pages:
    1.	Go to ‘The Brewers’ page *(gallery.html)*
    1.	Successfully find information about breweries included in service
    1.	Successfully clicked through to sign up form using button

*	Reaching sign up form from landing page jumbotron:
    1.	Go to landing page *(index.html)*
    1.	Successfully clicked through to sign up form using button

Through testing I discovered the image used for Bluestones’s Red Heaven beer was stretched and out of proportion.

I also discovered an issue with the modal used as a success message when submitting the sign up form – the modal appears when form is submitted regardless of validation.

### **Responsiveness**
The Craft Cymru website is a responsive, user-centric website that works well on all different browsers have and adapts to the user’s screen size and device. 

This has been thoroughly test tested on Google Chrome, Mozilla Firefox and Internet explorer.

Thorough testing has also been performed opening the site on various screen sizes. Functionality does not break on screen sizes from small (mobile phones) to large (desktops). 

## **Deployment**

NEED Content

## **Credits**
### **Content**
* The text for Tiny Rebel’s beer selection, and their description on ‘the brewers’ page, was copied from the [Tiny Rebel](https://www.tinyrebel.co.uk/browse/c-BEERS-5) website
* Text for Bluestone Brewing’s beer selection, and their description on ‘the brewers’ page, was copied from the [Bluestone Brewing](https://www.bluestonebrewing.co.uk/) website
* Text for Crafty Devil’s beer selection, and their description on ‘the brewers’ page, was copied from [Untapped](https://untappd.com/)

### **Media**
* The photos used in this site were obtained [Unsplash](https://unsplash.com) and [Untapped](https://untappd.com/)

## **Acknowledgements**
* I received inspiration for this project from the Whiskey Drop website examples from Code Institute module core CSS bootstrapping your next big idea module. I used code from this example for the landing page jumbotron and features. The features section was replicated across multiple pages.
* I used Bootstrap’s carousel template
* I received inspiration for the opaque overlay over the carousel from Opaque overlay over carousel [medium.com](https://medium.com/@shehzada.salman072/how-to-make-a-black-overlay-over-bootstrap-4-carousel-132f3a36813a)
* This project also uses various Bootstrap components including, but not limited to a navbar, modal, jumbotron, and buttons.

