# Cobonkoi Games

User Centric Frontend Development Milestone Project

This is a website created for Cobonkoi Games, an indie games development company that are currently developing their first game.
The website includes information on the company/employees, the game that is currently being developed and contact information should you wish to get in touch.
In addition it allows you to sign up for the alpha testing of "Hard Brexit", and a monthly newsletter.

The goals of the website are to:
 - Build awareness of Cobonkoi Games
 - Provide information about the games created by Cobonkoi Games
 - Provide information on the progress of the games that are in development
 - Get people to sign up to Alpha Testing
 - Get people to sign up to the Newsletter

## Demo

A demo can be viewed on Github Pages [here](https://cobonkoi.github.io/cobonkoi-games/).
 
## UX
My goal was to provide a simple design for the website to provide lots of information in small, easily digestible chunks.
To do this I have made the navigation easy to understand. Each section on the pages are clearly titled and seperate from one another.

The website is for people who would like to know more about Cobonkoi Games and/or the games they develop. Also for people who wish to become alpha testers for them.

#### User Stories

1. As a new visitor to the site, I want to be able to easily navigate the site, so that I can find what I want easily.
2. As a new visitor to the site, I want to see the games this company has created, to see if they are worth purchasing.
3. As an interested Alpha tester, I want to sign-up to become a tester, so that I can begin testing games.
4. As a person interested in Cobonkoi Games, I want to learn more about the company, so that I can decide whether to support them further.
5. As a person interested in Cobonkoi Games, I want to learn how I can contact them, so that I can receive further information.
6. As a person interested in Hard Brexit, I want to learn more about the game, so that I can decide whether I would like to purchase it on release.

#### Wireframe Mockups

- [Index](wireframes/index.png).
- [Index - Mobile](wireframes/indexmobile.png).
- [Index - Mobile - Menu](wireframes/indexmobilemenu.png).
- [Hard Brexit](wireframes/hardbrexit.png).
- [Hard Brexit - Mobile](wireframes/hardbrexitmobile.png).
- [About](wireframes/about.png).
- [About - Mobile](wireframes/aboutmobile.png).
- [Contact](wireframes/contact.png).
- [Contact - Mobile](wireframes/contactmobile.png).


## Features
Each page features an alert that will only appear on larger screen sizes, this provides information about Hard Brexit Alpha testing and a link for more information.
Each page features a navigation bar that is responsive to screen sizes. This contains links to each other page, as well as the company name in the top left.
Each page features a footer which contains links to 5 social media pages for the company.

#### Home
This page features a large carousel with 2 slides on it. This has indicators on the bottom to show which slide you are currently on. 
On larger screens it features navigation arrows to switch between the slides, these are removed on mobile due to being too obstructive.

Slide 1 features a little information about the game Hard Brexit, as well as a button to sign up to the Alpha.
The Sign-Up button bring a modal up on screen which can be used to input data.
This form will check for valid data and warns the user if there is data missing or in the incorrect format.

Slide 2 features a little information about the newsletter and an input box to enter your email and submit it.
This form will check for valid data and warns the user if there is data missing or in the incorrect format.

#### Hard Brexit
This page features firstly, a section detailing the game with an embed teaser video hosted on youtube. This does not autoplay as it contains music and
this playing unexpectedly would make for poor user experience.
On the mobile version the video will appear under the text instead of to the side. This provides a much better viewing experience on mobile.

The second section features an embed soundcloud album of soundclips from the game, this also will not autoplay.

The third section features another sign-up button for the Alpha. 
The Sign-Up button bring a modal up on screen which can be used to input data.
This form will check for valid data and warns the user if there is data missing or in the incorrect format.

#### About
This page features firstly, a section detailing the company itself, with an accompanying image.

The second second features images and text to give details on the employees.

In both of the sections on this page, the text and images become full columns on mobile instead of appearing next to one another.
This provides a much better viewing experience on mobile.

#### Contact
This page features 3 seperate blocks with information in each on larger screen sizes.
On mobile devices they become full columns and follow one after the other with dividers to define where the sections end.

One section contains the 5 links from the footer of the page.

While another section contains a form that will enable you to contact the company directly.
This form will check for valid data and warn the user if there is data missing or in the incorrect format.
 

### Existing Features
- Alpha Sign-Up form - This form allows the user to sign up for the "Hard Brexit" Alpha by having them fill in their information and submitting it.
- Newsletter Sign-Up - This allows the user to sign up for a newsletter by having them fill in their email address and submitting it.
- Contact Us Form - This form allows the users to contact the company by having them fill in their details and message and submitting it.

### Features Left to Implement
- A gallery containing screenshots of the game on the Hard Brexit page.

## Technologies Used
1. HTML
2. CSS
3. Bootstrap (4.3)
4. JQuery

## Testing
1. Alpha Sign-Up form:
    1. Went to the "Index" page
    2. Tried to submit the empty form and confirmed that an error message about the required fields appears.
    3. Tried to submit the form with an invalid email address and verify that a relevant error message appears.
    4. Tried to submit the form with all inputs valid and verify it submits.

2. Newsletter form:
    1. Went to the "Index" page
    2. Tried to submit the empty form and confirmed that an error message about the required fields appears.
    3. Tried to submit the form with an invalid email address and verify that a relevant error message appears
    4. Tried to submit the form with all inputs valid and verify it submits.

1. Contact Us form:
    1. Go to the "Contact Us" page
    2. Tried to submit the empty form and confirmed that an error message about the required fields appears.
    3. Tried to submit the form with an invalid email address and verify that a relevant error message appears
    4. Tried to submit the form with all inputs valid and verify it submits.

## Deployment
This site is hosted on Github Pages, it uses the master branch. The site updates automatically every time there is a new commit to the master branch.


### Media
- The workspace image on this site was found on [Pexels](https://www.pexels.com/), a stock image website.
- The Union Jack image on this site was found on [Pixabay](https://pixabay.com), which allowed free commercial use of this image.

This is for educational use.