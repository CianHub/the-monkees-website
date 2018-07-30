# The Monkees Website

This website offers both existing and potential fans of The Monkees a way to see and hear songs from the bands back catalog and find out about any new material as it becomes available. The site provides information and links to buy tickets for the bands upcoming concerts as well as a method of booking the band for private events. Fans can learn about the individual members of The Monkees through the band section and provides links to the bands social media and a newsletter sign-up option.

## Features

1. Users can watch music videos.
2. Users can listen to existing songs.
3, Users can find information about upcoming releases.
4. Users can find information and links to purchase tickets for upcoming concerts.
5. Users can book the band for private events.
6. Users can find information about each member of The Monkees.
7. Users can find links to the bands social media and sign up for a newsletter.
8. Users can view a gallery containing images related to The Monkees (e.g. album covers).

## Technology Used

This application was developed using HTML5, CSS3, Bootstrap 3 and minimal JavaScript.

## Design

The Bootstrap framework serves as the base for the sites design. The website uses a single page layout consisting of seven main sections: the navbar/jumbotron section, band section, gigs section, booking form/modal section, music section, video section, and the social footer section. This layout uses the Bootstrap grid system and each section was built using a wrapper - container - row - column structure. The background of the navbar/jumbotron section makes use of flexbox to display its background image.

The website is structured semantically with a mobile-first philosophy. Keeping with this approach, the core elements (minimal viable product) of the site are present on all screens while there is more detail present in various areas like the navbar and gigs table on larger screens.

As The Monkees have been around and long established their brand, the sites colors and typography draw on the existing aesthetic and color scheme in order to instantly identify the site with the band.


## Development Process 

During the development of the site different elements were experimented with e.g. in an early version of the site a jQuery based music player was trialled but due to my lack of experience with JQuery at the time of development, customising the player was very challenging and I opted to work with the HTML5 audio elements instead. 

Similiarly as the images I had been provided with were in a variety of different sizes and displayed quite poorly. This led to some tinkering with different methods of displaying the images until finally settling on a customised version of the Bootstrap slideshow component which allows for a consistent presentation.

## Installation

1. Clone the repository.
2. Open index.html in your web browser of choice.

## Testing

As it primarily consists of HTML an CSS, the site has been manually tested on a section by section basis and is fully responsive across all screen sizes and browsers (the calendar selector tool in the modal section is only available in Chrome and Edge as of the time of development). 


## Deployment

The website has been deployed to Github pages and can be found at: <https://cianhub.github.io/the-monkees-website/>
