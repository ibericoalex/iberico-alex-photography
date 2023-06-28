# **Iberico Alex Photography - Portfolio Project 1**

Iberico Alex Photography is a website that represents my own work as a freelance fashion photographer. It serves as a platform for showcasing my portfolio and provides clients with a convenient way to connect with me. With the aim of creating a useful online presence, I have included various features such as a collection of my best photographs, a selection of produced videos, a brief section about myself, and a contact form for clients to inquire about my services.

Live deployment link can be found [here](https://ibericoalex.github.io/iberico-alex-photography/).

![Website mockup](./assets/documentation/Website-mockup.png)

# Table of Contents

1. [Project Goals](#project-goals "Project Goals")
2. [User Experience](#user-experience "User Experience")
   - [Target Audience](#target-audience "Target Audience")
   - [User Requirements and Expectations](#user-requirements-and-expectations "User Requirements and Expectations")
   - [User Stories](#user-stories "User Stories")
3. [Design](#design "Design")
   - [Design Choices](#design-choices "Design Choices")
   - [Colour](#colour "Colour")
   - [Fonts](#fonts "Fonts")
   - [Music & Sounds](#music--sounds "Music & Sounds")
   - [Wireframes](#wireframes "Wireframes")
4. [Technologies, Languages & Programs Used](#technologies-languages--programs-used)
5. [Features](#features "Features")
   - [Existing Features](#existing-features "Existing Features")
     - [Start Screen](#start-screen "Start Screen")
     - [Game Screen](#game-screen "Game Screen")
     - [End Screen](#end-screen "End Screen")
   - [Future Features](#future-features "Future Features")
   - [Responsiveness](#responsiveness "Responsiveness")
6. [Testing](#testing "Testing")
   - [Bugs](#bugs "Bugs")
   - [Validator Testing](#validator-testing "Validator Testing")
7. [Deployment, Development & Version Control](#deployment-development--version-control)
8. [Credits](#credits "Credits")

## **User Stories**

As a **user**, I want **to be able to view a consistent colour scheme across the website** so that it **provides a seamless and harmonious browsing experience**.

As a **user**, I want **to be able to find and access the navigation bar** so that I can **navigate effortlessly through the platform**.

As a **user**, I want **to be able to view the footer section** so that I can **find social media links**.

As a **user**, I want **to be able to explore Iberico Alex's work, inclusing both photos and videos** so that I  **can appreciate the artist's talent and style**.

As a **user**, I want **to be able to contact the artist** so that I can **inquire about the services offered**.

As a **user**, I want **to be able to learn more about the photographer** so that I can **ensure that his background and artistic approach align with my preferences**.


## **Design**
For my project, I used my existing [website](https://www.ibericoalex.com/), built with [wix.com](https://www.wix.com/) website builder, as the foundation. The website showcases a bold, minimal, and clean design that perfectly complements my work and artistic perspective.

All the images and videos presented in the project are exclusively captured and owned by me.

### **Colour**
I have chosen bold colors like red, black, and white to represent my artistic brand. These colors not only enhance the visual appeal but also ensure easy readability for users. To generate the color scheme, I utilized [Coolors.co](https://coolors.co/ff0000-0d0d0d-fafafa-525252).

![Color palette](./assets/documentation/Color-palette.png)
### **Fonts**
I incorporated fonts from [Google Fonts](https://fonts.google.com/) into my website. For the main headers and logo, I selected the font Roboto, while for the body text, I opted for Nunito. These font choices add a stylish and cohesive touch to the overall design.

### **Wireframes**
Before proceeding with any HTML or CSS coding, I made use of Balsamiq to create wireframes for each of the four pages. This step allowed me to envision and solidify the desired visual structure of the changes I intended to implement from my previous website. By establishing a clear blueprint through wireframes, I could confidently proceed with the development process.

- Index/Portfolio page
![Wireframe index](./assets/documentation/index.png)

- Videos page
![Wireframe videos](./assets/documentation/Videos.png)

- About page
![Wireframe about](./assets/documentation/About.png)

- Contact page
![Wireframe contact](./assets/documentation/Contact.png)

## **Technologies, Languages & Programs Used**

* [HTML](https://www.w3schools.com/html/): Markup language for creating web pages.
* [CSS](https://www.w3schools.com/CSS/): Stylesheet language for styling the appearance of web pages.
* [GitHub](https://github.com/): Web-based platform for version control and collaboration on software projects.
* [GitHub Pages](https://pages.github.com/): Hosting service provided by GitHub for publishing static web pages.
* [Google Fonts](https://fonts.google.com/): Library of free and open-source web fonts.
* [Google Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/): Automated tool for auditing and improving web page quality.
* [W3C Validator](https://validator.w3.org/): Tool for checking HTML and CSS code compliance with web standards.
* [CodeAnywhere](https://codeanywhere.com/): Cloud-based integrated development environment (IDE) for coding, collaborating, and deploying projects.
* [VSCode](https://code.visualstudio.com/): Free and highly extensible source code editor with built-in features for editing, debugging, and version control integration. It supports various programming languages and is available for multiple platforms.


## **Features**
### **Common Features**
As the user navigates through the website, the following elements consistently appear across every page. These elements maintain a cohesive presence throughout the user's browsing experience.
 - **Logo and Navigation Bar** 
    - The logo and navigation bar are prominently displayed on every page of the website. These elements have been carefully designed and optimized to ensure seamless functionality across various screen sizes. The logo serves as a clickable link, directing users back to the homepage/portfolio. Additionally, each link within the navigation menu accurately leads users to the corresponding page, enhancing the overall user experience.

    ![Logo and navigation menu](./assets/documentation/logo-nav.png)

- **Favicon**
    - The favicon displayed on the browser tab encapsulates the branding of Iberico Alex Photography, providing a small yet impactful visual representation of the website's identity.

    ![Favicon](./assets/documentation/Logo-favicon.png)

- **Footer**
    - The footer is consistently visible on every page of the website. It features social media icons that are linked to the corresponding social media platforms, allowing users to easily connect and stay updated with the photographer on these platforms. This enables seamless access to the artist's social media presence and encourages users to stay connected and engaged with their latest updates.

    ![Footer](./assets/documentation/footer.png)


### **Homepage/Portfolio**

The landing page serves as the initial entry point for users when they first visit the website. It prominently showcases the portfolio of the photographer, providing a captivating introduction to their body of work.

The photo gallery draws inspiration from the Code Institute Love Running gallery masonry. When hovering over an image, it reduces its opacity to indicate the selected photo. The ultimate goal is to enable image enlargement upon clicking; however, implementing this functionality would require the use of JavaScript.

Additional noteworthy features include:
- The gallery is fully responsive, adjusting the column count based on the screen size for optimal viewing.
- The navigation bar has a visually appealing effect with a blurred transparent background color.
- On smaller screens, the navigation bar adapts by switching to a centered layout, ensuring both the logo and navigation options are displayed in a user-friendly manner.

![landing-page](./assets/documentation/landing-page.png)

### **Videos**

The landing page serves as the initial entry point for users when they first visit the website. It prominently showcases the portfolio of the photographer, providing a captivating introduction to their body of work.

![videos-page](./assets/documentation/videos-page.png)

* Landing page where user first arrives upon opening of application.
* Single image has been split up into three different images that are links to separate pages in the application.




![testimonials-page](./assets/documentation/features/testimonials-page.png)

* Navigation bar available at the top of page.
* Stylish hero image apparent upon opening of page.
* Incorporation of a LGBTQ+ colour theme.

![testimonials-page-example](./assets/documentation/features/testimonials-page-example.png)

* Podcast samples are found and available on the testimonial page.
* Users can actively engage with these podcasts and listen to them to engage with the application.

![conversation-game](./assets/documentation/features/conversation-page.png)

* Application contains a question-generator for in-person socialising. 
* Questions are generated with JavaScript at random.
* Users can engage with other people on a personal basis using this game.

![milestones-page](./assets/documentation/features/milestones-page.png)

* Milestone landing page has a historically relevant landing page.
* Navigation bar can also be seen for user-ease.

![milestones-page-example](./assets/documentation/features/milestones-page-example.png)

* Example of historical description for user engagement.

![milestones-page-second-hero](./assets/documentation/features/milestones-page-second-hero.png)

* Relevant hero image for the milestone events.
* Engaging, powerful imagery with strong references to the LGBTQ+ theme.

![milestones-page-example-event](./assets/documentation/features/milestones-page-example-event.png)

* Example of a historical event in LGBTQ+ history for educative purposes.

![footer](./assets/documentation/features/footer.png)

* Footer available at the bottom of every page.


## **Testing**

### **Manual Testing**

Manual testing following the User Stories was carried out throughout the development of the project, with the final results available below.

- As a **user**, I want **to be able to view a consistent colour scheme across the application** so that **the application and its navigation feels like a smooth transition**.

| **Test** | Issue | Result |
| -------- | ----- | ------ |
| 1        | Consistent colour palette is evident across the application is consistent with itself. | PASS   |

- As a **user**, I want **to be able to find and access the navigation bar** so that I can **navigate around the application with ease**.

| **Test** | Issue | Result |
| -------- | ----- | ------ |
| 2        | Navigation bar can be found on every page of the application and delivers the user from page to page with ease. | PASS   |

- As a **user**, I want **to be able to view the footer** so that I can **view any extra beneficial information regarding the application**.

| **Test** | Issue | Result |
| -------- | ----- | ------ |
| 3        | The footer can be view across every page of the application and compliments the site with its information regarding the team. | PASS   |

- As a **user**, I want **to be able to land on the home page** so that I am **able to have a central point of contact in the application**.

| **Test** | Issue | Result |
| -------- | ----- | ------ |
| 4        | Users land on the home page as soon as they open the link and can find their back to it, itself serving as a link between the theme of the application: connection. | PASS   |

- As a **user**, I want **to be able to find a question game** so that I can **play it in person with another stranger to get to know them better**.

| **Test** | Issue | Result |
| -------- | ----- | ------ |
| 5        | A game that randomly generates interesting and personal questions has been created for the user for their entertainment. | PASS   |

- As a **user**, I want **to be able to listen to different podcasts** so that I can **engage and associate with the experiences of others**.

| **Test** | Issue | Result |
| -------- | ----- | ------ |
| 6        | Podcasts have been used on the testimonial page and generated for user curiosity to be enjoyed and explored. Users are even able to engage further by having the option to contact the application management to send their own experiential testimony. | PASS   |

- As a **user**, I want **to be able to view historical information** so that I can **learn and appreciate LGBTQ+ history**.

| **Test** | Issue | Result |
| -------- | ----- | ------ |
| 7        | An archive of current and historical LGBTQ+ people can be found as well as information for the user regarding historical events. | PASS   |

## **Bugs**

### **Fixed bugs**

To find a list of fixed bugs that were mended during development, please click [here](https://github.com/keironchaudhry/june-pride-hackathon-2023/issues?q=label%3Abug+is%3Aclosed).

### **Remaining bugs**

* In the testimonial page, at the smallest media query, there is a giant margin-right due to an image conflict.

## **Validator Testing**

### **HTML Validator**

The [W3C Markup Validation Service](https://validator.w3.org/) for the HTML code was passed in as a URL and returned no errors.

![html-validator-results](./assets/documentation/readme_images/html-validator.png)

### **CSS Validator**

The [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) for the CSS code brings up one single error which is connected to the Materialize library. For the CSS code available and developed by the team, there are no errors.

![css-validator-results](./assets/documentation/readme_images/css-validator.png)

### **JSHint**

The [JSHint Validation Service](https://jshint.com/) for the JavaScript code was passed in as source code and returned no errors.

## **Deployment, Development & Version Control**

The development environment used for this project was VSCode, GitPod and CodeAnywhere.

Each software developer on the team created their own individual branch divergent from main from the get-go and have communicated via Slack to collaborate, pitch ideas, fix bugs and talk about relevant Pull Requests. Regular commits and pushes to Github have been employed to be able to track and trace the development process of the web application.

For local deployments instructions shall be written below, along with instructions with deployment to GitHub Pages, the hosting service used to deploy this particular website.

### **Local Deployment**

This repository can be cloned and run locally with the following steps:

- Login to GitHub.
- Select repository named: keironchaudhry/june-pride-hackathon-2023
- Click code toggle button and copy the url (i.e., https://github.com/keironchaudhry/june-pride-hackathon-2023.git).
- In your IDE, open the terminal and run the git clone command (i.e., git clone https://github.com/keironchaudhry/june-pride-hackathon-2023.git). The repository will now be cloned in your workspace.

### **Deployment to GitHub**

The live version of the project is deployed at GitHub pages.

The procedure for deployment followed the "Creating your site" steps provided in GitHub Docs.

- Log into Github.
- Select desired GitHub Repository to be deployed live.
- Underneath the repository name, click the “Settings” option.
- In the sub-section list on the left, under “Code and automation”, click “Pages”.
- Within the ”Source” section choose ”main” as Branch and root as folder and click ”Save”.
- The page refreshes and a website shall then deploy via a link.
- The following is the live link deployed: 

## **Credits**

### **Acknowledgments**

This project was created in collaboration by [Team Symbiotic+](https://hackathon.codeinstitute.net/teams/314/): [Hermon Asmelash](https://github.com/Hasmelash95), [Iberico Alex](https://github.com/ibericoalex), [Keiron Chaudhry](https://github.com/keironchaudhry), [Stephen Opoku](https://github.com/Stephenkofipoku), [Sam Petchey](https://github.com/sampetchey), [Samuel Ukachukwu](https://github.com/SamuelUkachukwu).
