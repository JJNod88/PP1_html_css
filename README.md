# PP1 Name ..


## Introduction
Welcome to Your 5-A-Side

A site where you can Join, Create  and manage a 5-A-Side Team in Manchester, UK.

It is designed for people looking for a good blend of social and fitness activities. Everyone is welcome and has access to the available games in their area. 

The site will be targeted toward people who have a keen interest in football, socialising and keeping fit. The site provides details of the benefits of joining, gives them the ability to check the next avaialble games, meet existing teams and a sign up section.

I have used real world teams and players, including images to give the site authenticity, and to connect with users.

## UX
# Structure
* For the site I have used HTML for the core structure and CSS for styling -
    * HTML structuring:
        * Whilst i followed the industry standard for a core html structure, to ensure my site was consistent i used Flex boxes to structure my content. 
        * this proved extremely beneficial in structuring each section. I used no more than 3 divs per section using display:flex, this meant each section is positioned equally in either 100%, 50% or 33% divs. This increases the visual consistency and display of my content, and allowed my elements to be aligned.
        * I ensured I correctly linked my CSS stylesheet (checked using the background color technique) with appropriate SEO key words so my site is searchable on the internet.
        * Because of the way i structured my site, I was able to duplicate many of my html elements into new pages. this was great for time saving and consistency.
    * CSS
        * I created an asset folder that held my style.css sheet which allowed me to style many pages at once. I linked this in to the html using rel and href attributes 
        * Images were kept in the asset folder under an inserted Images foler, this ensured there would always be an image there, without the risk of an external owner closing a website or authorisations. 
        * I used Pexels for the background and form image, this is a free image site that requires no consent. My other two images were taken by myself. 
        * Some of my pictures needed scaling. I used the free site promo.com to resale, and compressor.io to reduce the size of my image files. 



    * The site has been designed to be simple, effective and easy to navigate. This includes navigation, background and font color, relatable images, responsive and accessibility. 
    * Font color and sizing has been designed to be clearly visible, consistent with appropriate sizing.
        * Font sizing has been duplicated where possible. This includes appropriate proportions for icons vs their text, all headers on each page the same size and font.
        * Font color has been consistent, with a basic and effective pallet. Dark Green using 'rgb' is the standard font color, with white for backgrounds and red for highlighted navs, buttons and icons.
        * Font Style was imported from Google Fonts, I chose Roboto and Lora with a back up sans Serif. This gave headings and their text meaning.
        * I used font styling across the site. This includes font spacing for (header) and line heights (p's and addresses) to make text easier to read.
    * Background kept simple, only differentiating in color to define sections of the page, minus backgorund images.

 
## Features:

### Landing Page (Home)
* Landing Page
    * An image of a football will instantly tell the user the sites main focus, giving it visual context to grab their attention.
    * The image will have text overlay with the Sites Name, a catchy slogan, and a location. 
    * The image has an opacity value, to help blend the text and header. 
* Header and Nav Bar consistent throuhgout
    * The site has a Navigation bar accessible at all times, that blends in to the web page. It includes a link to the *Home*, *Community* and *Sign Up* pages. 
* Section below
    * The format here will be consistent throughout the site
    * It will include an introduction to the site
    * A brief description of the benefits of the site including *keeping fit*, *socialising* and *friendly*. 
* Game On ection
    * A Header highlighting the prupose and directing users to available games
    * Linked Signup button below the available games links them to the 'Captain' section on aother page when they click on it
* Footer
    * A simple Footer with links to Social Media, this will be consistent across all pages for UX and UI.

### Community Page
* Header and Nav Bar consistent throughout
* Tect from the founder beside an image of the team that started it all
    * Captain 1 and 2. Accompanied by a header with their date/time of game, image and an intro paragraph.
* Where
    * Image of the Football Pitch we play
    * Below this a section with the Name and Address of the pitched
    * A Google Maps sextion will be adjacent to the Address details
* Footer

### Sign Up
* Header introducing the Sign Up page
    * Image of an astro football pitch
    * Transparent Form in the centre to ensure UX is maintained. 
    * The form method will be 'GET' and it will ask for **First Name**, **Last Name**, **Email Address** and**Location** with a radio buttons of **Manchester** and **Other**.


UX
For headers i used the same style and formatting.
Have used FlexBox across the site promoting fluidity and repetition for site structure
Copied my html and css structure when possible for site consistency
for sign up and home page, same size first section & image
Font sizes for main title and ending title the same
color theme consistent
Eahc section mupltiples of 90px, often the same height each page
_blank used to keep users on the site when viisting externals
nav bar fixed, and colored to be visible across all site
Footer equal size and consistent on each page


## Testing


## Validator Testing


## All things Bugs and Fixes
Bug: Theres a single circle in one of my div elements as part of my 'li'. I have text-decoration:none but still shows. It shows on Dev Tools but theres nothing in my html pointing to what it is. 

Fix: had line-style-type: non in the 'li' not 'ul.

Bug: Font not working properly.

Fix: Capitalise first letter of font with brackets.

Bug: Cant get my button to move in 'upcoming ganes'. I can style but not move it. 

Fix: none

Bug: Not sure how to have the active only highlight current page. It highlights home regardless

Bug: Icons not aligned.

Fix:

## Deployment


## Credits
Flexbox positioning, learned from https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox introduced by my mentor

Confirming button html and css https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button

w3schools - Added opacity to my images
https://www.w3schools.com/html/html_form_elements.asp for Form > Select element

Adding Google Maps - a google search had bullet points that i easily followed

Love Running project for media query rereshing
Stack Overflow for the correct media min max for images.

promo.com for picture re-sizing

## Content


## Media