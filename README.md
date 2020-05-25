# technical-documentation-page

## Documentation Template

### Author: Adrienne Easton

### Links and Resources
* [Deployed site](https://adrienneeaston.github.io/technical-documentation-page/)

### Skills Practiced
* HTML
* CSS
* Familiarity with documentation
* Vertical nav bar
* Media queries

### Description
This website is a template page for technical documentation, done as code practice. The user stories and test suite were created by Free Code Camp.

### User Stories
* User Story #1: I can see a main element with a corresponding id="main-doc", which contains the page's main content (technical documentation).
* User Story #2: Within the #main-doc element, I can see several section elements, each with a class of main-section. There should be a minimum of 5.
* User Story #3: The first element within each .main-section should be a header element which contains text that describes the topic of that section.
* User Story #4: Each section element with the class of main-section should also have an id that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding id="JavaScript_and_Java").
* User Story #5: The .main-section elements should contain at least 10 p elements total (not each).
* User Story #6: The .main-section elements should contain at least 5 code elements total (not each).
* User Story #7: The .main-section elements should contain at least 5 li items total (not each).
* User Story #8: I can see a nav element with a corresponding id="navbar".
* User Story #9: The navbar element should contain one header element which contains text that describes the topic of the technical documentation.
* User Story #10: Additionally, the navbar should contain link (a) elements with the class of nav-link. There should be one for every element with the class main-section.
* User Story #11: The header element in the navbar must come before any link (a) elements in the navbar.
* User Story #12: Each element with the class of nav-link should contain text that corresponds to the header text within each section (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").
* User Story #13: When I click on a navbar element, the page should navigate to the corresponding section of the main-doc element (e.g. If I click on a nav-link element that contains the text "Hello world", the page navigates to a section element that has that id and contains the corresponding header.
* User Story #14: On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left side of the screen and should always be visible to the user.
* User Story #15: My Technical Documentation page should use at least one media query.

### Setup

#### Running the app
* `live-server`
  
#### Tests
* Test suite accessed by script tag in the HTML file:

```HTML
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
```
* Click on hamburger icon to open test suite.
* Select appropriate project from dropdown menu.
* Click `run tests`.

