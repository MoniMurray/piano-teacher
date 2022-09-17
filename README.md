# PIANO TEACHER

This is the website of a fictional Piano Teacher offering tuition in piano in Co. Kildare, Ireland.

A User will be able to see at a glance, on the Home page, the Piano Teacher's credentials, that lessons can be provided either in-person or online, and that piano students of all ages and experience levels are welcome to take lessons.

![](/assets/images/README-screenshots/amiresponsive-screenshots.png)

## User Experience

With the neutral colour palette, text size and colour, and images chosen to support the theme of the website, a user's experience on the website will be positive.

### User Stories

- A user will see at a brief glance the purpose of the website.
- A user can navigate smoothly and intuitively from page to page through the website.
- A user can find easily information about the Piano Teacher and the lessons available.
- A user can choose to get in touch with the piano teacher by inputting some basic information.

## Features

- Hamburger menu opening drop-down navigation menu; 
- Interactive Footer containing external links; 
- Embedded YouTube video of sample RIAM Preliminary Grade piece for 2022;
- Sign-up Form requiring user input; and
- Embedded Google map.

### Website Logo and Navigation menu

Featured on all three pages are the Website logo and hamburger-styled drop-down navigation menu.   

The navigation menu contains links to the Home page, Lessons page and Get in Touch page, and is identical in each page to allow for intuitive navigation.

![](/assets/images/README-screenshots/hamburger-closed.png)

This navigation menu is deployed on clicking the hamburger three-lines.  

![](/assets/images/README-screenshots/Hamburger-open.png)

The interactive navigation menu will allow the user to easily navigate from page to page across all devices without having to revert to the previous page via the browser ‘back’ button.
An underline will appear on the drop-down menu under the name of the website page currently being viewed by the user.
Hovering over a page name in the navigation menu will cause that page name to be underlined temporarily.

### Interactive Footer

The footer section includes links to the relevant social media sites for the fictional Piano Teacher. Each of the links will open to a new browser tab to allow easy navigation for the user.

![](/assets/images/README-screenshots/footer-screenshot.png)

The footer is valuable to the user as it encourages them to keep connected to the fictional Piano Teacher via social media.  The footer also includes an external link to the Royal Irish Academy of Music from where they can purchase Grade related sheet music and register for Grade exams. 

The footer section is common across the three pages of the website.

Each of the social media link icons were created using font awesome.  Hovering over any of the footer links will cause that link to highlighted.

### Embedded video

A user-controlled YouTube video is embedded on the Lessons page.

![](/assets/images/README-screenshots/embedded-video.png)

### Sign-up Form

The user is required to enter their name and email address.  Placeholder text prompts the user where to input their details in both of these input fields.

![](/assets/images/README-screenshots/Sign-up-form.bmp)

The user is required to:

- indicate, by ticking a checkbox, whether they have previous experience taking piano lessons;
- select a radio button to specify if they would like to take this lesson In Person or Online; and, 
- use a radio button selection to specify whether the user is an Adult signing up for lessons for themselves, or whether the user is a Parent signing up for lessons for their child.  

The radio button inputs are *required*, and a user will be prompted to complete these sections if left blank on clicking 'Book Your Lesson'.

### Google map

An embedded Google map of the fictional Piano Teacher's lesson location is on the Signup page.

![](/assets/images/README-screenshots/embedded-map.png)

## Home page 

The landing page, or Home Page, includes:

- the website logo;
- an image with text overlay to allow the user to see that this is a website introducing and offering the professional service of an experienced Piano teacher; and,
- a biography section which allows the user see the biography of the Piano teacher overlaid over three further images.

The images selected compliment and reinforce the purpose of the site.

![](/assets/images/README-screenshots/Home-page.png)

The three biography section background images appear in a row on large screen view, and appear in a column in mid-and small screen view.

![](/assets/images/README-screenshots/biography-column-view.png)

The html for the Home page is contained in index.html, with CSS code contained in the style.css file.

## Lessons page

The Lessons page provides the user with information about the lessons provided by the Piano Teacher and what they broadly cover.

![](/assets/images/README-screenshots/Lessons-page.png)

This section is valuable to the user as they will be able to easily identify both the lessons provided for Adults and the lessons provided for Children, the duration of those lessons and what they cover.

The images on the Lessons page appear in a row on a large screen view, and appear in a column in mid- and small screen view.

![](/assets/images/README-screenshots/lessons-column-view.png)

The html for this page is contained in lessons.html, with CSS code contained in the style.css file.

## Get in Touch page

This page allows the user to submit a sign-up Form to book a lesson with the fictional Piano Teacher.  

![](/assets/images/README-screenshots/Get-in-Touch-page.png)

The user will submit their information via the 'Book Your Lesson' submit button.  The submit button also contains a hover feature which causes it to change colour on mouse hovering over it.

The html for this page is contained in get-in-touch.html, with CSS code contained in the style.css file.

## Images

Images for the Project can be viewed in the Images sub-folder of the Assets folder [here](assets/images/).

## Future feature ideas

If this website were to be used by a real-world Piano teacher I would include payment links, ie. via Paypal or Revolut, and enable the user to block-book lessons.


## Testing

During coding and while ensuring the page was responsive, I had some issues with margin size interfering with different element appearances on the page.  I used DevTools to source and fix the problem as it arose.  I also used Tutor Support when I needed to.

Including a Hamburger drop-down navigation menu took some additional upskilling, and styling the hamburger and it's drop-down menu took time to perfect.  I initially used another of my repositories to work on coding the navigation bar, following instructions from codepen.io, before bringing the code into my Project to fine-tune within the pages of my site.

I have tested the site and all links contained within the site on PC, on Chrome, Edge and Firefox, on ipad, and on Samsumg Galaxy and iPhone 13 mobile phones.  Testing initially showed no bugs, but the iphone 13 screen size displayed the Website logo split with the word 'Teacher' dropping below the hero image.  I expanded the media query originally set to max-width 375px up to 385px to fix this issue. 

I have tested the functionality of the Form, ensuring that where 'required' information or input has not been provided by the user, that the user is prompted to include that information before they can submit the form.  The form's submission goes to the [CI](https://formdump.codeinstitute.net/), has been tested, and is fully functional. 

Each of the site's pages work well and are responsive on different sized devices, from small-screen at max-width 320px to mid-screen at max-width 768px to larger laptop size and pc.  

## Validator Testing

### HTML

First pass through W3C validator returned an error in the meta element where the 'name' and 'content' attributes were incorrectly assigned. Fixed.

Following the inclusion of the Hamburger menu, the W3C validator returned an error relating to the list elements containing the navigation anchor elements.  Fixed by adding an unordered list element as a parent to these list elements.

No errors were subsequently returned when passing through the official W3C HTML validator    
![W3C Validation Screenshot](/assets/images/README-screenshots/w3c-validator-check.png)

### CSS

First pass through Jigsaw validator returned value errors (fixed) and parse errors.

These were margin errors, and one colour value to a box-shadow attribute where no colour value was required.  Once these errors were addressed, my site [passed](http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fmonimurray.github.io%2Fpiano-teacher%2F&usermedium=all&vextwarning=&warning=1).

### Lighthouse

Lighthouse score is as follows:

![](/assets/images/README-screenshots/lighthouse-score.png)

## Deployment

The site was deployed to GitHub pages. 

The steps to deploy are as follows:

In the GitHub repository, navigate to the Settings tab;
From the Code and Automation area on the left side of the page, select Pages;
From the source section drop-down menu, select the Master Branch, select Save;
The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
Once again navigate to the Settings tab, and then to Pages where the live link can now be found.

The following is a live link to the site - https://monimurray.github.io/piano-teacher/

## Credits

My mentor provided invaluable help in suggesting better ways to code sections of my site for functionality and responsiveness, for example Flexbox and Hamburger Menu.  My mentor also encouraged me to make better use of DevTools to trial lines of CSS before including what worked in Gitpod.

Colleagues on Slack channels answered questions and provided encouragment and feedback, and asked questions themselves that helped point me in the right direction when an area of code, or point of procedure, was proving difficult.

Tutor support helped me by pointing out the different screen break-points and also by assisting me to locate the source of a bug in my Header whereby the logo was not shrinking correctly at small screen size.  They provided me further reading material and reference material which helped me get to the finish line.

[W3Schools](https://www.w3schools.com) appeared repeatedly in my Google searches and was a valuable resource throughout this Project.

### Media & Content

Most images credited to [Pexels](http://www.pexels.com).  

Landing page hero image credited to [Unsplash](https://unsplash.com/s/photos/piano).

How to create a fixed Navigation bar [W3Schools](https://www.w3schools.com/howto/howto_css_fixed_menu.asp). Amended to suit my Piano Teacher design.

Credit to [RIAM](https://www.riam.ie) for the Preliminary Grade music recording embedded in the Lessons page, and to [W3Schools](https://www.w3schools.com/html/html_youtube.asp) for the lesson on how to embed video and audio using CSS.

Credit to [Google-Maps](https://www.google.com/maps/@53.1593669,-6.8112036,17z) for the embedded iframe link to the map contained on Get in Touch page.

#### Responsiveness

Responsive placement of text over an image googled and learned from [W3Schools](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_hero_image).

Media screen responsivness and how to style sections for smaller device sizes taken and adapted from the Love Running Walkthrough project.

Responsive Hamburger menu using CSS credited to [www.codepen.io](https://codepen.io/alvarotrigo/pen/wvrzPWL) and adapted to suit the style of this Project's website.

#### Form Creation

The Form on the Get in Touch page was created by following the steps in Challenges 1 and 2 of Love Running Walkthrough project, with adjustments to suit the Piano Teacher form as I designed.

## Wireframe

The Wireframe for this Project was created using Balsamiq. ![here](/assets/images/README-screenshots/balsamiq-wireframe.png)
