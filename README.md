# My 5-A-Side

# Contents
* [Introduction](#-introduction)
* [Value](#Value)
* [Screenshots]
* [UX]
* [Accessibility]
* [Responsiveness]
* [Features]
* [Technologies]
* [Testing]
* [Validation]
* [Deployment]
* [Credits]
* [Content]


# Introduction
Welcome to My 5-A-Side

The focus of this site is to provide a fictional platform for people to locate available football games and players in their local community.

The site is aimed at footballers and people looking to get involved in football, bringing together a social aspect with teansparent locations, captains and teams. It outlays the benefits of playing football, calculating game stats and giving users the opportunity to contact propsective teams.

I have used real world teams, players and images to give the site authenticity, and to connect with users and members.

![image-of-responsive-site-design](/assets/images/readme-images/am-i-responsive.png)


# Value
### New User / Target Audience
* Users who are both new and experienced in playing football, specficially 5, 6 and 7-aside football. 
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
    * All images have an alt attribute for those needing a site that is accessible. 
    * It is inclusive. It has social media, contact links and forms to be able to sign up. 


# Screenshots


# UX
The Site needed to be intuitive, simple, and provide an enjoyable experience for the Users. 
For UX, I kept in mind the Five pillars of good UX, and used these as foundations for my Website. 

## 1. Strategy Plane -
I have explained the startegy in detail [here](#-Value)
 
## 2. Scope Plane -
This includes the features needed to provide content, material and access for Users. you can find the detail to this [here](#-Features)

## 3. Structure Plane -
### Structure
* For the site I have used HTML for the core structure and CSS for styling -
    * HTML structuring:
        * My structure includes four pages, each with: Header & Nav > Sections with headers, divs and additional elements > Footer & Nav.
        * Whilst I followed the industry standard for a core html structure, I used Flexboxes to structure my content throughout.  
        * This proved extremely beneficial in structuring each section. I used no more than 3 divs per section using display:flex, this meant each section is positioned equally in either 100%, 50% or 33% divs. This increases the visual consistency and display of my content, and allowed my elements to be aligned.
        * I ensured I correctly linked my CSS stylesheet (checked using the background color technique) with appropriate SEO key words so my site is searchable on the internet.
        * Because of the way I structured my site, I was able to duplicate many of my html elements into new pages. This was great for time saving and consistency.
    * CSS
        * I created an asset folder that held my style.css sheet which allowed me to style many pages at once. I linked this in to the html using rel and href attributes 
        * Images were kept in the Asset folder under an inserted Images folder, this ensured there would always be an image there, without the risk of an external owner closing a website or authorisations. 
        * I used Pexels for the background and form image, this is a free image site that requires no consent. My other image for the Location section was taken by myself. 
        * Some of my pictures needed scaling. I used the free site promo.com to rescale, and compressor.io to reduce the size of my image files. 

## 4. Skeleton Plane -
### Site Layout
* The Site needed to be presented in an intuitive and simple way. One that makes it easy to use with its naviagtion and features.
    * Layout
        * It consists of a landing page, a community page, a sign up page and a submit successful page. 
        * Left to Right, the Site flows correctly. Home > Community > Sign Up.
        * Each page is divided into sections of equal size (unless it affected the look of the site, i.e the opening section for the background image). The height of each section is in mupltiples of 90px to maintain consistency throughout. 
        * Headings and Images are specific to the sites purpose.
        * Each section has been designed to sell, provide information and direct the user to the product. 
        * For my background color I used rgba(0,44,0,.1);, which allows for content to be easily visible and also minimilistic whilst the green matches the theme of a football site. I have seperated sections using the standard white background color or Images for good contrast and simplicity.
    * Navigation 
        * I have used lots of naviation in my site, to allow users to navigate the site with ease.
        * A visible header, with a position:sticky and Z-index of 999 means it is always accessible and visible. The title and three page navs link to all aspects of the site. 
            * This is the same for the Footer.
        * In my icons I have added href links to the appropriate sections and pages. An example of this is the 'how' icons on the index page. They direct to sign up and to the available game section. I have also used :hover elements to make them stand out and easier to click on. 
        * My buttons have links, and also stand out with red backgrounds. I have also used :hover elements to make them stand out and easier to click on. 
        * _blank has been used to ensure new tabs are created when a user is directed to one, to keep them active on my website
        

## 5. Surface Plane -
I used [Balsamiq](https://balsamiq.com/) for my wireframes. This gave a great indication of how the site will look once completed. 
###  Font size, color, type and styling:
* Font color has been standardised to dark green, designed to be clearly visible, consistent and following the football theme color.
* Font sizing has been duplicated where possible. This includes appropriate proportions for icons vs their text, all headers on each page the same size and font. Have used % to increase responsiveness.
* Font Type was imported from Google Fonts, I chose Roboto and Lora with a back up sans Serif. This gave headings and their text meaning and provides a foundation font should the google fonts ever be unreadable on a browser. 
* I used font styling across the site. This includes font spacing for (header) and line heights to make text easier to read - Headings, paragraphs and lists primarily.

### Images
* Images were chosen that represented the sites identity. Stored in an Assets folder so they would always be visible. 
    * Landing Page has a picture of a football pitch that gives the site meaning instantly to the user.
    * Use of real images of the football teams (Location section) gives the site meaning.

# Accessibility
* The site is accessible to Users who may have a disability that prevents them from accessing the site in certain ways.
    * The foundation of this is the site layout and semantic HTML elements.
        * The Page is layed out with a standard HTML format to improve its flow, allowing screen readers to indicate header, nav, section, heading, p, ul, form and footer elements of the site. 
        * Using these Semantic Elements in the correct order provides additional functionality for tab keys and screen readers.
    * UI Controls - Nav bar is set to Float Left so that you can use the tab to navigate it accurately. All buttons are accessible using the keyboard tab and enter functions.
    * For the form, I have used labels and linked them to inputs so that a screen reader can distinguish each field.
    * To ensure I have provided enough information for any links in my site, I have added aria-label outlinining the purpose of the link, and have used brackets if it is taking the person to a new tab.


# Responsiveness
### Structure:
* Flexbox has been used to structure my elements which is an extremely responsive way of structuring the site. With display:flex and flex:1 for example, all of my sections and divs were automatically positioned correctly, and did so when scaling the screen size up and down. This saves a lot of time and looks great!
### Units:
* Across the site I have used primarily % for sizing. This inclused in height, width, padding, margins and font-sizes etc. I implemented this from the beginning to ensure my design was adaptive across multiple screen sizes - This is extremely important in todays world as there is not one size fits all. 
### Media queries and designs 
* I have implemented different screen resolutions to ensure the site is responsive at different sizes and can be used on any device.
    * Using Google Developer, I have tested each element of the site to ensure it responds to scaling.
        * For smartphones and Tablets I adapted the media queries to use smaller images, fonts and changed structures by using Flex-Directions. 
        * I grouped my elements as much as I could to reduce the amount of changes to the layout. I started my Media Queries at max 1250px which is around the industry standard size for desktop screns and worked my way down, until I got to smartphones with a Media Query set up for Min 0px and Max 480px. 
        * Seperating my Media Queries like this really helped as I tested the site scaling. Fortunately I have two screens to work from which meant not only could I code whilst using Google Developer, I can test the Site realtime using an Apple MacBook Screen and a HP Large Desktop Monitor Screen.
* The site had thorough testing to ensure these Media queries worked and the site was responsive. Please visit [Testing](#-Testing) for further detail and 

 
# Features:
### Header & Footer
* Consistent interactive Header and Nav elements are used throughout the entire site.
    * The site has a Navigation bar accessible at all times, that blends in to the web page. It includes a link to the *Home*, *Community* and *Sign Up* pages.  
        * Navigation Bar is the same size throughout, and repsonds to responsive design in the same way.  
        * Navigation Bar is fixed with a position:fixed and a z-index: 999; ensuring it is always visible and accessible
    * A simple Footer with links to *facebook*, *Email/Contact us* and *Sign Up* pages.
        * The Footer is the same size throughout, and repsonds to responsive design in the same way.  

## Four pages -

### 1. Landing Page (Home)
* Landing Page section -
    * An image of a football will instantly tell the user the sites main focus, giving it visual context to grab their attention.
    * The image has text overlay with the Sites Name, a catchy slogan, and a location. Re-inforcing the reason the site exists and why the User is visiting.  
    * The image has an opacity value, to help blend the text and header.  

![image-of-landing-page](/assets/images/readme-images/landing-page.png)

* Benefits Section -
    * A Catchy phrase giving the User an other reason why they are visiting. 
    * Benefits displayed with appropriate Icons in Red, in a List style. 

![image-of-landing-page-benefit-section](/assets/images/readme-images/LP-benefits.png)

* Map and Key Indicator Section -
    * There is a basic Map with Manchester circled, reminding the user of the sites taregteed locations
    * Adjacent to the Map are some Key Indicators of how many live games, members and Goals there is. This was to give the User a personal feel to the site, one where if they are a member they can contribute too.

![image-of-landing-page-map-stats-section](/assets/images/readme-images/LP-map-and-stats.png)

* How Section -
    * I have created 3 large icons with a few words outlining how to use the site. 
    * the icons have a link to the corresponsing part of the site, with 'hover' styling to increase its size when a user hovers over them.

![image-of-landing-page-how-section](/assets/images/readme-images/LP-how-to.png)

* Quote Section -
    * To give context and personality, a quote from one of the members of the site has been added. This is adjacent to a clear header.
    * The quote has a white background so it stands out, it in italic, and has a 'hover' styling.

![image-of-landing-page-feedback-section](/assets/images/readme-images/LP-feedback.png)


### 2. Community Page (Second)
* Same consistent header and footer
* Avalable Games section -
    * This section has details of the available games. It is designed to be inclusive with an image of the games creator with details of the game.
    * Each game section has a border with a 3D effect to help it blend in. It has a white background to stand out, with three accessible buttons.
    * Each button has a link to the corresponsing part of the site.
        * Request to Join - Takes the user to the sign up page if they are not a member
        * Check Location - Takes the User to the Location section and its specific pitch location
        * Contact Us - Takes the User to Outlook External Website, where they could contact the Game Creator (in the absence of a member chat area)

![image-of-community-page](/assets/images/readme-images/Community-Page.png)

* Location section - 
    * Background image of the football pitches that are specific to each available game. 
        * For this example, the background is indeed of the pitch, and players, of the available games. This gives the site personality and makes it relatebale to its members and users.
    * Embedded in the abckgroudn image are two divs containing Address Details and a Google Maps link.
        * The Address details have a transparent red background, following the color scheme of the site, with large and readable text.
        * For additional site functionality, there is also a Google Maps image of the location, which can be enlarged and followed on an external tab.

![image-of-community-location](/assets/images/readme-images/CP-Locations.png)


### 3. Sign Up Page (third)
* Same consistent header and footer
* Form Section - 
    * Kept simple and to the point, there is only once section for the Sign Up page.
        * It has a formal background image of a person in a suit writing down on paper on a desk. This image was chosen, as it reflects a football manager or player signing a football contract. So is relateable.
        * It is set at the same opacity as the landing page background image. This keeps theme consistency but also allows the form to be more visible.
    * The form method will be 'GET' and it will ask for **First Name**, **Last Name**, **Email Address** and**Location** with a radio buttons of **Manchester** and **Other**.

![image-of-sign-up-page](/assets/images/readme-images/Sign-Up-Page.png)


### 4. Submit Page (additional)
* To ensure excellent user UX, when submitting the button 'sign up' when completin the form, users are taken to a seprate page that consists with the sites design, to let them know that their sign up has been successful. There is also a message to wish them luck.
* They are able to return back to the home page using either the 'Home' Button on the Nav Bar.

![image-of-submit-page](/assets/images/readme-images/Submit-Page.png)


# Technologies
* CSS
* HTML5
### Programmes
* Git - Version Control (add, commit, push)
* Github - Store Projects, Repositories and commits from Git
* Google Fonts - For addiitonal font styles
* Font Awesome - Use of Icons
* Balsamiq - Wireframes for site designs and planning
* Promo.com for rescaling images
* Compressor.io to reduce the size of the file image size, improving the sites loading speeds


# Testing
### Lighthouse -
    * Desktop average: Performance 100%, Accessibility 96%, Best Practice 98%, SEO 100%.
    * Mobile average: Performance 94%, Accessibility 96%, Best Practice 98%, SEO 100%.

![Image-of-lighthouse-results-desktop](/assets/images/readme-images/lighthouse-desktop.png)
![Image-of-lighthouse-results-mobile](/assets/images/readme-images/lighthouse-mobile.png)



### Validator Testing
#### W3C HTML

    * Page 1 (Index) 

![Image-of-w3c-validated-code](/assets/images/readme-images/index-html.png)

    * Page 2 (Community)

![Image-of-w3c-validated-code](/assets/images/readme-images/community-html.png)

    * Page 3 (Form)

![Image-of-w3c-validated-code](/assets/images/readme-images/form-html.png)

    * Page 4 (Submit Page)

![Image-of-w3c-validated-code](/assets/images/readme-images/index-html.png)

#### W3C CSS

    * style.css document

![Image-of-w3c-validated-code](/assets/images/readme-images/css-code.png)

### Site Testing
Please follow this [link](../tworeadme.md)


### Browser Testing
* Microsoft Edge
* Safari (apple) 
* FireFox

### Device Testing
* Iphone 7
* Iphone 11
* Samsung Galaxy s5
* Ipad 6th Generation
* MacBook Air 13"
* HP Monitor 24"


### Bugs and Fixes
Bug: Theres a single circle in one of my div elements as part of my 'li'. I have text-decoration:none but still shows. It shows on Dev Tools but theres nothing in my html pointing to what it is. 
Fix: had line-style-type: non in the 'li' not 'ul.

Bug: Font not working properly.
Fix: Capitalise first letter of font with brackets.

Bug: Cant get my button to move in 'upcoming games'. I can style but not move it. 
Fix: none

Bug: Not sure how to have the active only highlight current page. It highlights home regardless
Fix: None 

Bug: Icons not aligned.
Fix: Decreased size of the icons to match the others. Could have used Flexbox to do this also. 

Bug: How to alt and reference images done in css
Fix: Mentor, Dick, confirmed this was not neccessary when images are stored correctly in a linked css folder.

Bug: Hover Buttons on community page effect structure and repsonsiveness on smartphones and tablets
Fix: Removed Hover buttons, not necessary here. 

Bug: Location address and Google Maps when smaller resolution looked conjested and hard to read
Fix: Added flex-direction: column and added margin / padding to increase the look and usability.

# Deployment
* GitHub and GitPod has been used for the creation and deployment of the site. By using Github Pages, the site can be viewed on all devices. 
    To do this I:
    1. Created a Repository on [GitHub Pages](https://github.com/) using my user profile.
    2. Utilised GitPod, accessible in my repository, to create my site using html and css.
    3. GitPods version control funcitonality meant I could commit and push my code as I progresses. Previouses commits were always accessible should I have needed to revisit them. 
    4. Returning to my repository in GitHub, I located the 'page section' in Settings
    5. I then changed the source from 'none' to 'Master Branch' and published the link.
    6. I checked this was working by following the link. 
* < Insert Link to the Page >


## Credits
Flexbox positioning, learned from https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox introduced by my mentor, Antonija.

Confirming button html and css https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button

w3schools - Added opacity to my images
https://www.w3schools.com/html/html_form_elements.asp for Form > Select element

Adding Google Maps - a google search had bullet points that I easily followed

Love Running project for media query refresher training. 

Stack Overflow for the correct media min max for images.

promo.com for picture re-sizing

Image of UK - http://www.supercoloring.com/coloring-pages/united-kingdom-blank-outline-map. Author: Supercoloring. License: Creative Commons Attribution-Share Alike 4.0 License.

## Content


## Media