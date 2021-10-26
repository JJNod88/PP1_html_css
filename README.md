# My 5-A-Side


## Introduction
Welcome to My 5-A-Side

A site for footballers looking for a new game, new players to add to their squad or a place they can create and manage a 5-A-Side Team in Manchester, UK.

It is designed for people looking for a good blend of social and fitness activities. Everyone is welcome and has access to the available games in their area. 

The site will be targeted toward people who have a keen interest in football, socialising and keeping fit. The site provides details of the benefits of joining, gives them the ability to check the next avaialble games, meet existing teams and a sign up section.

I have used real world teams and players, including images to give the site authenticity, and to connect with users.

## Value
# To ther User
* The site has an SEO defined to accurately show up when people search for 5,6 and 7-a-side football games in Manchester.
* Designed to be simple and engaging, users will know instantly what the sites intention is, and can navigate around the site with ease.    
    * Navigation elements in the header, footer and icons/buttons means they can access all parts of the site no matter where they.
    * The site has been seperated into sections with a clear purpose. Headers and their corresponsding information are clear and easy to distinguish.
    * Div, Icon and Buttom elements have been styled to Hover to improve the interactiveness of the site.
* They will see the benefits to the site, and to football, and can see what games are available with details around the captains and why the games were created. They'll be able to click on locations of the games to be directed to detailed address and google maps of the football pitches, which open on a seperate browser. An easy to fill in form means they are not spending a long time signing up. 
* The site is responsive, so they can access the site on the move on their smartphone, tablet or desktop.
* Specific Images have been used to make the site easier on the eye and fun to view. 
* All images have an alt attribute for those needing a site that is accessible. 


## Screenshots


## UX
# Structure
* For the site I have used HTML for the core structure and CSS for styling -
    * HTML structuring:
        * My structure includes three pages, each with: Header & Nav > Sections with headers, divs and additional elements > Footer & Nav.
        * Whilst I followed the industry standard for a core html structure, I used Flexboxes to structure my content throughout.  
        * This proved extremely beneficial in structuring each section. I used no more than 3 divs per section using display:flex, this meant each section is positioned equally in either 100%, 50% or 33% divs. This increases the visual consistency and display of my content, and allowed my elements to be aligned.
        * I ensured I correctly linked my CSS stylesheet (checked using the background color technique) with appropriate SEO key words so my site is searchable on the internet.
        * Because of the way I structured my site, I was able to duplicate many of my html elements into new pages. This was great for time saving and consistency.
    * CSS
        * I created an asset folder that held my style.css sheet which allowed me to style many pages at once. I linked this in to the html using rel and href attributes 
        * Images were kept in the Asset folder under an inserted Images folder, this ensured there would always be an image there, without the risk of an external owner closing a website or authorisations. 
            * I used Pexels for the background and form image, this is a free image site that requires no consent. My other image for the Location section was taken by myself. 
        * Some of my pictures needed scaling. I used the free site promo.com to rescale, and compressor.io to reduce the size of my image files. 

# Site layout
* The site has been designed to be simple, effective and easy to navigate. 
    * Layout
        * My site consists of a landing page with content, a commutiy page with content, and a sign up page with a form. 
        * Each page is divided into sections of equal size (unless it affected the look of the site, i.e the opening section for the background image)
        * Headings and Images are specific.
        * Each section has been designed to sell, provide information and direct the user to the product. 
        * For my background color I used rgba 0.1 green, which allows for content to be easily visible and also minimilistic whilst the green matched the theme of a football site. I have seperated sections using the standard white background color or Images.
    * Navigation 
        * I have used lots of naviation in my site, to allow users to navigate the site with ease.
            * A visible header, with a position:sticky and Z-index of 999 means it is always accessible and visible. The title and three page navs link to all aspects of the site. 
                * This is the same for the Footer.
            * In my icons I have added href links to the appropriate sections and pages. An example of this is the 'how' icons on the index page. They direct to sign up and to the available game section. I have also used :hover elements to make them stand out and easier to click on. 
            * My buttons have links, and also stand out with red backgrounds. I have also used :hover elements to make them stand out and easier to click on. 
    * Font size, color, type and styling:
        * Font color has been standardised to dark green, designed to be clearly visible, consistent and following the football theme color.
        * Font sizing has been duplicated where possible. This includes appropriate proportions for icons vs their text, all headers on each page the same size and font. Have used % to icnrease responsiveness.
        * Font Type was imported from Google Fonts, I chose Roboto and Lora with a back up sans Serif. This gave headings and their text meaning and provides a foundation font should the google fonts ever be unreadable on a browser. 
        * I used font styling across the site. This includes font spacing for (header) and line heights (p's and addresses) to make text easier to read.

# Accessibility
    Semantic HTML - Headers, ULs provide addiitoal functionality and operation by keyboard, tab keys and enter.
    Text Content - HTML strucutre, headings p and lists, screen reader can have indiciators to read out, so the way site flows can help the screen reader
    Page Layouts - section and navs, provides screen reader hekps
    UI Controls - Buttons links and Forms. Browsers can be accessed using. akeyboard, using tab. 
    Form Labels - Connecting Inputs to Labels, id and for. scren Readers can lavel fields
    Aria Attributes - Aria - acceisble rich internet applications. 
    Alt for CSS Images

# Responsiveness
* Structure:
    * I used FlexBox to structure my elements which is an extremely responsive way of structuring the site. With display:flex and flex:1 for example, all of my sextions and divs were automatically positioned correctly, and did so when scaling your screen size up or down. This saves a lot of time and looks great!
* % units:
    * Across the site I have used % for sizing. This inclused in height, width, padding, margins and font-sizes etc. I implemented this from the beginning to ensure my design was adaptive across multiple screen sizes - This is extremely important in todays world as there is not one size fits all. 
* Media queries and designs have been implemented at different screen resolutions  to ensure the site is responsive at different sizes and can be used on any device.
    * Using Google Developer, I have tested each element of the site to ensure it responds to scaling.
        * For smartphones and Tablets I adapted the media queries to use smaller images, fonts and changed structures by using Flex-Directions. 
        * I grouped my elements as much as I could to reduce the amount of changes to the layout. I started my Media Queries at max 1250px which is around the industry standard size for desktop screns and worked my way down, until I got to smartphones with a Media Query set up for Min 0px and Max 480px. 
        * Seperating my Media Queries like this really helped as I tested the site scaling. Fortunately I have two screens t work from which meant not only could I code whilst using GDeveloper, I can test the Site realtime using an Apple MacBook Screen and a HP Large Desktop Monitor Screen.

 
## Features:

### Landing Page (Home)
* Consistent interactive Header and Nav elements are used throughout the entire site.
    * The site has a Navigation bar accessible at all times, that blends in to the web page. It includes a link to the *Home*, *Community* and *Sign Up* pages.    
    * A simple Footer with links to *facebook*, *Email/Contact us* and *Sign Up* pages.

* Landing Page section -
    * An image of a football will instantly tell the user the sites main focus, giving it visual context to grab their attention.
    * The image has. text overlay with the Sites Name, a catchy slogan, and a location. Re-inforcing the reason the site exists and why the User is visiting.  
    * The image has an opacity value, to help blend the text and header.  
* Benefits Section -
    * A Catchy phrase giving the User an other reason why they are visiting. 
    * Benefits displayed with appropriate Icons in Red, in a List style. 
* Map and Key Indicator Section -
    * There is a basic Map with Manchester circled, reminding the user of the sites taregteed locations
    * Adjacent to the Map are some Key Indicators of how many live games, members and Goals there is. This was to give the User a personal feel to the site, one where if they are a member they can contribute too.
* 



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

bug: how to alt and reference images done in css

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

Image of UK - http://www.supercoloring.com/coloring-pages/united-kingdom-blank-outline-map. Author: Supercoloring. License: Creative Commons Attribution-Share Alike 4.0 License.

## Content


## Media