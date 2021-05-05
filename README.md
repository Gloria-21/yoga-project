## Purpose of the project
## User stories
## Features

* This website is responsive in all devices sizes
* Have intectave elements such as forms and links

## Future Features
## Desing
* **Typography**

    I used google fonts for my typography. I have chosen fonts Viga for the headers and Sarabun for the rest ot the page
    
* **Color scheme**

    I have used colorSpace to generate my colour scheme. The Natural Palette was the final choice and that includes #DF7D6D, #FFF6F3, #BB8378, #EDE9D0 as main colours.

* Imagery

    Video by Vlada Karpovich from Pexels
## Wireframe

The wireframes that can be found below have been created using Balsamiq suring the Scope plane part of the desing and planning porcess of this project.

* [Homepage Wireframe](https://github.com/Gloria-21/yoga-project/blob/master/Yoga-project%20-%20desktop.mhtml)

* [Mobile Wireframe](https://github.com/Gloria-21/yoga-project/blob/master/Yoga-project%20-mobile.mhtml)

* Contact us form Wireframe /*--needs links*/

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

    I used Balsamiq to create the wireframing during the desing process

5. [Git](https://git-scm.com/)

    Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub

6. [Github](https://github.com/Gloria-21/yoga-project)

    I used GitHub to store the projects code after being pushed from Gitpod

### Bugs

This is my firt ever proyect coding on my own. So far I am finding it challenging as I am trying to put in use what I have learnt on the course so far as well as keep discovering new funtionalities on Boostrap and CSS.

* My Navbar has been problematic from the beggining as I used navbar-light and bg-light and when I tried to apply my styling to the CSS sheet I was not able ot override boostrap styling. Looking for an answer I found !important, which worked perfecty until I was informed that is considered bad practice. I decided to delete the two boostrap classes that there were being problematic and once that was done all the styling on CSS started to work. That have shown me the importance of understanding the different classes that boostrap has on offer.

* I have problems also with the sizes of the images. First of all I made a mistake on my HTML structure as I missed the first part of the link on my src class. Also looking on CCS-tricks I found a way to use as a background, that it wasn't my intial thought. That structure didn't work on my desing as it was too clutered but made me think of a smaller image and then write the welcome message on it.
To do so I created the jumbotron class, there was few issues with the image not matching the size of the jumbotron that were sorted after consulting [Stackoverflow webpage](https://stackoverflow.com/questions/31147543/how-to-fit-100-of-an-image-to-a-jumbotron). I realised that container instead container-fluid would suit the project better for the result I had planned. Also I had to do some adjustment on the margins to get the desing to be responsive

* When I added the cards for the shcedules and the online courses to my features they shown one underneath the other. I reviewed the grid for the cards and I managed to get a responsive side by side result on my desktop/tablet layout following the [boostrap cheat-sheet](https://hackerthemes.com/bootstrap-cheatsheet/). After adding the Jumbotron class, I have encounter some issues as the cards weren't being responsive anymore and the footer out of place as well. I targeted the margin left to align the site and make it responsive, after that it worked correctly.

* The table created for the schedule.html wasn't responsive on mobile or table as the footer was not covering the the same area than the table. I added <div style="overflow-x:auto;"> as seen on [w3school webpage](https://www.w3schools.com/howto/howto_css_table_responsive.asp)
    