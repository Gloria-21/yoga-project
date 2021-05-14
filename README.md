# Yoga Project (Milestone 1 User-Centric Frontend Development - Code Institute)

![Alt text](/doc/validator/responsive-mockup.png)

[Deployed website](https://gloria-21.github.io/yoga-project/index.html)

## Purpose of the project

The purpose of this project is to create a yoga studio in Cambridgeshire that offers Hatta, Vinyasa yoga, and meditation. Providing that one of the teachers is a midwife they also offer prenatal and baby yoga. The studio impart possibilities for both face to face and online courses classes, making this way more accessible the practice of yoga

## User stories
The end-user of this project is mainly the female population as the usual majority of attendance on yoga classes is women. Also, we have to bear in mind the prenatal and baby yoga classes are going to bring mums to be and mums to the classes, so it is expected that the scope of women attending the studio will be in the range of 20 to 50 years old.

The end-user wants information about the services that Yoga Project has to offer 

* The user wants to know what time the classes are
* Which type of yoga can she enjoys
* Which kind of education the teachers have
* How expensive the services are going to be
* Have more freedom with the on-demand classes
* Have a way of communicating with Yoga project in case there is any question
## Features

* **Landing page:**
It has a calming and warm welcome feeling with a jumbotron and cards as visual references that catch the attention
The cards, navbar and Contact Us button on the footer helps to navigate to other pages very easily

* **Schedule page:**
It is divided into two sections, the teachers' bio, and the schedule table. The use of alternate colors and the pictures of teaches helps to create a contrast amongst both

* **On-demand Classes:**
It is divided into three sections made with pictures that show the different classes online offered. They have buttons to purchase them and that activate a modal to sign up. When that button is clicked it leads to the Success page

* **Contact us:**
This page wasn't planned on the original wireframe, it was created as was going along with the project and it becomes clear it was necessary to have it. It follows the same structure of Navbar and footer as well as the same chromatic scheme, but present a form as the main element of the body as well as a button that leads to the Sucess page

* **Success page**
This page wasn't included in the original plan either. It has the general structure of Navbar and footer being the main body a jumbotron with a background image and a message and a button to go to the Home page

* **Navbar:**
The navbar has links to all the pages and all pages have it, so in this way the navigation is smooth. Also on the mobile version, it can be found on the top right corner as a burger button that collapses, giving a better UX experience

* **Footer:**
Each page has on the footer a Contact Us button that links to the Contact us page, also has links to social media

## Future Features

In the future, I would like to add another path for clients that already have an account and would like to sign up. Also, I would like to implement the payment system on the website and add some user reviews.
## Design
* **Typography**

    I used google fonts for my typography. I have chosen fonts Viga for the headers and Sarabun for the rest of the page
    
* **Color scheme**

    I have used colorSpace to generate my colour scheme. The Natural Palette was the final choice and that includes #DF7D6D, #FFF6F3, #BB8378, #EDE9D0 as main colours that run all the way through the website giving warmth and continuity to the theme.

* **Images**

    All the images on the website have been taken from [Pexels](https://www.pexels.com/)
## Wireframe

The wireframes that can be found below have been created using Balsamiq during the Scope plane part of the design and planning process of this project.


* [Landing page Mobile Wireframe](https://share.balsamiq.com/g/u5ix7GDWbSYkA11w6SGrx5.png)
* [Schedule page Mobile Wireframe](https://share.balsamiq.com/g/6hUk3HXucuYDQDASriEy9M.png)
* [On-demand courses page Mobile Wireframe](https://share.balsamiq.com/g/qjkRjP8esH6tNEP5gcLped.png)

* [Landing page Desktop Wireframe](https://share.balsamiq.com/g/er1s3g3voeHPLhMuVWUM4h.png)
* [Schedule page Desktop Wireframe](https://share.balsamiq.com/g/hD3Gddt7uv5dPUXULouA3j.png)
* [On-demand courses page Desktop Wireframe](https://share.balsamiq.com/g/qgaUxBLqi71B4inU84zbDo.png)

## Technologies Used 

 As it follows below
### Languages used
* [HTML5](https://en.wikipedia.org/wiki/HTML5) I have used HTML5 to design the structure  and the content of the website 

* [CSS3](https://en.wikipedia.org/wiki/CSS) I have used CSS3 to style the apearence of the website
### Frameworks, Libraries & Programs Used

1. [Bootsrap 4.4.1](https://getbootstrap.com/docs/4.4/getting-started/introduction/)

    I have used Bootstrap to help with the responsiveness of the website as well as the styling

2. [Google Font](https://fonts.google.com/)

    I have used Google font to import "Josefine Slab" into my style.css file, which is being used on all pages throughout the project

3. [FontAwesome](https://fontawesome.com/)

    Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes

 4. [Balsamiq](https://balsamiq.com/)

    I used Balsamiq to create the wireframing during the design process

5. [Git](https://git-scm.com/)

    Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub

6. [Github](https://github.com/Gloria-21/yoga-project)

    I used GitHub to store the project's code after being pushed from Gitpod

7. [Am I responsive](http://ami.responsivedesign.is/)

    I used Am I responsive to create the mockup at the beginning of the README.md document



## Testing

I have done the testing for my website using the dev tools on google chrome. I have been testing regularly checking that the results were the expected on different sizes, from mobile devices to desktop and tablet, making sure the website was responsive in all of them.
I used this tool as a main source to implement my code, trying the functionality and styling effects there first and adding them to my code afterward.

At a later stage, when the site was deployed, the website was tested by family and friends who looked on different devices and gave feedback on responsitivity and user experience.



### Validator testing
To check the validity of the codes I have used [W3C Markup Validation](https://validator.w3.org/) and [W3C CSS Validation](https://jigsaw.w3.org/css-validator/)

All the pages of the project passed the validator with 0 errors [Home](/doc/validator/index-html-validator.png) [Schedule](/doc/validator/schedule-html-validator.png) [On-demand](/doc/validator/online-courses-html-validator.png) [Contact-us](/doc/validator/contact-us-html-validator.png) 

Also the CSS page passed the validation with 0 erros [CSS](/assets/doc/validator/css-validator.png) 

### Performance

To check the website performance level as well as the speed I used [Google lighthouse](https://developers.google.com/web/tools/lighthouse)
![Atl text](/doc/validator/lighthouse.png)


### Test user stories

_These stories have links to screenshots to the desktop version and all different sizes of mobiles on the dev tool_

1. As a first-time visitor and potential client to the website I want to easily understand the services offered and if they suit my necessities.
    * Upon entering the website, the user will be welcomed with a warm, calm ,and easy navigation. 

      [Home-Desktop](/doc/screenshots/index-img.png) [Home-mobile](/doc/screenshots/index-mobile.png)

    * The user will find the services offered signed-posted on the cards as well as the navbar. 

2. The user wants to know what time the classes are
    * The user will click either the card inviting to check the schedule or on the tab schedule on the navbar. 
    * Once on the Schedule page the user will need to scroll down to find the schedule table 

      [Schedule-Desktop](/doc/screenshots/schedule-img.png) [Schedule-mobile](/doc/screenshots/schedule-mobile.png)

3. Which type of yoga can she enjoys
    * The user has to follow the card inviting meeting the team and schedule, once there, on the Schedule page the user can check the types of yoga on offer.

4. Which kind of education the teachers have
    * The user has to follow the card inviting meeting the team. Once on the Schedule page, the first section is dedicated to the teachers and their education.

5. How expensive the services are going to be
    * The user has to follow either the schedule card/navbar to the Schedule page and scrolling down, passing the table with the schedule itself, the user will find a section with the prices.
    * Alternatively, if the user rather has online classes has to follow the card to On-demand and once on the On-demand page will be able to see prices for the different courses. Also, the user will be able to purchase the course if this is the preferred option. 

      [On-demand-Desktop](/doc/screenshots/ondemand-img.png) [On-demand-mobile](/doc/screenshots/ondemand-mobile.png)

6. Have more freedom with the on-demand classes
    * As we have explained in the previous point the user will go to the On-demand page and will be able to choose and purchase from the different options shown there. 
    * The user will click the purchase button and a modal will pop up offering to create an account with Yoga project. 

      [Modal-Desktop](/doc/screenshots/modal-img.png) [Modal-mobile](/doc/screenshots/Modal-mobile.png)

    * Once that is done the user will click the Create Account button the user will be lead to the Success page where a message will the user know that the account has been created successfully. 
    * Also the user will find a button to go to the home page.

      [Success-Desktop](/doc/screenshots/success-img.png) [Success-mobile](/doc/screenshots/Success-mobile.png)

7. Have a way of communicating with Yoga project in case there is any question
    * The user will find two different ways to go to the Contact us page. One is situated on the navbar with the other pages and also on the footer of each page the user will find a Contact us button. 
    * Once on the Contact us page the user will find a form with a text area to write a comment.

      [Contact-Desktop](/doc/screenshots/contact-img.png)

    * At the very end of the form, the user will find a Submit button that will lead to the Success page
    * Also on the footer of each page the user will find links to the Yoga project social media.

### Fixed Bugs

This has been my first ever project coding on my own. It has been challenging to say the least and a true learning curve as I had to use the knowledge learned in the course as well as introducing the new functionalities found on Boostrap and CSS

* My Navbar has been problematic from the beginning as I used navbar-light and bg-light and when I tried to apply my styling to the CSS sheet I was not able to override Bootstrap styling. Looking for an answer I found !important, which worked perfectly until I was informed that is considered bad practice. I decided to delete the two Bootstrap classes that there were being problematic and once that was done all the styling on CSS started to work. That has shown me the importance of understanding the different classes that Bootstrap has on offer.

* I have problems also with the sizes of the images. First of all, I made a mistake on my HTML structure as I missed the first part of the link in my src class. Also looking at CCS-tricks I found a way to use it as a background, that wasn't my initial thought. That structure didn't work on my design as it was too cluttered but made me think of a smaller image and then write the welcome message on it.
To do so I created the jumbotron class, there were few issues with the image not matching the size of the jumbotron that were sorted after consulting [Stackoverflow webpage](https://stackoverflow.com/questions/31147543/how-to-fit-100-of-an-image-to-a-jumbotron). I realized that container instead of container-fluid would suit the project better for the result I had planned. Also, I had to do some adjustment on the margins to get the design to be responsive

* When I added the cards for the schedules and the online courses to my features they showed one underneath the other. I reviewed the grid for the cards and I managed to get a responsive side-by-side result on my desktop/tablet layout following the [boostrap cheat-sheet](https://hackerthemes.com/bootstrap-cheatsheet/). After adding the Jumbotron class, I have encountered some issues as the cards weren't being responsive anymore, and the footer out of place as well. I targeted the margin-left to align the site and make it responsive, after that it worked correctly.

* The table created for the schedule.html wasn't responsive on mobile or tablet as the footer was not covering the same area as the table. I added ```html <div style="overflow-x:auto;">``` as seen on [w3school webpage](https://www.w3schools.com/howto/howto_css_table_responsive.asp)

* The modal header has been problematic when I have tried the validator as my initial code with a ```html 'p'``` element being a child of a ```html'h4'``` wasn't correct. I did find the answer on [strackoverflow](https://stackoverflow.com/questions/50026151/bootstrap-4-add-a-subtitle-to-a-modal/50026307) using ```html 'br'``` and ```html 'small'``` instead.

### Supported screens and browsers

The website was mainly tested on different screen sizes using the devtool.
The web behaves in a responsive way in the different mobile sizes (Moto G4, Galaxy S5/A71, Pixel 2/2XL/3, iPhone 5/SE/6/7/8, iPhone 6/7/8 plus, iPhone X/10/12, Huawei p30)

It also behave as expected on tablets (iPad, iPad pro, surface duo)

* Google Chrome: website worked as expected
* Firefox: website worked as expected
* Microsoft Edge: website worked as expected
* Safari: website worked as expected

## Deployment

This website has been developed on Gitpod, using Github to host the repository

### Via Gitpod 

These are the step followed to deploy via Gitpod:
1. Log in to the Gitpod account 
2. Chose the MS1 repository
3. Add your code 
4. Type "python3 -m http.server" on the terminal
5. A new screen will pop up with the results of the code on the browser
### GitHub pages

These are the steps followed to deploy this website using GitHub:

1. Log in to your  GitHub account
2. Select MS1 on my repositories
3. Go to settings on the repository
4. Scroll down to the GitHub pages area
5. Select the Master Branch from the Source dropdown menu
6. Confirm my selection 

After this, the website was live on GitHub pages

### Making a Local Clone

Making a local clone of your repository allow others to view the original code and even to add changes on their own local copy.

To do so you have to 
1. Log in to GitHub and select teh repository you wish to clone
2. Click the download button or Code button
3. Copy the url that will show on the box
4. Open Gitpod (or your preferred IDE)
5. Use the "git clone" command in the terminal followed by url copied before

A clone of the original repository should be available on your computer

## Credits

* Design:
    * [GoogleFort](https://fonts.google.com/)
    * [MyColorSpace](https://mycolor.space/)
    * [Pexels](https://www.pexels.com/)
    * [Wireframe](https://balsamiq.com/)

* Coding:
    * Code Institute: I took inspiration above all from the Whisky project and the Mini project to structure my website and my coding
    * Slack community that is quite helpful when you are stuck and lacking inspiration
    * Stack Overflow: for helping me fix my [jumbotron](https://stackoverflow.com/questions/31147543/how-to-fit-100-of-an-image-to-a-jumbotron)
    * [W3school](https://www.w3schools.com/howto/howto_css_table_responsive.asp) The web has been with Bootstrap one of the first points of contact when I was encountering a problem. This specific link is for solving an issue with the table not being responsive
    * [Boostrap](https://hackerthemes.com/bootstrap-cheatsheet/) cheatsheet for helping to clarify concepts and give ideas
    * [Anna Greaves](https://ajgreaves.github.io/bootstrap-grid-demo/index.html) website help me with the grid and layout of the site. Her comments on how to create the milestone proyect on the Slack channel #user-centric-frontend were very helpful as well.

* Acknowledgements:
    * I would like to thank my fellow students in the Slack community and the tutor is there for their support
    * Tutor support for their assistance resolving bugs 
    * Also I would like to thank my mentor for his advice and aid in debugging technical issues 
    * The websites I used to inspire me were [KateWebster](https://katwebsteryoga.com/) and [CamYoga](https://www.camyoga.co.uk/)

