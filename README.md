# My 5-A-Side

# Contents
* [Introduction](#Introduction)
* [Value](#Value)
* [UX](#UX)
* [Accessibility](#Accessibility)
* [Responsiveness](#Responsiveness)
* [Features](#Features)
* [Technologies](#Technologies)
* [Validation](#Validation)
* [Testing](#Testing)
* [Deployment](#Deployment)
* [Credits](#Credits)



# Introduction
Welcome to My 5-A-Side

The focus of this site is to provide a fictional platform for people to locate available football games and players in their local community.

The site is aimed at footballers and people looking to get involved in football, bringing a social aspect with real life football pitch locations, captains and teams. It outlays the benefits of playing football, calculating game stats and giving users the opportunity to contact propsective teams and sign up to use the site.

I have used real world teams, players and images to give the site authenticity, and to connect with users and members.

![image-of-responsive-site-design](/assets/images/readme-images/am-i-responsive.png)


# Value
### New User / Target Audience
* Users who are both new and experienced in playing football, specifically 5, 6 and 7-aside football. 
* Who want to learn of the benefits to playing 5-a-side.
* Who do not currently play in a team and are looking to join one.
* Who play as part of a team and want to find new players.
* Who have a team but want a platform to manage their locations, fixtures and players easily and digitally.

### Return User
* Users who have previously utilised the site to find players 
* Who have previously utilisted the site to find games
* Who would like to use the sites functionality to find locations of games and teams 

### Site Aims
* The site aims to provide users a platform for finding new players and games to connect with.
* Providing the opportunity to:
    * Learn the benefits of 5-a-side and the site
    * See live stats of the games history to help the site come to life. 
    * View games, teams and locations of available football games.
    * Sign Up to the site via a form
    * Have access to relevant parts of the sites with links and buttons contained in Header, Footer and Section elements.
    * Build a pool of players and Teams, with increased functionality that can be commercialised.

### How the Site achieves this
* The site has an SEO defined to accurately show up when people search for 5,6 and 7-a-side football games in Manchester.
* A consistent Header and Footer will be accessible at all times for each user, with the title of the site consitently in view.
* Designed to be simple and engaging, users will know instantly what the sites intention is, and can navigate around the site with ease. 
    ### Page specific
    * Index / Home Page contains images of a football pitch and ball, key benefits to the site, stats on current games, how-to-guide to sign up and a peer review.
    * Community Page provides available games with key information, with links to the locations of each game including address details, google maps link and an image of the corresponding football pitch.
    * Sign Up page provides a simple form to allow sign up, with an image giving the impression of a football player / manager signing a contract.
    * Submit Page provides confirmation of users successful sign up, and allows them to return to the Index / Landing Page.
    ### Site specific
    * The landing page has a background-image of a football pitch and ball, giving the user an instant impression of the sites use.
    * Navigation elements in the header, footer and icons/buttons means they can access all parts of the site no matter where they are.
    * The site has been seperated into sections with a clear purpose. Headers and their corresponsding information are clear and easy to distinguish, Images have been used that are appropriate for the site, and the sections they are in.
    * Div, Icon and Buttom elements have been styled to Hover to improve the interactiveness of the site.
    * Users can click on locations of the games to be directed to detailed address and google maps of the football pitches, which open on a seperate browser. An easy to fill in form means they are not spending a long time signing up. 
    * The use of real world images, players and locations give the site authenticity and a personal touch, giving it relateability.
    * The site is responsive, so they can access the site on the move on their smartphone, tablet or desktop.
    * Specific Images have been used to make the site easier on the eye and fun to view. 
    * It is inclusive. It has social media, contact links and forms to be able to sign up. 

# UX
The Site needed to be intuitive, simple, and provide an enjoyable experience for the Users. 
For UX, I kept in mind the Five pillars of good UX, and used these as foundations for my Website. 

## 1. Strategy Plane -
* I have explained the strategy around the site in detail in my Values page [here](#Value)
    * Why the product exists, its goals and who are the users.
* I used Wireframes for the basic design, utilised traditional football colours, kept the site simple, engaging and intuitive.
 
## 2. Scope Plane -
This includes the features needed to provide content, material and access for Users. 
* You can find this in detail [here](#Features) in my Features section.
    * I needed to ensure the content was relevant and outline the key functions for a User of the site - Benefits, locations, feedback from current users, access to team information and the ability to sign up. 

## 3. Structure Plane -
### Structure

* For the site I have used HTML for the core structure and CSS for styling -
    * HTML structuring:
        * My structure includes four pages, each with: Header & Nav > Sections with headers, divs and additional elements > Footer & Nav.
        * Each page is ordered to go left to right, with the suitable direction of the Landing Page, Community Page and then the Sign Up page where users have had sufficient time and knowledge on whether they would like to sign up.
        * Whilst I followed the industry standard for a core html structure, I used Flexboxes to structure my content throughout.  
            * This proved extremely beneficial in structuring each section. I used no more than 3 divs per section using display:flex, this meant each section is positioned equally in either 100%, 50% or 33% divs. This increases the visual consistency and display of my content, and allowed my elements to be aligned.
        * The site structure and its elements can be easily changed.
        * I ensured I correctly linked my CSS stylesheet (checked using the background color technique) with appropriate SEO key words so my site is searchable on the internet.
        * Because of the way I structured my site, I was able to duplicate many of my html elements into new pages. This was great for time saving and consistency.
        * For the sections of my site, i used multiples of 90px when possible to keep the site consistent.
        * Some of the sections do change in format as screen resolutions reduce, however the structure of the site remains in the same order.
    * CSS
        * I created an asset folder that held my style.css sheet which allowed me to style many pages at once. I linked this in to the html using rel and href attributes 
        * Images were kept in the Asset folder under an inserted Images folder, this ensured there would always be an image there, without the risk of an external owner closing a website or authorisations. 
        * I used Pexels for the background and form image, this is a free image site that requires no consent. My other image for the Location section was taken by myself. 
        * Some of my pictures needed scaling. I used the free site promo.com to rescale, and compressor.io to reduce the size of my image files. 

## 4. Skeleton Plane -
### Site Layout

I used [Balsamiq](https://balsamiq.com/) for my wireframes. This gave a great indication of how the site will look once completed. Please see them below.

<details><summary>Balsamiq WireFrames</summary>

### Desktop

* In order of Pages 1 - 4:

![image-of-wireframe-page-1-desktop](/assets/images/readme-images/Page-1-dt.png)

![image-of-wireframe-page-2-desktop](/assets/images/readme-images/Page-2-dt.png)

![image-of-wireframe-page-3-desktop](/assets/images/readme-images/Page-3-dt.png)

![image-of-wireframe-page-4-desktop](/assets/images/readme-images/Page-4-dt.png)

### Smart Phones

* In order of Pages 1 - 4:

![image-of-wireframe-page-1-mobile](/assets/images/readme-images/Page-1-m.png)

![image-of-wireframe-page-2-mobile](/assets/images/readme-images/Page-2-m.png)

![image-of-wireframe-page-3-mobile](/assets/images/readme-images/Page-3-m.png)

![image-of-wireframe-page-4-mobile](/assets/images/readme-images/Page-4-m.png)


</details>

* The Site needed to be presented in an intuitive and simple way. One that makes it easy to use with its naviagtion and features.
    * Layout
        * Each page has the same Header and Footer.
        * It consists of a landing page, a community page, a sign up page and a submit successful page. 
        * Left to Right, the Site flows correctly and in an order. Home > Community > Sign Up.
        * Each page is divided into sections of equal size (unless it affected the look of the site, i.e the opening section for the background image). The height of each section is in mupltiples of 90px to maintain consistency throughout. 
        * Headings and Images are specific to the sites purpose.
        * Each section has been designed to sell, provide information and direct the user to the product. 
    * Navigation 
        * I have used lots of navigation in my site, to allow users to navigate the site with ease.
        * A visible header, with a position:sticky and Z-index of 999 means it is always accessible and visible. The title and three page navs link to all aspects of the site. 
            * This is the same for the Footer.
        * In my icons I have added href links to the appropriate sections and pages. An example of this is the 'how' icons on the index page. They direct to sign up and to the available game section. I have also used :hover elements to make them stand out and easier to click on. 
        * My buttons have links, and also stand out with red backgrounds. I have also used :hover elements to make them stand out and easier to click on. 
        * _blank has been used to ensure new tabs are created when a user is directed to one, to keep them active on my website      

## 5. Surface Plane -

### User Friendly
* The sites main goal and content is specific: 
    * It functions correctly and demonstrates to its users why it exists and how it can provide them with solutions to their problems and needs.

### Site Color palette

<details><summary>Color Palette in principal </summary>

![image-of-footer](/assets/images/readme-images/color-palette.png)

</details>

* The sites main colors of choice are Green, White, Black and Red - 
    * Green, white and black are traditionaly associated with football, as the color of a football pitch is traidtionally green, with white lines. 
    * I used red as a background for text, icons and attributes as it effectively stands out against the other colors. Often, football corner flags are red.
    * I ensured all text, images and content was distinctly visible, careful not to use colours that contrast and make them hard to distinguish from one another.  
* For my background color I used rgba(0,44,0,.1);, which allows for content to be easily visible and also minimilistic whilst the green matches the theme of a football site. I have seperated sections using the standard white background color or Images for good contrast and simplicity.

###  Font size, color, type and styling:
* Font color has been standardised to dark green, designed to be clearly visible, consistent and following the football theme color.
    * Background Color was set to: rgba(0,44,0,.1)
    * Text Color was set to: rgb(0,43,0);
    * For Icons, attributes, and form background, it was set to: #df1616
    * Opacity was used to enable to text and forms to be more visible. 
* Font sizing has been duplicated where possible. This includes appropriate proportions for icons vs their text, all headers on each page the same size and font. Have used % to increase responsiveness.
* Font Type was imported from Google Fonts, I chose Roboto and Lora with a back up sans Serif. This gave headings and their text meaning and provides a foundation font should the google fonts ever be unreadable on a browser. 
* I used font styling across the site. This includes font spacing for (header) and line heights to make text easier to read - Headings, paragraphs and lists primarily.

### Images
* Images were chosen that represented the sites identity. Stored in an Assets folder so they would always be visible. 
    * Landing Page has a picture of a football pitch that gives the site meaning instantly to the user.
    * Use of real images of the football teams (Location section) gives the site meaning.
    * A ReadMe Images folder was created, for images utilised in the ReadMe. 

# Accessibility
* The site is accessible to Users who may have a disability that prevents them from accessing the site in certain ways.
    * The foundation of this is the site layout and semantic HTML elements.
        * The Page is layed out with a standard HTML format to improve its flow, allowing screen readers to indicate header, nav, section, heading, p, ul, form and footer elements of the site. 
        * Using these Semantic Elements in the correct order provides additional functionality for tab keys and screen readers to highlight the key information and content.
    * UI Controls - Nav bar is set to Float Left so that you can use the tab to navigate it accurately. All buttons are accessible using the keyboard tab and enter functions.
    * For the form, I have used labels and linked them to inputs so that a screen reader can distinguish each field.
    * To ensure I have provided enough information for any links in my site, I have added aria-label outlinining the purpose of the link, and have used brackets if it is taking the person to a new tab.
    * Images have been included using css statements, the w3c validator was telling me that these were not required as a result of this. 

# Responsiveness
### Structure:
* With todays technology and the multitude of devices that can access the Internet, programmes etc, it is exremely important to ensure the site can be used and looks great despite the size of the screen.
* The site has been designed to adapt to any screen size. This started out by adding a viewport in the HEAD of all pages with the addition of media queries and images. 
    * Flexbox has been used to structure my elements which is an extremely responsive way of structuring the site. With display:flex and flex:1 for example, all of my sections and divs were automatically positioned correctly, and did so when scaling the screen size up and down. This saves a lot of time and looks great!
    * Flex-Direction has been used also to restructure sections and screen sizes are reduced.
### Units:
* Across the site I have used primarily % for sizing. This inclused in height, width, padding, margins and font-sizes etc. I implemented this from the beginning to ensure my design was adaptive across multiple screen sizes - This is extremely important in todays world with so many devices of different sizes. 
### Media queries and designs 
* I have implemented different screen resolutions to ensure the site is responsive at different sizes and can be used on any device.
    * Using Google Developer, I have tested each element of the site to ensure it responds to scaling.
        * For smartphones and Tablets I adapted the media queries to use smaller images, fonts and changed structures by using Flex-Directions. 
        * I grouped my elements as much as I could to reduce the amount of changes to the layout. I started my Media Queries at max 1250px which is around the industry standard size for desktop screns and worked my way down, until I got to smartphones with a Media Query set up for Min 0px and Max 480px. 
        * Seperating my Media Queries like this really helped as I tested the site scaling. Fortunately I have two screens to work from which meant not only could I code whilst using Google Developer, I can test the Site realtime using an Apple MacBook Screen and a HP Large Desktop Monitor Screen.
* The site had thorough testing to ensure these Media queries worked and the site was responsive. Please visit [Testing](#Testing) for further detail and 
 
# Features:
### Header & Footer
* Consistent interactive Header and Nav elements are used throughout the entire site.
    * The site has a Navigation bar accessible at all times via the header, that blends in to the web page. It includes a link to the *Home*, *Community* and *Sign Up* pages.  
        * Navigation Bar is the same size throughout, and repsonds to responsive design in the same way.  
        * Navigation Bar is fixed with a position:fixed and a z-index: 999; ensuring it is always visible and accessible.
        * I gave the Nav an .active attribute so users knew which page they were on, but also gave them a hover border so they could easily click the correct page
    * A simple Footer with links to *facebook*, *Email/Contact us* and *Sign Up* pages.
        * The Footer is the same size throughout, and repsonds to responsive design in the same way. 
        * It has a Z-Index of 900 to ensure it is always visible, but not sticky as this would have impacted the visbility of the content.  

![image-of-header](/assets/images/readme-images/header.png)
![image-of-footer](/assets/images/readme-images/footer.png)


## Four pages -

### 1. Landing Page (Home)
* Landing Page section -
    * An image of a football will instantly tell the user the sites main focus, giving it visual context to grab their attention.
    * The image has text overlay with the Sites Name, a catchy slogan, and a location. Reinforcing the reason the site exists and why the User is visiting.  
    * The image has an opacity value, to help blend the text and header.  

![image-of-landing-page](/assets/images/readme-images/landing-page.png)

* Benefits Section -
    * A Catchy phrase reinforcing a reason as to why the user is visiting.
    * Benefits displayed with appropriate Icons in Red, in a List style. Gives the user the benefits to playing footy and using the website.
    * The structure of this section changes when at a reduced screen size to ensure the UX of it. 

![image-of-landing-page-benefit-section](/assets/images/readme-images/LP-benefits.png)

* Map and Key Indicator Section -
    * There is a basic Map with Manchester circled, reminding the user of the sites targeted locations.
    * Adjacent to the Map are some Key Indicators of how many live games, members and Goals there is. This was to give the User a personal feel to the site, one where if they are a member they can contribute to it.
    * I have included multiple images of the map for improved ux as the screen size reduces

![image-of-landing-page-map-stats-section](/assets/images/readme-images/LP-map-and-stats.png)

* How Section -
    * I have created 3 large icons with key words outlining how to use the site. 
    * The icons have a link to the corresponsing part of the site, with 'hover' styling to increase its size when a user hovers over them. Gives the user additional visual experience and navigation around the site.

![image-of-landing-page-how-section](/assets/images/readme-images/LP-how-to.png)

* Quote Section -
    * To give context and personality, a quote from one of the members of the site has been added. This is adjacent to a clear header.
    * The quote has a white background so it stands out, it in italic, and has a 'hover' styling for improved user experience (desktop).

![image-of-landing-page-feedback-section](/assets/images/readme-images/LP-feedback.png)


### 2. Community Page (Second)
* Same consistent header and footer
* Avalable Games section -
    * This section has details of the available games. It is designed to be inclusive with an image of the games creator with details of the game.
    * Each game section has a border with a 3D effect to help it blend in. It has a white background to stand out, with three accessible buttons.
    * Each button has a link to the corresponding part of the site, or external site depending allowing easy navigation for the User.
        * Request to Join - Takes the user to the sign up page if they are not a member.
        * Check Location - Takes the User to the Location section and its specific pitch location.
        * Contact Us - Takes the User to Outlook External Website, where they could contact the Game Creator (in the absence of a member chat area).

![image-of-community-page](/assets/images/readme-images/Community-Page.png)

* Location section - 
    * Background image of the football pitches that are specific to each available game. 
        * For this example, the background is indeed of the pitch, and players, of the available games. This gives the site personality and makes it relatebale to its members and users.
        * Embedded in the background image are two divs containing Address Details and a Google Maps link.
        * The Address details have a transparent red background, following the color scheme of the site, with large and readable text. This is informative with clear address details.
        * For additional site functionality, there is also a Google Maps image of the location, which can be enlarged and followed on an external tab.
        * The structure of this section changes when at a reduced screen size to ensure the UX of it. 

![image-of-community-location](/assets/images/readme-images/CP-Locations.png)


### 3. Sign Up Page (Third)
* Same consistent header and footer
* Form Section - 
    * Kept simple and to the point, there is only one section for the Sign Up page, and is clearly displayed as 'Sign Up'. 
        * It has a formal background image of a person in a suit writing down on paper on a desk. This image was chosen, as it reflects a football manager or player signing a football contract. So is relateable.
        * It is set at the same opacity as the landing page background image. This keeps theme consistency but also allows the form to be more visible.
        * The form method will be 'GET' and it will ask for **First Name**, **Last Name**, **Email Address** and**Location** with a radio buttons of **Manchester** and **Other**.
        * I have added 'required' into these inputs so that users are prompted to fill in all of their information correctly, and will ensure they have to before submitting.

![image-of-sign-up-page](/assets/images/readme-images/Sign-Up-Page.png)


### 4. Submit Page (Fourth - additional)
* To ensure excellent user UX, when submitting the button 'sign up' when completin the form, users are taken to a seprate page that consists with the sites design, to let them know that their sign up has been successful. There is also a message to wish them luck.
* They are able to return back to the home page using either the 'Home' Button on the Nav Bar or a highlighted link in yellow. 

![image-of-submit-page](/assets/images/readme-images/Submit-Page.png)

### Future Features

* I will add a carousel to the games section as more games are added.
* Using additional languages and programmes, I will enable users to create profiles, utilise a dashboard and allow them to manage their games and teams. 
* Add a payment section to collect player subs. 

# Technologies
* CSS
* HTML5
### Programmes
* Git - Version Control (add, commit, push)
* To Store Projects, Repositories and commits from Git, GitHub was used [GitHub](https://github.com/)
* Google Fonts for addiitonal font styles [google-fonts](https://fonts.google.com/)
* I used Font awesoe for my icons [font-awesome](https://fontawesome.com/v5.15/icons?d=gallery&p=2)
* Wireframes for site designs and planning I used [balsamiq](https://balsamiq.com/)
* For reducing my Image files [Compressor.io](https://compressor.io/)
* For image re-sizing I used [promo.com](https://promo.com)
* For jpeg to webp conversions I used [Online-Converter-Free](https://onlineconvertfree.com/) 
* Free images, royalty free. I used [pexels.com](https://www.pexels.com/)

# Validation
## Lighthouse -
    * Desktop average: Performance 100%, Accessibility 100%%, Best Practice 98%, SEO 100%.
    * Mobile average: Performance 94%, Accessibility 100%, Best Practice 98%, SEO 100%.
        
<details><summary>Evidence</summary>

![Image-of-lighthouse-results-desktop](/assets/images/readme-images/lighthouse-desktop1.png)

![Image-of-lighthouse-results-mobile](/assets/images/readme-images/lighthouse-mobile1.png)

 </details>


## Validator Testing

### W3C HTML

* Pages 1-4 were put through the w3c validator test, all with zero errors and warning. Please see below confirmation: 

![Image-of-w3c-validated-code](/assets/images/readme-images/html-validator.png)

### W3C CSS

* style.css document:

![Image-of-w3c-validated-code](/assets/images/readme-images/css-code.png)


# Testing 

## Manual Testing
<details><summary>Actions, Expectations and Results</summary>

Have tested everything works on my website on the following devices:

* Desktop - MacBookAir 13" 
* HP 24” Monitor
* Ipad Generation 6
* Iphone 11 
* Android Galaxy S5

### Header & Nav

Action: Visible and accessible
* Expected: Visible and accessible 
* Result: Pass.

Action: Check if hover attribute is working
* Expected: Red border surrounds the nav element in which the cursor is placed
* Result: Pass

Action: Click on the ‘My 5-A-Side page title’
* Expected: Directs to Home Page
* Result: Pass

Action: Click on ‘Home’
* Expected: Directs to Home Page
* Result: Pass

Action: Click on ‘Community’
* Expected: Directs to Community Page
* Result: Pass

Action: Click on ‘Sign Up’
* Expected: Directs to Sign Up Page
* Result: Pass

### Footer
Action: Visible and accessible
* Expected: Always at the bottom of the page
* Result: Pass

Action: Click on Facebook icon
* Expected: Directs you to facebook.com via new tab
* Result: Pass

Action: Click on Envelope icon
* Expected: Directs you to outlook.com via new tab
* Result: Pass

Action: Click on User+ icon
* Expected: Directs you to Sign Up page
* Result: Pass

### First Page - Home

Action: Enter URL of website into browser
* Expected: Taken to the Landing Page of the site
* Result: Pass

Action: Hover over ‘Sign up & create your profile’ icon		
* Expected: Increases in Size 
* Result: Pass

Action: Click on ‘Sign up & create your profile’ icon		
* Expected: Directs user to the Sign Up page
* Result: Pass

Action: Hover over ‘Join games & manage your team’ icon		
* Expected: Increases in Size
* Result: Pass

Action: Click on ‘Join games & manage your team’ icon	
* Expected: Directs user to Community Page		
* Result: Pass

Action: Hover over the feedback comment 
* Expected: Increases in size
* Result: Pass

### Second Page - Community

Action: Click ‘request to join’ button
* Expected: Directs you to Sign Up page
* Result: Pass

Action: Click ‘check location’ button
* Expected: Directs you to the Location section of the page
* Result: Pass

Action: Click ‘contact’ button
* Expected: Directs you too outlook.com via new tab
* Result: Pass

Repeated for the second game:
* Result: Pass

Action: Navigate google Maps
* Expected: Google Maps functional. Link to ‘view larger map’ directs via new tab
* Result: Pass 

### Third Page - Sign Up

Action: Click Sign up without entering any information into the required fields
* Expected: Asks to fill in ‘First Name’ field before progressing
* Result: Pass

Action: Type name in First Name field and click sign up
* Expected: Asks to fill in ‘Second Name’ before progressing
* Result: Pass

Action: Type First and Second Name into appropriate fields and click sign up 
* Expected: Asks to fill in ‘Email’ files before progressing
* Result: Pass

Action: type inappropriate email address, with @ missing and click sign up
* Expected: Asks to include an @ in the email address
* Result: Pass

Action: Fill in First Name and Email Address only and click sign up
* Expected: Asks to complete missing field
* Result: Pass

Action: Change location to Other and click sign up (with completed fields)
* Expected: Progresses to Submit Page
* Result: Pass

### Fourth Page - Submit Confirmation

Action: Click the yellow link ‘Click here to return to home page’
* Expected: Directs to the Home Page
* Result: Pass
</details>
<details> <summary>Responsiveness Tests for ux</summary>

* 1350px 
    * All sections appear correctly
* 1250px
    * Page 1 Benefit Section - Font size reduced
    * Page 2 game Section - Font size reduces
    * Page 2 Location Section - Address font size reduced
    * Pagee 3 Form section - Font size reduced
* 950px
    * Page 1 Benefit Section - UL font size reduced
    * Page 1 How Section - flex-direction:column 
    * Page 1 Quote Section - font size reduced in the quote div
    * Page 3 Form Section - location box size reduced
* 800px
    * Nav element font size reduced
    * Page 1 First Section - Height of section reduced by 200px. Heading font size reduced
    * Page 1 Benefit section - flex-direction:columm
    * Page 1 Map Section - Height increases by 90px. Smaller Image appears, font size reduced
    * Page 1 How Section - Height of the section reduced by 200px
    * Page 2 Game Section - Headers and fotn size reduced, margin left and right reduced
    * Page 3 Form Section - Height reduced to 800px, font size reduced
    * Page 4 Submit Section - Height Reduced to 700px 
* 600px
    * Page 4 Submit Section - Height reduced to 600px, font size reduced with increased padding-left
* 480px
    * Nav element font size reduced
    * Page 1 First Section - Height reduced to 310px. Smaller image replaced. Heading font size reduced, text centred.
    * Page 1 Benefit Section - Height reduced by 90px, font size reduced
    * Page 1 Map Section - Height reduced by 180px, smaller image replaced, font size reduced
    * Page 1 How Section - Height reduced to 630px, font and icon size reduced
    * Page 2 Game Section - flex-none, incresed margin by 5% 
    * page 2 Location Section - flex-direction:column, increased height to 675px
    * Page 3 Form Section - flex-direction:column 
    * Page 4 Submit Section - Height reduced to 500px, font size reduced
* 340px
    * Page 2 Game Section - Flex-none, Height reduced to 450px, line-height increased
* 280px 
    * Nav element font size reduced
    * Page 1 Benefit Section - Height increased by 90px, font size reduced
    * Page 1 Map Section - Smaller image replaced
    * Page 1 Quote Section - Height increased to 450px

* No responsiveness problems to report, all sections are visible and readable on a range of devices and screen sizes.

</details>

## Browser Testing
<details><summary>Browser List</summary>

* Google Chrome
* Microsoft Edge
* Safari (apple) 
* FireFox

</details>

## Device Testing
<details><summary>Device List</summary>

* Iphone 7
* Iphone 11
* Samsung Galaxy s5
* Ipad 6th Generation
* MacBook Air 13"
* HP Monitor 24"

</details>

## ReadMe Testing 

* Testing of the ReadMe document was done by clicking every link on this ReadMe on github.com and qualifying each corresponding link.

## Bugs and Fixes

<details><summary>Bug List</summary>
<br> 

Bug: Theres a single circle in one of my div elements as part of my 'li'. I have text-decoration:none but still shows. It shows on Dev Tools but theres nothing in my html pointing to what it is. 
* Fix: had line-style-type: none in the 'li' not 'ul'.

Bug: Font not working properly.
* Fix: Capitalise first letter of font with brackets.

Bug: Not sure how to have the active only highlight current page. It highlights home regardless
* Fix: Mentor pointed out I only had the active class specified in one of my nav elements. I had previously copied and pasted my code into the seperate new pages, which was the cause. 

Bug: Icons not aligned in my benefits list.
* Fix: Decreased size of the icons to match the others. Could have used Flexbox to do this also. 

Bug: How to alt and reference images done in css.
* Fix: Mentor, Dick, confirmed this was not neccessary when images are stored correctly in a linked css folder.

Bug: Hover Buttons on community page effect structure and repsonsiveness on smartphones and tablets
* Fix: Removed Hover buttons, not necessary here. 

Bug: Location address and Google Maps when smaller resolution looked conjested and hard to read
* Fix: Added flex-direction: column and added margin / padding to increase the look and usability.

Bug: Validator notifying me theres a problem with my font-awesome script location.
* Fix: Mentor identified that on one of my pages the script was otuside the body. 

Bug: Lighthouse performance for mobile was 85% due to the use of JPEG image files.
* Fix: I converted files to webp and then compressed them further. This increased the performance by 9%.

Bug: Was getting warnign of an incorrect aria-label one of my footer icon elements.
* Fix: I posted the warning and my code in slack. Daisy_mentor notified me that my aria-label was in my icon element, not the anchor element. This fixed the bug, and also improved my accessibility to 100% across my site (lighthouse).

### No Unfixed Bugs to report.

</details>

# Deployment
* GitHub and GitPod has been used for the creation and deployment of the site. By using Github Pages, the site can be viewed on all devices. 
    To do this I:
    1. Created a Repository on [GitHub Pages](https://github.com/) using my user profile that i set up for personal use.
    2. Utilised GitPod, accessible in my repository, to create my site using html and css. The Gitpod Button is in bright green, below the setting tab and above the repository documents etc.
    3. GitPods version control funcitonality meant I could commit and push my code as I progressed. Previous commits were always accessible should I have needed to revisit them. I did this using the gitpod terminal: 'git add .' , 'git commit -m "message"' , 'Git push'. My Commit Messages were designed to be simple and descriptive. 
    4. Returning to my repository in GitHub, I located the 'page section' in 'Settings'. Located above the green GitPod button. 
    5. Via the 'source' section, I selected 'Master Branch' from the drop down and published the link.
    6. My site was then displaying as published.
    7. I followed the link by clicking on it to check that the site was working.

* Link to my Site [jjn-my-five-aside](https://jjnod88.github.io/jjn-my-five-aside/)

## Local Deployment
The purpose of a local deployment is for other coders to use my code to deploy my website, allowing them to utilise the code and design so that they cna make changes to build their own. You can do this by: 
1. Ensure git is installed on your device
2. In Github, locate the correct repository, click the code button 'next to the gitpod button'.
3. Copy the link
4. In a ternminal, type the following code: git clone 'pasted link of the code from the repository'
5. Once loaded, change into the created directory
6. Double click index.html which will open the website in the default browser.
7. Check that the site is working, and begin to amend and edit the code.
8. Because there is a repository in github, the commands add, commit and push can be used for version control


## Credits

### Content 

* Mentor, Dick, for supporting me with bugs and recommendations.
    * Adding a link to the home page on submit page
    * Changing the flex-direction of the location & google maps section for smaller screen sizes
    * Fixed my font-awesome script bug
    * Amending the h1 element in my header so that only one h1 element per page

* Mentor, Daisy_mentor from slack, for rectifying my aria-label warning in w3c validator. Further details in my Bug and Fixes section. 

* Flexbox positioning, learned from developer.mozilla - [link](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
    * Introduced by mentor Antonija.

* Confirming the correct html and css for using buttons via developer.mozilla - [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button)

* Added opacity to my images, text, forms and button elements - [w3schools](https://www.w3schools.com/html/html_form_elements.asp) 

* Love Running project for media query refresher training 

* Stack Overflow for extra ideas around media queries - [link](https://stackoverflow.com/questions/51606127/standard-media-query-to-make-website-responsive/51606295) 

### Media 

* Image of UK - http://www.supercoloring.com/coloring-pages/united-kingdom-blank-outline-map. 
    * Author: Supercoloring. License: Creative Commons Attribution-Share Alike 4.0 License.

* Image of person signing a document at a desk via pexels.com - [link](https://www.pexels.com/)

* Adding Google Maps - a google search had bullet points that I easily followed - [link](https://www.google.com/search?q=how+to+add+google+maps+to+website+html&rlz=1C5CHFA_enGB972GB972&oq=how+to+add+google+maps+to&aqs=chrome.3.0i512l2j69i57j0i512l7.6790j0j7&sourceid=chrome&ie=UTF-8)

* For proof of my sites responsiveness across multiple devices, it was captured perfectly by the [Am-I-Responsive](http://ami.responsivedesign.is/) website. Thanks to Shellie_5p from Slack Community for highlighting this for me. 

* For my color palette identifications, I used the [coolors](https://coolors.co/) website.
