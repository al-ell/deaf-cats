# Deaf Cats

![Welcome to Deaf Cats](/documentation/multi-device-mockup.png) 


Deaf Cats was created as my first milestone project for the Code Institutes Level 5 Diploma in Web Application Development.

Link to deployed site: [Deaf Cats](https://al-ell.github.io/deaf-cats)

![GitHub last commit](https://github.com/al-ell/al-ell.github.io/commits/main)

## CONTENTS

* [User Experience](#user-experience)
  * [Project Goals](#project-goals)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [Elements Fount on Each Page](#elements-found-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Databases Used](#databases-used)
  * [Frameworks Used](#frameworks-used)
  * [Libraries & Packages Used](#libraries--packages-used)
  * [Programs Used](#programs-used)
    * [Google Books API](#google-books-api)
    * [Flask Blueprints](#flask-blueprints)
    * [Flask Migrate](#flask-migrate)
    * [Error Handling](#error-handling)
    * [Defensive Programming](#defensive-programming)
    * [Database Migration to ElephantSQL](#database-migration-to-elephantsql)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
  
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)

- - -

## User Experience

### Project Goals

To create a website for fan's of the jazz bans "Deaf Cats" to see when and where they are playing live, look at pictures from past events
and to find out more about their history. The project will have media and social links for fans to find their music and content online on other platforms. 

### User Stories

#### __Target Audience__

The target audience for the website are people who like the bands music and want to find them on social media platforms, spotify and see them play live. It is also for people who would like to contact the band to book them for gigs and events. 

#### __First Time Visitor Goals__

As a first time user of the site I want to be able to:

* Understand the purpose of the site and how to navigate to other pages.
* Find where I can play their music online.
* Find out more about the band and see pictures of them.
* See when and where they are playing live.
* Contact the the band or book them to play at an event.

#### __Returning Visitor Goals__

As a returning registered user of the site I want to be able to:

* Find out about new music releases and where it can be played online.
* See when and where they are playing live.
* Book the band to play at an event.


#### __Admin User__

As an administrator for the site I want to be able to:

* Provide a way for the band can be contacted.
* Create a working form that sends messages to an email address.
* Create a ticket booking sytem (future releases).

- - -

## Design

### Colour Scheme

I began using the pallete below as inspiration for the colour scheme and then adapted the colours to increase accessability:

![Colour Scheme for Deaf Cats](/documentation/color-scheme-inspo.png)

[source website](https://www.canva.com/learn/website-color-schemes/)

I then experimented with different tones and shades of these colours using WebAIM's color contrast checker:
![Contrast checker][https://webaim.org/resources/contrastchecker/]


The the contrast ratio for the chosen colors for text and header & footer background elements passes the contrast checker for all colors. 

### Typography

I used Google Fonts to import the following fonts for use in the site:

##### Logo 
![Monoton](https://fonts.google.com/specimen/Monoton?query=monoton) 
I chose this as it has smooth curves and makes a unique logo style. 
![sample](/documentation/fonts/monotonsample.png)

##### Headings 
![Ubuntu](https://fonts.google.com/specimen/Ubuntu?preview.text=Deaf%20Cats&preview.text_type=custom&query=ubun) 
The font is easy to read, has good speacing between letters and continues the curves of the logo. 
![sample](/documentation/fonts/ubuntusample.png)

##### Paragraphs 
![Cabin Condensed](https://fonts.google.com/specimen/Cabin+Condensed?preview.text=Deaf%20Cats&preview.text_type=custom&query=cabin+con)
I felt this complimented the headings font well and is a sans-serif which improves legability. 
![sample](/documentation/fonts/cabincondensedsample.png)

##### Icons 
[Font Awesome](https://fontawesome.com/icons)
Icons are a good way to add accessability features to a website 


### Imagery

Favicon generated using [Favicon generator](https://www.favicon-generator.org/) ![Favicon](/assets/images/dc-favicon.ico)

As the site is for fans of the band I have chosen imsges of a group of people from a stockfile website. I have complimented these with musical themed images.Please view the media section for more information on where each image was sourced.


### Wireframes

Wireframes were created for mobile and desktop using Balsamiq.

#### __Home Page__

![Home Page](/documentation/wireframes/wireframehomepage.png)

#### __Contact Modal__

![]](/documentation/wireframes/wireframecontactus.png)

#### __Gallery Page__

![Login Page](/documentation/wireframes/wireframegallery.png)

#### __History Page__

![Profile Page](/documentation/wireframes/wireframehistory.png)

#### __Live Page__

![Live Page](/documentation/wireframes/wireframelivedates.png)

 -----


## Features

The website is comprised of 4 pages and a modal which are extended from a base template.

* Home page
* Gallery page
* History page
* Live page

* Contact form modal


### Elements found on each page


* Navbar - The Navbar is displayed on all pages of the website, it allows users to navigate the site with ease. The navbar is comprised of a logo, and links to navigate within the site and a search bar. It has a text-colour indicator to show the current page.

  __Navbar__
  
* Bootstrap navbar styled to have right sided margin.
  
  ![Navbar](/documentation/manual-testing/homepage-nav.png)

  __Nav-button__

* Flex wrap reverse used to get nav button to toggle and logo to sit below for smaller screen resolutions. 

    ![Nav-button-toggler](/documentation/manual-testing/mobile-nav-toggler.png)


  __Footer__

* Footer containing the modal button and external social media icons links is displayed on all pages of the website. d-none used to hide watch link for smaller devices.
  ![Footer](/documentation/manual-testing/homepage-footer.png)

- - -

### Home Page

![Home Page](/documentation/manual-testing/desktop-index.png)

![Home Page](/documentation/manual-testing/mobile-index.png)

![Home Page](/documentation/manual-testing/tablet-index.png)

### Gallery Page

![Gallery Page](/documentation/manual-testing/desktop-gallery.png)

### History Page

![History Page](/documentation/manual-testing/desktop-history.png)

### Live Page

![Live Page](/documentation/manual-testing/desktop-live.png)

### Contact Form Modal

![Contact Form Modal](/documentation/manual-testing/desktop-modal.png)

- - -

### Future Implementations

In future implementations I would like to:

* Create a ticket booking system/allow users to boy tickets on the website.
* Create an online shop selling merchandise.
* Add a sign up link for a mailing list.
* Add a blog documenting tour journey.
* Add a live instagram or twitter feed.
* Add an audio player with user controls to the gallery page.

### Accessibility

I have been mindful during coding to ensure that the website is as accessible friendly as possible. This has been achieved by:

* Using semantic HTML.
* Using descriptive alt attributes and titles for images and video on the site.
* Providing information for screen readers where there are icons used and no text.
* Adding "current" to navigation for screen reader to inform of page being accessed.
* Ensuring that there is a sufficient colour contrast throughout the site.

- - -

## Technologies Used

### Languages Used

HTML, CSS.

### Databases Used

[css flexbox guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)


### Frameworks Used

[Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) - V 4.5 Css framework.

### Libraries & Packages Used

[W3 Schools html](https://www.w3schools.com/html/default.asp)
[W3 Schools css](https://www.w3schools.com/css/default.asp)


### Programs Used

[Codeanywhere] - Online code editor.

[Balsamiq](https://balsamiq.com/) - Used to create wireframes.

[Github](https://github.com/) - To save and store the files for the website.

[Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.

[Font Awesome](https://fontawesome.com/)  - For the icons on the website.

[Google Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) - To troubleshoot and test features, solve issues with responsiveness and styling.

[Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

- - - 

## Deployment & Local Development

### Deployment

The project was developed using Codeanywhere cloud IDE and pushed to GitHub using the inbuilt command line. To deploy to GitHub Pages from the [Github repository](https://github.com/al-ell/al-ell.github.io/tree/main) follow these steps:

    1. Log in to [GitHub]()
    2. Go to the [repository page](https://github.com/al-ell/al-ell.github.io/tree/main)
    3. Change the name of the respository to "username.github.io" : al-ell.github.io
    4. From the menu above the repository menu select __settings__
    5. On the left select __pages__ 
    6. Under __source__ select __deploy from a branch__
    7. Go to "username.github.io" : al-ell.github.io



### Local Development

#### How to Fork

    1. On GitHub.com, navigate to the octocat/Spoon-Knife repository
    2. In the top-right corner of the page, click __Fork__
    3. Under "Owner," select the dropdown menu and click an owner for the forked repository
    4. By default, forks are named the same as their upstream repositories. Optionally, to further distinguish your fork, in the "Repository name" field, type a name
    5. Optionally, in the "Description" field, type a description of your fork
    6. Optionally, select __Copy the DEFAULT branch only__
    7. Click __Create fork__   

#### How to Clone

    1. On GitHub.com, navigate to the main page of the repository
    2. Above the list of files, click __<> Code__
    3. Copy the URL for the repository
        * To clone the repository using HTTPS, under "HTTPS", click __clipboard icon__
        * To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click SSH, then click __clipboard icon__
        * To clone a repository using GitHub CLI, click GitHub CLI, then click __copy icon__
    4. Open Terminal, change the current working directory to the location where you want the cloned directory
    5. Type 'git clone', and then paste the URL copied earlier
    6. Press __Enter__ to create your local clone

- - -

## Testing

Please see [TESTING.md](TESTING.md) for all testing performed
- - -

## Credits

### Code Used


All instances of Tutor support and fixes found online are documented as comments in the code.

##### Gallery Page

[Responsive Gallery Tutorial](https://blog.logrocket.com/responsive-image-gallery-css-flexbox/)
[Responsive Gallery Source Code](https://codesandbox.io/s/delicate-wave-sts6l7?file=/index.html:313-2227)
To create the gallery page I followed the above tutorial to make the responsive gallery page. Doing this helped me to learn more about how flexbox works. After this I went to make the history page.

##### History Page

[Youtube Flexbox Tutorial](https://www.youtube.com/watch?v=Y8zMYaD1bz0)
I used the tutorial playlist above to make a flexbox grid layout that becomes a stack for a smaller resolution.

##### Live Page

[Youtube timeline tutorial](https://www.youtube.com/watch?v=TcYSRI1JFQE&t=6s)
I used the timeline and knowlege gained during the Resume project to make the timeline for the tour dates. 


##### Bootstrap Components  

* Bootstrap Grid and flexbox used across all pages

* Alert
* Buttons
* Navbar
* Modal
* Form

### Content

Content for this project was written by Alice Elliott.

### Media

* Homepage Image for larger screen resolutions [street-homeimage](https://www.pexels.com/photo/two-men-and-woman-sitting-next-to-each-other-2479312/)

* Homepage Image for smaller screen resolutions/Image for gallery [street2](https://www.pexels.com/photo/man-playing-guitar-beside-woman-and-man-listening-to-him-2479320/)

* Image for gallery [street3](https://www.pexels.com/photo/man-playing-guitar-on-street-2479323/)

* Image for gallery [trumpet](https://www.pexels.com/photo/people-performing-on-stage-442540/)

* Image for gallery [guitar](https://www.pexels.com/photo/two-men-and-woman-sitting-next-to-each-other-2479312/)

* Image for gallery [outdoor-concert](https://www.pexels.com/photo/man-playing-a-saxophone-16803242/)

* Image for gallery [outdoor-concert2](https://www.pexels.com/photo/    man-and-woman-dancing-while-man-in-black-clothes-playing-the-saxophone-on-the-roof-top-7502577/)

* Image for gallery [drums-studio](https://www.pexels.com/photo/man-in-black-jacket-playing-drum-5650907/)

* Image for gallery [garden-stage](https://www.pexels.com/photo/a-band-playing-music-in-a-park-in-summer-16803238/)

* Image for gallery [closeup-guitar](https://www.pexels.com/photo/close-up-of-a-man-playing-an-electric-guitar-8133318/)

* Image for history [history1](https://www.pexels.com/search/stage%20and%20tables/)

* Image for history [history2](https://www.pexels.com/photo/16844655/)

* Image for history [band-practice](https://www.pexels.com/photo/16844655/)

* Image for history [festival-stage](https://www.pexels.com/search/festival%20stage/)

* Video for history [youtube-video](https://youtu.be/wPRwhu7WKp4)

* Video for live [youtube-video](https://www.youtube.com/watch?v=St7G1F4mu_4&t=3s)

* Device mark up creator [markup maker](https://techsini.com/multi-mockup/index.php)