# Cafe_Cervantes_Bootstrap
This is my first project I created from start to finish.
It is written with HTML, CSS/Bootstrap, and JS.
A small amount of Node is included but this is primarily a front end project.
I used this as an example for my future projects to show how my knowledge
    of coding has grown.

/////////////////////////////////////////////////////////////////////////////

This is something I have started seeing when attending concerts.
Either the restaurant side is not well maintained or the ability to find
    upcoming shows is a nightmare to find and purchase.
When the project starts you begin on the "Home" page.
You are then greeted with a carousel that links to different pages.
All pictures are edited to stay the same size to maintain a fluid carousel.
The entire project is responsive using bootstrap as the main framework.

Within the navbar you will see a "Schedule Event" button.
Clicking toggles a modal with light validation methods.
An example is the Email needing a @ to sumbit.
There is no backend so sumbit does nothing but it does toggle the modal off.

By clicking "Our Story" either at the top navbar, "Humble Beginnings"
    carousel-item, or bottom footer takes you to the "Our Story" page.
The first page was more of a single page style layout being able to see
    everything without scrolling.
This page is a zig zag example showing different ways to layout a page.
If the resolution is changed the page will responsively modify accordingly.
Notice now that after navigating away from the home page there is now a
    breadcrumb trail just below the navbar.
Clicking "Home" within the breadcrumb trail brings you back home.

Next, the "Menu" page uses a auto collapsing accordion style menu.
Researching different businesses around me I went with what was common
    in my area for menu styling.
Easy to read colors and similar pricing to whats in the area.
If not already noticed anything you can click on that will activate
    will change colors when hovering.

Navigating to the "Venue" page shows my favorite layout on other sites
    for displaying upcoming events.
There is plenty of room for adding supporting bands or any other info.
The times for doors opening and pricing is clearly on display to avoid
    confusion as some sites only post one time.
There is also side by side Labels for "Search" and Joining a newsletter.
This may be a small page but I experienced two things I had fun overcoming.
One was getting all the pictures to match the banner they are within
    when in the bigger resolutions and then having the same sized border
    around the image when in smaller resolutions.
The other experience was getting the Tickets button and prices to behave
    and turned into a good way to practice with CSS and the different ways
    to manipulate using flex.

The last page "Contact Us" shows contact info along with open hours.
This project was made 2 months into learning to code so figuring out how
    to use google maps on a website was exciting just how customizable it was
    right from google.
The map does not use a pin because the restaurant does not exist but could
    easily be added.
There is a Form at the bottom that behaves very similar to the "Schedule
    Event" Modal with the intent being for lost items or just spreading
    a good message about the restuarant.
It uses light validation mainly just on the Email.
Same as the Modal sumbitting does nothing intentionally because it does
    not have a back end.

Thanks for taking the time to view!

/////////////////////////////////////////////////////////////////////////////

If running locally from github:

Make sure you have Node.js installed it does not have a true backend but a
    small amount of node is there when navigating between the pages.
Within your terminal install the dependancies with "npm i".
Then to start the project use "npm start".