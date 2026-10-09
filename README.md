# Assignment 1 - Personal Portfolio Website

## Project Description
    This project is a personal portfolio website created for Web and Script Programming. The website was developed using HTML5 and CSS3 and contains four separate pages: Home, Contact Me, Projects, and About Me.

    The portfolio provides information about me, examples of projects I have completed, and a contact form that allows visitors to enter their name, email address, phone number, and comments.

## Responsive Design
    The website uses three separate CSS stylesheets to support different screen sizes:
    1. Mobile.css: screen widths of 480px or less.
    2. Tablet.css: screen widths of 481px to 959px.
    3. Full.css: screen widths of 960px or greater.

    These viewport sizes were selected based on the responsive design concepts covered in the Week 3 lecture. The lecture identifies smartphones as screens up to 480px wide, tablets as approximately 481px to 960px wide, and full-sized displays as 960px or greater.

    The website uses a fluid design so that content can adjust to different screen sizes. Percentage-based widths and responsive media sizing are used where appropriate. On the Home page, the desktop layout displays the main content in two columns, while the tablet and mobile layouts display the content in a single column. The mobile navigation is also stacked vertically and uses larger links to make navigation easier on smaller screens.

    Images and video are resized for smaller displays to prevent them from extending outside their sections. The Contact form also adjusts to the available screen width, with the Submit button expanding across the available width on mobile devices.

## Colour Scheme

    The colour scheme for the portfolio was created using the Adobe colour palette generator. I selected a purple, blue, and pink colour scheme because purple is my favourite colour and I wanted the portfolio to have a colourful appearance while still using a darker overall theme.

    The main colours from the generated palette include:

    - #6700ED - Purple
    - #1900ED - Blue
    - #B400ED - Magenta/Purple  
    - #0033ED - Blue
    - #ED66D7 - Pink

    Additional dark colours, including #160D24 and #251438, are used for the page and content backgrounds. #F5F5F5 is used for the primary text to provide contrast against the dark backgrounds.

## Gradients

    Two linear gradients are used throughout the website.

    The header uses a horizontal linear gradient:

    'linear-gradient(to right, #6700ED, #1900ED)'

    The footer uses an angled linear gradient:

    'linear-gradient(135deg, #6700ED, #B400ED)'

    The header gradient transitions from purple to blue from left to right. The footer uses a 135-degree angle to create the required angled linear gradient.

## Code Sources

    The HTML and CSS techniques used in this project are primarily based on concepts and examples taught in the INFR3120 course lectures.

    Course material used includes:

    - Week 1: Basic HTML and CSS, external stylesheets, CSS selectors, floats, clearing floats, and CSS linear gradients.
    - Week 2: HTML forms, labels, text and email input fields, HTML5 validation, required fields, and native HTML5 video.
    - Week 2B: Semantic HTML5 elements including header, navigation, article, section, and footer.
    - Week 3: Responsive web design, fluid layouts, percentage-based sizing, media queries, separate stylesheets for different viewports, and float-based layouts.

    The lecture material was adapted to fit the structure, content, colour scheme, and responsive layout of my personal portfolio.

### External Code

    A small amount of code outside of the course lecture examples was used with assistance from ChatGPT by OpenAI. This code represents less than 10% of the overall project and was adapted and understood before being included.

    The external techniques used were:

    - 'box-sizing: border-box;' - Used to include padding and borders within an element's specified width. This helps prevent the responsive form fields and desktop Home page columns from exceeding their intended widths.
    - 'pattern="[0-9]{10}"' - Used on the Contact form's telephone field to require a 10-digit phone number.

    Source: ChatGPT by OpenAI, used as coding assistance during development of the portfolio.

## Website Features

    - Four separate HTML5 pages: Home, About Me, Projects, and Contact Me.
    - Navigation between all four pages.
    - Semantic HTML5 elements used to organize page content.
    - Personal photo and introduction on the About Me page.
    - Embedded HTML5 video with video controls and a poster image.
    - Five previous projects displayed on the Projects page.
    - Contact form containing Name, Email, Cell Number, Comments, and Submit fields.
    - HTML5 client-side validation for required fields, email format, and phone number format.
    - Responsive layouts for mobile, tablet, and full-sized displays.
    - Fluid percentage-based layout on the Home page.
    - Horizontal and angled CSS linear gradients.
    - Adobe-generated colour scheme adapted to a dark purple theme.

## Testing and Validation

    The website was tested and validated before final submission using the following tools and methods:

        - W3C Markup Validation Service - All four HTML pages were validated successfully.
        - W3C CSS Validation Service - Full.css, Tablet.css, and Mobile.css were validated successfully.
        - W3C Link Checker - The website was checked for broken links.
        - Spell checking - The written content on all pages was reviewed for spelling errors.
        - WAVE Web Accessibility Evaluation Tool - All four pages were tested for accessibility errors and contrast issues. An alert related to captions/transcription was manually reviewed because the embedded video contains a piano performance with no spoken dialogue.
        - Responsive testing - The live website was tested at desktop, tablet, and mobile viewport sizes to verify that the navigation, content, images, video, and Contact form display correctly.

## Repository

    This repository contains the source files for my INFR3120 Assignment 1 Personal Portfolio Website.

    GitHub Repository:
    https://github.com/harrisongolden7417/Assignment_1

## Live Website
    The deployed portfolio website can be viewed at:

    https://harrisongolden7417.github.io/Assignment_1/