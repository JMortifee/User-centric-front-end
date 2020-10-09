# Greenstride (UX Design for User-Centric Front End Milestone Project) 

# Table of Contents
1. [Introduction](#intro) 
2. [UX](#UX)
3. [Features](#features)
4. [Technologies](#tech)
5. [Testing](#testing)
6. [Deployment](#deployment)
7. [Credits](#credits)
8. <a href="https://jmortifee.github.io/user-centric-front-end/" target="_blank">Site</a>

## Introduction <a name="intro"></a>
For this project, I have decided to develop a website for the IT relocation company greenstride. The overall goal of the project will be to create an attractive and intuitive website to increase traffic and inquiries. The website must contain at least 3 pages of custom HTML5 and a supporting CSS3 style document. There must be a navbar and a supporting README.md file.

Greenstride are specialists in IT relocation, installation, and recycling, based in the southwest of the UK and South Wales.

## UX <a name="UX"></a>

Greenstried's website will be viewed by potential customers who are both knowledgable, and completely new to the services Greenstride provides. To ensure both parties, and all of those in between, have a positive emotional reaction to the site, the information must be informative without being jargon-filled. Images will be placed in each section to inform the user, at a glance what the section is about.

### User Stories

Below are four user stories that have been extrapolated out of 2 epics:

#### Epic 1: Users want to be able to view the services that Greenstride provides so that they can determine if they are the services the user requires. The user can then learn more about these services in more detail and get in contact if they want a quote.

__User story 1:__ The user wants to see the services Greenstride provide and how they go about these services.

__Solution to user story 1:__ When the user loads the website the home page will contain a brief overview of the company, there will also be a button for the user to click to get to the services page to learn more about the company.

![Home Wireframe](wireframes/home-wireframe.png)

__User story 2:__ Once the user has read through the information about the service they would like to use they need to be able to get in contact.

__Solution for user story 2:__  At the end of each services section an embedded link in some text will guide them to the contact page.

![Home Wireframe](wireframes/services-wireframe.png)

#### Epic 2: Existing customers or users who have been recommended Greenstride, want to be able to get a quote quickly.

__User story 3:__ The user knows or has learnt of the services and would immediately like to get in contact.

__Solution for user story 3:__  Next to the learn more button there will be a quick quote/ contact button that will take you directly to the contact page where there will be phone information and a contact form.

![Home Wireframe](wireframes/home-wireframe.png)

__user story 4:__ The User is an existing customer and would like to see what their company has used Greestride for in the past.

__Solution to user story 4:__ A login section will allow users to see their previous invoices and transactions.

![Home Wireframe](wireframes/contact-wireframe.png)

## Features <a name="features"></a>

__Navbar:__ The navbar is used to easily navigate between the pages of the site, by selecting which page the user wants.

__Home Jumbotron Buttons:__ The Buttons on the jumbotron allow for a quick navigation to the desired location, by clicking the desired button.

__Contact Form:__ The contact form allows users to send an enquiry directly from the website, by filling out the form or calling the number.

__Existing Customer Login:__ A login for existing customers to view their transactions and recycled waste.

### Existing Features

__Navbar:__ I used a clean and simple design for the navbar so that it was easy to use but didn’t distract from the content of each page. It consists of a home, services and contact button that fade to a darker colour when hovered over and stay darker to show what page the user is on.

![navbar](screenshots/navbar.png)

![Navbar with home active and contact hovered over](screenshots/navbar-close.png)

__Home Jumbotron Buttons:__ The Buttons on the jumbotron of "learn more" and "get a quote" are large enough for the user to understand their purpose immediately. Their static colour is in keeping with the colour scheme of the company’s logo and when hovered over they slowly transition to a darker colour that is also in keeping with the company’s colours.

![Home page with "get a quote" hovered over](screenshots/home-buttons.png)

__Contact Form:__ The contact form is clean and aesthetically pleasing with inputs that will give the person who receives the enquiry enough information to send a quote or contact the user for more information. I used light text on a dark background to ensure it was easy to read and not harsh on the eye.

![Navbar with home active and contact hovered over](screenshots/contact.png)

### Features Left to Implement

__Existing Customer Login:__ I do not have the knowledge to be able to implement this feature yet however I would have put a link in the navbar to easily access an existing users account.

## Technologies <a name="tech"></a>
### HTML5
I Used HTML5 because it is the best language for creating static webpages to be displayed on browsers. it is the most efficient and simple to use and understand.

### CSS3
I Used CSS3 because it is the best language for styling HTML5 webpages

### Bootstrap 4
I used Bootstrap because it uses CSS3 to implement styles into HTML documents via class names. This greatly increases the speed in which a webpage can be generated without having to style every single element on the page. The CSS code can then be overwritten by a custom CSS file or inline styling.

<a href="https://getbootstrap.com/docs/3.4/" target="_blank">Here is a link to the Bootstrap4 website</a>

### Fontawesome
I used Font Awesome because it has a lot of aesthetically pleasing icons that can be easily implemented with a quick copy and paste. they can turn a webpage from being just lines of text to a more interesting minimalist style with small simplistic images to enhance the text.

<a href="https://fontawesome.com/" target="_blank">Here is a link to the Fontawesome website</a>

### Google Fonts
I used Google fonts because it is a great way to implement different fonts into an HTML document with very little effort.

<a href="https://fonts.google.com/" target="_blank">Here is a link to the Google Fonts website</a>
### Balsamiq
I used Balsamiq as it is a good-looking wireframing tool that is easy to manipulate and edit in any way you need. 

<a href="https://balsamiq.com/" target="_blank">Here is a link to the Balsamiq website</a>


## Testing <a name="testing"></a>

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

### Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment <a name="deployment"></a>

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits <a name="credits"></a>
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X


Click <a href="https://jmortifee.github.io/user-centric-front-end/" target="_blank">here</a> to view the site.
