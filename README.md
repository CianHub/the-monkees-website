# The Monkees Website

This website offers concert bookers, existing fans and potential fans of The Monkees a way to see and hear songs from the bands back catalog and find out about any new material as it becomes available. 

The site provides information and links to buy tickets for the bands upcoming concerts as well as a method of booking the band for private events. Fans can learn about the individual members of The Monkees through the band section and provides links to the bands social media and a newsletter sign-up option.
 
## UX

### User Stories

Before beginning development on the site, several user stories were created to determine who a visitor to the site could be and what they might want from the site:

- "As an existing fan of The Monkees, I want to be able to quickly access the bands    existing output, discover any new material and upcoming concert dates so that I can enjoy my favourite Monkees songs."

- "As an existing fan of The Monkees, I want to direct people, whom I want to introduce to the band, to a website where they can read about the band members, listen to The Monkees music, watch their music videos, see art and photos of the band and find out about any upcoming concert dates so that they can become fans."

- "As a potential fan of The Monkees, I want to be able to go to a website where I can read about the band members, listen to The Monkees music, watch their music videos, see art and photos of the band and find out about any upcoming concert dates so that I can become a fan."

- "As a potential concert booker, I want to be able to go to a website where I can read about the band members, listen to The Monkees music, watch their music videos, see art and photos of the band, find out about any upcoming concert dates so that I can decide if I want to send a booking form to the band through the website."

### Design

The Bootstrap framework serves as the base for the sites design. The website uses a single page layout consisting of seven main sections: the navbar/jumbotron section, band section, gigs section, booking form/modal section, music section, video section, and the social footer section. This layout uses the Bootstrap grid system and each section was built using a wrapper - container - row - column structure. The background of the navbar/jumbotron section makes use of flexbox to display its background image.

The website is structured semantically with a mobile-first philosophy. Keeping with this approach, the core elements (minimal viable product) of the site are present on all screens while there is more detail present in various areas like the navbar and gigs table on larger screens.

As The Monkees have been around for some time and long established their brand, the sites colors and typography draw on the existing aesthetic and color scheme in order to instantly identify the site with the band.

A site map drawn up prior to start of the websites development can be found in this repository titled: The Monkees Website_ Preliminary Site Map.pdf

## Features

1. Users can watch music videos.
2. Users can listen to existing songs.
3. Users can find information about upcoming releases.
4. Users can find information and links to purchase tickets for upcoming concerts.
5. Users can book the band for private events.
6. Users can find information about each member of The Monkees.
7. Users can find links to the bands social media and sign up for a newsletter.
8. Users can view a gallery containing images related to The Monkees (e.g. album covers).

## Technologies Used

- [HTML](https://www.w3.org/)
    - The project uses **HTML** to create the page.

- [CSS](https://www.w3.org/)
    - The project uses **CSS** to style the page.

- [JavaScript](https://developer.mozilla.org/bm/docs/Web/JavaScript)
    - The project uses **JavaScript** to manipulate the DOM.

- [Bootstrap](https://getbootstrap.com/docs/3.3/)
    - The project uses **Bootstrap** to style the page and user experience.

- [JQuery](https://jquery.com/)
    - The project uses **JQuery** to enable Bootstraps full functionality (e.g. collapsible navbar etc)

## Testing

As it primarily consists of HTML and CSS, the site has been manually tested on a section by section basis and is fully responsive across all screen sizes and browsers (the calendar selector tool in the modal section is only available in Chrome and Edge as of the time of development). 

1. Booking form:
    1. Go to the "Gigs" section
    2. Submit the form and verify that the modal appears.

1. Gallery
    1. Go to the "Gallery" section
    2. Verify that the arrow buttons control the slides.

During the development of the site different elements were experimented with e.g. in an early version of the site a jQuery based music player was trialled but due to my lack of experience with JQuery at the time of development, customising the player was very challenging and I opted to work with the HTML5 audio elements instead. 

Similiarly as the images I had been provided with were in a variety of different sizes and displayed quite poorly. This led to some tinkering with different methods of displaying the images until finally settling on a customised version of the Bootstrap slideshow component which allows for a consistent presentation.

## Deployment

The website has been deployed to Github pages and can be found at: <https://cianhub.github.io/the-monkees-website/>

## Installation

1. Clone the repository.
2. Open index.html in your web browser of choice.

## Credits

### Content

- The text for 'Band' section was copied from the [Wikipedia article - The Monkees](https://en.wikipedia.org/wiki/The_Monkees)

### Media

- The media files used in this website were provided by the Code Institute

### Acknowledgements

- I received inspiration for image overlay and block divider from the [Whiskey Drop - Course Project](https://github.com/Code-Institute-Solutions/BootstrapLandingPage)
