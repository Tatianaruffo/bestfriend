<h1>Best Friend.ie</h1>

View the live project [here](https://tatianaruffo.github.io/bestfriend/)

Best Friend.ie is a Dog rescue shelter webpage to find new homes for rescued dogs in Ireland. The site describes the personality of each dog to help people looking for a new dog friend to connect.

The website has 3 pages, the main one helps the user to trust the shelter telling about the story of the shelter and happy stories of previous adoptions, the second page is a list of dogs available for adoption, you can read about their story and personalities. The last page is dedicated for the user to book a visit to the shelter.

![Mockup](documentation/readme-images/mockup.png)


## Contents

- [Users Stories](#users-stories)
   - [Site Owner Goals](#site-owner-goals)
   - [Users Goals](#users-goals)
- [Design](#design)
  - [Prototype](#prototype)
  - [Typepgraphy](#typography)
    - [Primary Font](#primary-font)  
  - [Colour Palette](#colour-palette)
    - [Primary Colour](#primary-colour) 
    - [Dark Colour](#dark-colour) 
    - [White Colour](#white-colour) 
- [Features](#features)
  - [Navigation Bar](#navigation-bar)
  - [Landing Page](#landing-page)
    -[First Section](#first-section)
    -[Happy Stories](#happy-stories)
    -[About us](#about-us)
  - [Book a Visit](#book-a-visit)
  - [Adopt](#adopt)
  - [Footer](#footer)
- [Testing](#testing)
  - [Browsers](#browsers)
  - [Lighthouse](#lighthouse)
    - [Desktop](#desktop)
    - [Mobile](#mobile)
  - [HTML Validation](#html-validation)
  - [CSS Validation](#css-validation)
- [Credits](#credits)
  - [Code](#code)
  - [Resources](#resources)


# Users Stories

### Site Owner Goals
- I want users to easily navigate the website
- I want user to book visits to the shelter 
- I want users to see our history 
- I want users to see happy adoptions stories
- I want the user to connect with a dog through their stories

### Users Goals
- I want to learn about the shelter
- I want to know about previous adoptions stories
- I want to visit the shelter and see the dogs 
- I want to see the dogs available for adoption

# Design 

## Prototype

Prototype was created using [Figma](https://www.figma.com/)

<img src="./documentation/readme-images/prototype-index.JPG" alt="Website Prototype" width="30%" height="30%">
<img src="./documentation/readme-images/prototype-adoption.JPG" alt="Website Prototype" width="30%" height="30%">
<img src="./documentation/readme-images/prototype-book.JPG" alt="Website Prototype" width="30%" height="30%">

## Typography 
The fonts used are from [Google Fonts](https://fonts.google.com/).

### Primary Font:
[Inter](https://fonts.google.com/specimen/Inter?query=inter)

## Colour Palette 

Colour palette was generated using [ColorSpace](https://mycolor.space/).

### Primary Colour:
#B2BBAF

### Complimentary Colours:
#F2CDC3
#BEA6A0
#3B3D22
#56423D

### White Colour: 
Alice Blue

# Features

## Navigation Bar

* Desktop and laptop Navigation Menu
  * Contains links to the Home, Happy Stories, About Us, Book a Visit and Adopt pages.
  * Is identical in each page to allow for easy navigation.
  * Will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

![Nav Menu](documentation/readme-images/navbar.JPG)

* Tablet and mobile Navigation Menu
  * Hamburger menu with a dropdown options to the Home, Happy Stories, About Us, Book a Visit and Adopt pages.

![Nav Menu](documentation/readme-images/navbar-responsive.JPG)

## Landing page 

* The landing includes 3 sections:
  * First Section with CTA 
  * Happy Stories
  * About Us

### First Section

* Contains a hero image and a CTA button, is responsive for smaller screens 

![First Section](documentation/readme-images/First-section.JPG)

![First Section Responsive](documentation/readme-images/first-section-responsive.JPG)

### Happy Stories

* Happy Stories Section will allow the user to see the benefits of adopting a Dog through true stories from previous adopters

![Happy Stories](documentation/readme-images/happystories-image.JPG)


### About us 

* This Section allows the user to understand the story and purpose of the shelter

![About us](documentation/readme-images/aboutus-image.JPG)

## Book a visit page

* This Section contains a form where the user can book a visit to the shelter
  * The user can choose the day of the week, period and time range to visit.
  * On successful submission of the booking form, the user will be navigated to thankyou.html displaying a thank you message.

![Book a Visit](documentation/readme-images/form-image.jpg)

## Adoption page

* This page allows the user to see the dogs that are ready for adoption.
  * When the user hovers the mouse on each dog picture it will show the story and personality of the dog.
  * Each picture contains a CTA button that leads to the book a visit page, allowing the user to meet the dog personally 

![Adopt](documentation/readme-images/adopt-image.JPG)

## The Footer

* The footer section includes links to the relevant social media sites for Best Friend and contact details. 
 * The social media links will open to a new tab to allow easy navigation for the user.
 * The email and phone are hyperlinks for easy contact for the user

![Footer](documentation/readme-images/footer.JPG) 

## Features Left to Implement

* The About us section should be a separate page telling the user more about the shelter to improve trustworthy.
* A page with tips for first time pet owners 

# Testing

## Lighthouse Testing

### Desktop

![Testing Landing Page](documentation/readme-images/lighthouse-landingpage.JPG)

![Testing Form](documentation/readme-images/lighthouse-form.JPG)

### Mobile

![Testing Mobile Landing Page](documentation/readme-images/lighthouse-mobile-landingpage.JPG)

![Testing Mobile Form](documentation/readme-images/lighthouse-mobile-form.JPG)

### Validator Testing

#### HTML
No errors were returned when passing through the official W3C validator

#### CSS
No errors were found when passing through the official (Jigsaw) validator

#### Unfixed Bugs
You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub)

The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html

## Credits
https://refine.dev/blog/css-grid-vs-flexbox/

https://michmattera.github.io/newline-alebrije/ -Grid/Flex

https://www.w3schools.com/html/html_form_input_types.asp - Form

https://stackoverflow.com/questions/9182978/semi-transparent-color-layer-over-background-image - layer background


## Content
The text for the Home page was taken from Wikipedia Article A
Instructions on how to implement form validation on the Sign Up page was taken from Specific YouTube Tutorial
The icons in the footer were taken from Font Awesome

## Media
Hero image - Victor Grabarczyk Unsplash https://unsplash.com/photos/N04FIfHhv_k

Form Image - Fabian Gieske - Unsplash - https://unsplash.com/photos/AXtlIC-eHjQ

Adoption photos

Fudge - Jamie Street - Unsplash https://unsplash.com/photos/UtrE5DcgEyg?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink