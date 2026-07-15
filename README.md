# Pet Thinkful Portfolio
## About the Project
This project is a one-page portfolio website for Pete Thinkful, an artist based in Denver, CO.
## Design and Layout Plan
The goal of this project was to recreate the Pete Thinkful portfolio mock-up as closely as possible while building a clean, readable one-page portfolio website. The page was organized into five main sections: a header with navigation links, as About section, a Portfolio section, a Contact section, and a footer.

The layout used a centered page structure with a light bakground and dark blue text.  The header included the "Pete | Artist" title and horizontal navigation links that allow users to move directly to the About, Portfolio, and Contact sections.  The About section included a circular profile image with a dark border, introductory content, a bulleted list of artistic interests, and background information.  The Portfolio section displayed three artwork images vertically with titles and descriptions.  The Contact section included an ordered list of social-media links, followed by a centered footer.

The design decisions were based primarily on the provided project mock-up.  CSS was used to control alignment, spacing, typography, colors, image sizing, link apperance, and the overall visual hierarchy.  The layout was revised during development as individual elements were compared with the mock-up and adjusted.

## Implementation Plan
Build the HTML structure one section at a time, beginning with the header and navigation, followed by the About, Portfolio, Contact, and footer sections.  After completing and testing the HTML structure, apply CSS styling to match the provided mock-up. Use VS Code, Git and GitHub to save progress through commits GitHub Pages and VS Code Live Server to publish and review the live website, and the W3C Markup Validation Service to identify and correct HTML syntax and structural errors.

## Design Decisions and Trade-offs
The webpage was designed by the provided mockup over redesigning the page according to an alternative style.  Navigation-specific class was used instead of resusing the same class for both lists. I used the specific decendant selector for the footer rather than changing the global paragraph rule helped keep the design exactly the same as the mockup. I used the required palette and image treatment rather than introducing a custom brand direction.  Lastly, I used a simple one-page layout with anchor navigation rather than creating multiple pages was decided. Essentially, I by-passed greater creative freedom in exchange for closer alignment with the provided design requirements.

## Technologies and Tools Used
- HTML
- CSS
- Git
- GitHub
- Visual Studio Code
- MDN Playground
- The W3C Markup Validation Service

## AI Tool Disclosure
I used ChatGPT as a learning mentor and debugging resource throughout this project.  I used it to clarify unfamiliar concenpts, better understand Git, GitHub, and VS Code workflows, interpret project requirements, organize project documentation, and recieve guidance when troubleshooting HTML, CSS, and Markdown.  My goal was to complete the project independently rather than have AI generate the webpage.  I wrote and tested the HTML and CSS myself and used ChatGPT primaryly for explanation, reasoning prompts, terminology, and targeted guidance when I became stuck.  When possible, I attempted to identify the cause of an issue before requesting assistance.  

## Challenges and Debugging
### Understanding Git, GitHub, and the Development Workflow
One of my first challenges was understanding how VS Code, Git, GitHub, and GitHub Pages work together. I learned that staging selects the files to include in a commit, comitting records a version locally through Git, and syncing or pushing sends the commit to GitHub.  I also learned how to deploy the project through GitHub Pages and use a hard refresh when the live website temporarily displayed an older cached version.
### Targeting Elements with CSS Selectors
CSS was initially the most intiminating part of the project because I needed more experience identifying the correct selector During development, I began using a target-first approach: identify the exact element I want to change, select that element, and then apply the appropriate property and value. For example, I used a class selector to create Pete's circular image and a descendant selector to target list items inside the navigation.  I also learned that a general paragraph selector afftected the footer paragraph.  I corrected the issue by using a more specific descendent selector to center only the paragraph inside the footer.
### Seperating Navigation and About List Styles
I intially used the same class for the navigation list and the bulleted list in the About section.  As a result, the inline naigation styling also affected the About list. I corrected the issue by separating the navigation sytling so the navigation links could display horizontally while the About list, aligned the content to match the mock-up, and added anchor elements to make the social-media links clickable.
### Correcting the Contact Ordered List
While styling the Contact section, I encountered issues with list alignment and marker types. Some CSS declarations changed the numbered list markers into bullets. I learned that list-markers type, marker postion, and text alignment are separate styling concerns.  I simplified the CSS, restored the numbered list, aligned the content to match the mock-up, and added anchor elements to make the social-media clickable.
### HTML Validation
The W3C Markup Validation Service initially reported four errors. After reviewing the message, I discovered that all four errors resulted from one missing closing '</header>' tag. The browser still rendered the webpage because browsers can attempt to recover from invalid HTML, but the validator indentified the incorrect document hierarchy. Adding the missing closing tag resolved all four validation errors.
  
## What I Learned
During this project, I learned how to build and style a one-page portfolio, use CSS selectors to target specific elements, validate HTML, 
and use VS Code, Git and Github for version control. The following provides additional details:
*  HTML reates the structure and hierarchy of the webpage.
*  CSS controls presentation and begins with identifying the correct target.
*  A CSS rule follows the pattern: **selector -> property -> value**.
*  Element selectors, class selectors, pseudo-classes, and descendant selectors target different things.
*  A broad selector can unintentionally affect other elements.
*  More CSS is not always the solution; sometimes removing an unnecessary property fixes the problem.
*  Classess are resuable, but sharing a class can create unintended styling when elements need different behavior.
*  Parent-child relationships in HTML help you create more precise CSS selectors.
*  Git, GitHub, and GitHub Pages are different tools with different jobs.
*  Staging, committing, pushing, deploying, and refreshing are separate steps.
*  Browsers can disply a page even when the HTML structure contains errors.
*  One root coding error can create multiple validator messages.
*  Validation check code structure and standards and not whether the webpage looks attractive.
*  Debugging is observation, testing, identifying the cause, correcting it, and verifying the result.
*  Researching documentation is part of development and not evidence that you failed to memorize something.
*  A README is technical documentation that explains the project, process, tools, decisions, challendges, and learning and not merely a short description
*  I discovered that I genuinely enjoy CSS and visual front-end development.
  
## Development Screenshots
The following screenshots illustrate the development of the webpage from the original starter code through the completed and validated portfolio.
### Overall Webpage Progression
![Before index](screenshots/before-index-header.png)
![Index after header](screenshots/index-after-header.png)
![Before CSS Style](screenshots/before-style-css.png)
![Fixed link targets](screenshots/fix-link-targets.png)
### Header and Navigation
![After header and nav created](screenshots/add-header-and-nav.png)
### About Section
![About section text](screenshots/about-text.png)
### Portfolio and Contact Sections
![Webpage portfolio and Contact text](screenshots/portfolio-contact-text.png)
![Webpage portfolion section page 1](screenshots/add-portfolio-p1.png)
![Webpage portfolion section page 2](screenshots/add-portfolio-p2.png)
### Final Styled Webpage
![Final webpage part1](screenshots/final-webpage-p1.png)
![Final webpage part2](screenshots/final-webpage-p2.png)
![Final webpage part3](screenshots/final-webpage-p3.png)
![Final webpage part4](screenshots/final-webpage-p4.png)
### HTML Validation
![Validation syntax](screenshots/header-syntax-fix.png)
![Markup Validation no errors](screenshots/markup-validation-no-errors.png)
### Git Commit History

## Git Commit History

## Live Project
