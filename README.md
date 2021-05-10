# Yoga Project

Project - User-Centric Frontend Development - Code Institute.

## Purpose of the project

The purpose of this project is to create a yoga studio in Cambridgeshire that offers Hatta, Vinyasa yoga, and meditation. Providing that one of the teachers is a midwife they also offer prenatal and baby yoga. The studio impart possibilities for both face to face and online courses classes, making this way more accessible the practice of yoga

## User stories
The end user of this project is mainly the female population as the usual majority of attendance on yoga classes is women. Also, we have to bear in mind the prenatal and baby yoga classes are going to bring mums to be and mums to the classes, so it is expected that the scope of women attending the studio will be in the range of 20 to 50 years old.

The end user wants information about the services that Yoga Project has to offer 

* The user wants to know a what time the classes are
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
It is divided into two sections, the teachers bio and the schedule table. The use of alternate colors and the pictures of teaches helps to create a contrast amongst both

* **On-demand Classes:**
It is divided in three sections maked with pictures that show the different classes online offered. They have buttons to purchase them and that activate a modal to sign up. When that button is clicked it leads to the Success page

* **Contact us:**
This page wasn't planned on the original wireframe, it was created as was going along with the project and it become clear the it was necessary to have it. It follows the same structure of Navbar and footer as well as the same chromatic scheme, but present a form as main elemet of the body as well as a button that lead to the Sucess page

* **Success page**
This page wasn't included on the original plan either. It has the general stucture of Navbar and footer being the main body a jumbotrom with a background image and a message and a button to go to the Home page

* **Navbar:**
The navbar has links to all the pages and all pages has it, so in this way the navigation is smooth. Also on the mobile version it can be found on the top right corner as a burger button that collapses, giving a better UX experience

* **Footer:**
Each page has on the footer a Contact Us button that links to the Contact us page, also has links to social media

## Future Features

In the future I would like to add another path for clients that already have an account and would like to sign up. Also I would like to implement the payment system on the website and add some users reviews.
## Design
* **Typography**

    I used google fonts for my typography. I have chosen fonts Viga for the headers and Sarabun for the rest ot the page
    
* **Color scheme**

    I have used colorSpace to generate my colour scheme. The Natural Palette was the final choice and that includes #DF7D6D, #FFF6F3, #BB8378, #EDE9D0 as main colours that run all the way through the website giving warmth and continuity to the theme.

* **Images**

    All the images on the website have been taken from [Pexels](https://www.pexels.com/)
## Wireframe

The wireframes that can be found below have been created using Balsamiq suring the Scope plane part of the design and planning process of this project.


* [Landing page Mobile Wireframe](https://share.balsamiq.com/g/u5ix7GDWbSYkA11w6SGrx5.png)
* [Schedule page Mobile Wireframe](https://share.balsamiq.com/g/6hUk3HXucuYDQDASriEy9M.png)
* [On-demand courses page Mobile Wireframe](https://share.balsamiq.com/g/qjkRjP8esH6tNEP5gcLped.png)

* [Landing page Desktop Wireframe](https://share.balsamiq.com/g/er1s3g3voeHPLhMuVWUM4h.png)
* [Schedule page Desktop Wireframe](https://share.balsamiq.com/g/hD3Gddt7uv5dPUXULouA3j.png)
* [On-demand courses page Desktop Wireframe](https://share.balsamiq.com/g/qgaUxBLqi71B4inU84zbDo.png)

## Technologies Used 

 As it follows below
### Languages used
* [HTML5](https://en.wikipedia.org/wiki/HTML5) 

 I have used HTML5 to design the structure  adn the content of the webiste 

* [CSS3](https://en.wikipedia.org/wiki/CSS)

 I have used CSS3 to style the apearence of the website
### Frameworks, Libraries & Programs Used

1. [Bootsrap 4.4.1](https://getbootstrap.com/docs/4.4/getting-started/introduction/)

    I have used Boostrap to help with responsiveness of the website as well as the styling

2. [Google Font](https://fonts.google.com/)

    I have used Google font to import "Josefine Slab" into my style.css file, which is being used in all pages throughout the project

3. [FontAwesome](https://fontawesome.com/)

    Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes

 4. [Balsamiq](https://balsamiq.com/)

    I used Balsamiq to create the wireframing during the design process

5. [Git](https://git-scm.com/)

    Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub

6. [Github](https://github.com/Gloria-21/yoga-project)

    I used GitHub to store the projects code after being pushed from Gitpod

### Bugs

This is my first ever project coding on my own. So far I am finding it challenging as I am trying to put in use what I have learnt on the course so far as well as keep discovering new funtionalities on Boostrap and CSS.

* My Navbar has been problematic from the beginning as I used navbar-light and bg-light and when I tried to apply my styling to the CSS sheet I was not able ot override boostrap styling. Looking for an answer I found !important, which worked perfectly until I was informed that is considered bad practice. I decided to delete the two boostrap classes that there were being problematic and once that was done all the styling on CSS started to work. That have shown me the importance of understanding the different classes that boostrap has on offer.

* I have problems also with the sizes of the images. First of all I made a mistake on my HTML structure as I missed the first part of the link on my src class. Also looking on CCS-tricks I found a way to use as a background, that it wasn't my initial thought. That structure didn't work on my design as it was too cluttered but made me think of a smaller image and then write the welcome message on it.
To do so I created the jumbotron class, there was few issues with the image not matching the size of the jumbotron that were sorted after consulting [Stackoverflow webpage](https://stackoverflow.com/questions/31147543/how-to-fit-100-of-an-image-to-a-jumbotron). I realised that container instead container-fluid would suit the project better for the result I had planned. Also I had to do some adjustment on the margins to get the design to be responsive

* When I added the cards for the schedules and the online courses to my features they shown one underneath the other. I reviewed the grid for the cards and I managed to get a responsive side by side result on my desktop/tablet layout following the [boostrap cheat-sheet](https://hackerthemes.com/bootstrap-cheatsheet/). After adding the Jumbotron class, I have encounter some issues as the cards weren't being responsive anymore and the footer out of place as well. I targeted the margin left to align the site and make it responsive, after that it worked correctly.

* The table created for the schedule.html wasn't responsive on mobile or table as the footer was not covering the the same area than the table. I added div style="overflow-x:auto;" as seen on [w3school webpage](https://www.w3schools.com/howto/howto_css_table_responsive.asp)

* The modal header has been problematic when I have tried the validator as my initial code with a <p> being a child of a <h4> wasn't correct. I did find the answer on [strackoverflow](https://stackoverflow.com/questions/50026151/bootstrap-4-add-a-subtitle-to-a-modal/50026307) using <br> and <small> instead.
## Testing

### Validator testing

The webistes used to check the validity of the codes are [W3C Markup Validation](https://validator.w3.org/) and [W3C CSS Validation](https://jigsaw.w3.org/css-validator/)
All the pages passed the validator with 0 errors [Home](![Alt text](/assets/doc/validator/index-html-validator.png))

### Test case

The potential clients fo the webiste can follow two different paths depending on their necesities.
If they chose attend to a face to face class they will follow 

Home > Schedule (card or navbar) > Contact us > Success 

If they are looking for an online course to practice on their own time they will follow

Home > On-demand (card or navbar) > Purchase > Create an account > Success

## Deployment
### Via gitpod

To deploy the project via gitpod
