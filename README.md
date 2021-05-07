# Yoga Project

Project - User-Centric Frontend Development - Code Institute.

## Purpose of the project

The purpose of this project is to create a yoga studio in Cambridgeshire that offers Hatta, Vinyasa yoga, and meditation. Providing that one of the teachers is a midwife they also offer prenatal and baby yoga. The studio impart possibilities for both face to face and online courses classes, making this way more accessible the practice of yoga

## User stories
The end user of this project is mainly the female population as the usual majority of attendance on yoga classes is women. Also, we have to bear in mind the prenatal and baby yoga classes are going to bring mums to be and mums to the classes, so it is expected that the scope of women attending the studio will be in the range of 20 to 50 years old.

The end user wants information about the services that Yoga Project has to offer 

* The user wants to know a what time the classes are
* Which type of yoga can she enjoys
* Which kidn of education the teachers have
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
It is divided in three sections maked with pictures that show the different classes online offered. They have buttons to purchase them and that activate a modal to sign up
* **Navbar:**
The navbar has links to all the pages to make the navigation smooth. Also on the mobile version it can be found on the top right corner as a burger button that collapses, giving a better UX experience
* **Footer:**
Each page has a Contact Us button that links to the Contact us page, also has links to social media

## Future Features
## Design
* **Typography**

    I used google fonts for my typography. I have chosen fonts Viga for the headers and Sarabun for the rest ot the page
    
* **Color scheme**

    I have used colorSpace to generate my colour scheme. The Natural Palette was the final choice and that includes #DF7D6D, #FFF6F3, #BB8378, #EDE9D0 as main colours that run all the way through the website giving warmth and continuity to the theme.

* **Images**

    All the images on the webiste have been taken from [Pexels](https://www.pexels.com/)
## Wireframe

The wireframes that can be found below have been created using Balsamiq suring the Scope plane part of the design and planning porcess of this project.


Original Wireframe

* [Landing page Mobile Wireframe](https://share.balsamiq.com/g/u5ix7GDWbSYkA11w6SGrx5.png)

* [Landing page Wireframe](https://share.balsamiq.com/g/er1s3g3voeHPLhMuVWUM4h.png)

## Tecnologies Used 

### Languages used
* [HTML5](https://en.wikipedia.org/wiki/HTML5)

* [CSS3](https://en.wikipedia.org/wiki/CSS)

### Frameworks, Libraries & Programs Used

1. [Bootsrap 4.4.1](https://getbootstrap.com/docs/4.4/getting-started/introduction/)

    I have used Boostrap to help with responsiveness of the webpage as well as the styling

2. [Google Font](https://fonts.google.com/)

    I have used Google font to import "Josefine Slab" into my style.css file, which is being used in all pages throughout the proyect

3. [FontAwesome](https://fontawesome.com/)

    Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes

 4. [Balsamiq](https://balsamiq.com/)

    I used Balsamiq to create the wireframing during the design process

5. [Git](https://git-scm.com/)

    Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub

6. [Github](https://github.com/Gloria-21/yoga-project)

    I used GitHub to store the projects code after being pushed from Gitpod

### Bugs

This is my firt ever proyect coding on my own. So far I am finding it challenging as I am trying to put in use what I have learnt on the course so far as well as keep discovering new funtionalities on Boostrap and CSS.

* My Navbar has been problematic from the beggining as I used navbar-light and bg-light and when I tried to apply my styling to the CSS sheet I was not able ot override boostrap styling. Looking for an answer I found !important, which worked perfecty until I was informed that is considered bad practice. I decided to delete the two boostrap classes that there were being problematic and once that was done all the styling on CSS started to work. That have shown me the importance of understanding the different classes that boostrap has on offer.

* I have problems also with the sizes of the images. First of all I made a mistake on my HTML structure as I missed the first part of the link on my src class. Also looking on CCS-tricks I found a way to use as a background, that it wasn't my intial thought. That structure didn't work on my design as it was too clutered but made me think of a smaller image and then write the welcome message on it.
To do so I created the jumbotron class, there was few issues with the image not matching the size of the jumbotron that were sorted after consulting [Stackoverflow webpage](https://stackoverflow.com/questions/31147543/how-to-fit-100-of-an-image-to-a-jumbotron). I realised that container instead container-fluid would suit the project better for the result I had planned. Also I had to do some adjustment on the margins to get the design to be responsive

* When I added the cards for the shcedules and the online courses to my features they shown one underneath the other. I reviewed the grid for the cards and I managed to get a responsive side by side result on my desktop/tablet layout following the [boostrap cheat-sheet](https://hackerthemes.com/bootstrap-cheatsheet/). After adding the Jumbotron class, I have encounter some issues as the cards weren't being responsive anymore and the footer out of place as well. I targeted the margin left to align the site and make it responsive, after that it worked correctly.

* The table created for the schedule.html wasn't responsive on mobile or table as the footer was not covering the the same area than the table. I added div style="overflow-x:auto;" as seen on [w3school webpage](https://www.w3schools.com/howto/howto_css_table_responsive.asp)

## Testing

## Validator testing