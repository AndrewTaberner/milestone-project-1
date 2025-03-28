# GT Elite

GT Elite is a fictional Preformance Car hire website offering high performance luxury cars to rent for any event.

---

## Features

1. Navigation bar
2. Our range section
3. contact section
4. Request quote form
5. Success screen

---

## Audience

The website hopes to attract all types of audience, but is mostly targeted at customers who are are planning special event (i.e. Wedding, Prom or Graduation).

---

## User Stories

User stories are short, simple descriptions of a feature or requirement from the end user’s perspective. They help teams understand what users need and why. This aid the planning and design process. Here are the user stories for the project.

- As a First-Time Visitor, I need easy navigation and a user-friendly design, including a responsive layout for my device, so I can find information quickly and efficiently without frustration.
- As a visitor, I want to see high-quality images and specifications of the companies available cars for hire, so I can decide on the right type of car for me.
- As a potential customer, I need to find essential information such as location, contact details, and opening hours, so I can easily plan my visit or get in touch the company.
- As a Customer, I want to request a quote using a simple inquiry form, so I can plan this into my budget.

---

## Project Planning

### Project board

The project board is a tool to aid a developer what the minimum elements are needed to be created for the website to be fit for purporse. The user stories are assigned labels for must-have, should-have, could-have (MSC), based on the above goals and project constraints.

The project board can be viewed here:
[project board](https://github.com/users/AndrewTaberner/projects/3)

## Wireframes

The basic wireframes were drawnup. Here is an example:

![wireframe](./assets/images/wireframe.jpg)

## Design choices

The overall design was to give a luxury high performance feel. The following design choices were made with this in mind:

### Font

The font chosen was "Big Shoulders". This was chosen to git the pages a mordern, tech, speedy feel.

### Colours

The colour scheme was generated from colormind.io and has colours of white and grey to give a good contrast.

![colors](./assets/images/colourmind.jpg)

## Testing

Several different methos were employes for testing, These were:

- Features Testing
- Browser Compatability
- Responsiveness
- Code Validation
- Lighthouse
- Accessibility

To view the project and conduct testing VSCode terminal command as shown below was used. Then the link below was followed by using 'ctrl + click'.

![link](./assets/images/terminal-link.jpg)

### Features Testing

This tests the functional elements of the site.

|        Feature         |               Test Case               |                  Outcome                   |
| :--------------------: | :-----------------------------------: | :----------------------------------------: |
|          Logo          |            Click logo icon            |            Home page displayed             |
|    Navbar-Home Page    |    Click the home link on eachpage    |          User taken to home page           |
|    Navbar-Our Range    | Click the Our Range link on each page |       User taken to gallery of cars        |
|     Navbar-Contact     |         Click on contact limk         |         Contact details displayed          |
| Navbar-Request a Quote |     Click on Request a quote link     |       User taken to quote form page        |
|   Social Media Links   |      Click on Social Media Link       | User taken to respective Social Media page |

### Browser Compatibility

This tests compatibilty of the project on browsers tha the user will commonly use.

| Browser tested | Intended appearance | Intended responsiveness |
| :------------: | :-----------------: | :---------------------: |
|     Chrome     |        Good         |          Good           |
|      Edge      |        Good         |          Good           |
|    Firefox     |        Good         |          Good           |

|Device tested|Site responsive >=700px|Site responsive <600px|Renders as expected|
|iphone 14|N/A|Good|Good|
|Tablet|Good|N/A|Good|
|Laptop 1024px|Good|N/A|Good|
|Desktop 1440px|Good|N/A|Good|

A mock up of this can be viewed [here](./assets/images/mock-up.jpg)

### Code Validation

## W3C CSS Validation

This was carried out to check for errors in the CSS files. The results are shown below.

![W3C-result](./assets/images/w3c-css.jpg)

## Validator

This was carried out the validate the code in each HTML file.
|Validator used|Code tested|Result|
| :------------: | :-----------------: | :---------------------: |
|W3 HTML Checker|index.html|No errors found, for info and a warning only|
![info-warning](./assets/images/index.html-info-warning.jpg) Info message due to format tool Prettier.
|W3 HTML Checker|gallery.html|Errors found, Warning shown|
![error](./assets/images/stray-tag.jpg)
![warning](./assets/images/validator-warning.jpg)
|W3 HTML Checker|quote.html|No errors found, for info and a warning only(see index.html)|
|W3 HTML Checker|success.html|No errors found for info (due to Prettier)and a warning only(see index.html)

### LightHouse

Performance and accessibilty testing was conducted usin Lighthouse. This is accessed via DevTools. As seen below, no issues were encoutered.

![lighthouse-result](./assets/images/lighthouse-result.jpg)

---

## Deployment

The steps below are used to deploy the project to Github pages.

1.  Login to github.
2.  On the dashboard screen select "AndrewTaberner/milestone-project-1"
    From the top respositaries section.
    ![images](./assets/images/Repo-section.jpg)
3.  Click on the "settings" icon.
    ![settings](./assets/images/settings.jpg)
4.  In the sidebar on the left click on "Pages"
    ![images](./assets/images/pages.jpg)
5.  Under Build and Deployment select "Deploy from a branch" from the Source dropdown menu.
    ![images](./assets/images/build.jpg)
6.  Under Branch, below the Source dropdown menu, select "main" and "/ root" respectively.
7.  Select Save to confirm

Once confirmed, GitHub will build and deploy the site. After a few minutes a link to the webpage will appear.
![images](./assets/images/build.jpg)
You may need to refresh the page to see the link.

The deployed website can be viewed here:

- [View the deployed website](https://andrewtaberner.github.io/milestone-project-1/)

Once deployed, the project was tested using various devices including a laptop and mobile phone. On the desktop, browsers Edge, Chrome and Firefox were used to certify compatibility. DevTools was also used to check responsivness.

## Deployed project

![images](./assets/images/mock-up.jpg)

## How to run the project loacally

To Clone the project from GitHub:

1. Navigate to the repository [https://github.com/AndrewTaberner/milestone-project-1]
2. Click the Code button and copy the repository URL.
3. Open your terminal or Git Bash.
4. Change your working directory to where you want the cloned directory to be made.
5. Type git clone then paste in the [repository URL] from step 2.
6. Press Enter.

## Credits

- Thanks to my mentor Lauren-Marie for her patience and support as I built this project.
- Thanks to fellow students on slack.
- Thanks to Tutor Support.
- Code snippets used from getbootstrap.com:

  Navbar used on all pages.
  Card sections used on 'Our Range' page.

  - Font Awesome: For the social media and address icons in the footer.
    Code Institute Boardwalk Games Online Tutorials for use as templates.

- Fonts were sourced from Google Fonts

- Images taken from Auto Trader

- Mock-up created at https://techsini.com/multi-mockup/
