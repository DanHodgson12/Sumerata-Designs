# Sumersata Designs

Sumersata Designs is a craft-design business situated in the South West of England, offering unique crafted products and courses teaching people how to craft like them.

The primary goal of this website is to provide an informative and easy-to-use platform for the user to explore products and coursesm offered by Sumersata Designs, as well as offer the ability for the user to contact the business for craft-design requests.

Visit the deployed site here.

---

# User Experience (UX)

## Project Goals

* The website can be easily navigated and understood.
* Explains who Sumersata Designs are and what they have to offer.
* Contains clear imagery and content.
* Clearly outlines where to purchase products and courses offered.
* Shows a vibrant image gallery of craft designs.
* Provides a simple contact form.

## User Stories

* As a user, I want to be able to navigate the website easily.
* As a user, I want to know who Sumersata Designs are.
* As a user, I want to know how and where to purchase products and courses.
* As a user, I want to see a selection of previous/current designs.
* As a user, I want to be able to contact Sumersata Designs easily.

## Colour Scheme

![Colour Scheme](assets/readme-files/sd_color_scheme.png)

The colours used for this website are:

* Lilac (#b0bdef) - for the header, footer and contact form
* Beige (#d7d5c2) - for the background of the 'Reviews' section
* Off-white (#fefefc) - for the navbar toggler, nav underlines, social links icons and main background color for each page and all cards
* Light Grey (#5c5c5c) - for the social links, the background colour for the 'Address & Contact' section on the home page, the outline for the input fields of the contact form and the hover effect for the form submit button
* Charcoal (#313131) - for the bulk of the text including the nav title, card text and contact form text, and the nav link underlines

## Typography

The main font used throughout the site is Roboto Condensed, with sans-serif as a fallback if it fails to load. This font was suggested on [figma.com](https://www.figma.com/google-fonts/roboto-font-pairings/#:~:text=Roboto%20font%20pairings,Nunito%2C%20Raleway%20and%20Space%20Mono.) as a good font pairing with Lora, which is used for all headings and the nav title. Serif is used as a fall-back for Lora.

## Wireframes

# Features

# Technologies Used

## Languages Used

* [HTML](https://en.wikipedia.org/wiki/HTML)
* [CSS](https://en.wikipedia.org/wiki/CSS)

## Frameworks, Libraries and Programs Used

* [Google Fonts](https://fonts.google.com/)
  * Google fonts was used to import Lora and Roboto Condensed into the head of each page. These fonts are used throughout the website.

* [Font Awesome](https://fontawesome.com/)
  * Font Awesome was used to add icons for the social links and stars for the reviews section, to add a better user experience.

* [CodeAnywhere](https://app.codeanywhere.com/)
  * CodeAnywhere was used for writing, committing and pushing the code to GitHub.

* [Bootstrap](https://getbootstrap.com/)
  * Bootstrap was used to develop a responsive mobile-first design using an assortment of templates.

* [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
  * Chrome DevTools was used throughout the development of the website to test ideas and responsiveness, and debug issues that arose.

* [W3C Markup Validator](https://validator.w3.org/)
  * W3C Markup Validator was used to validate the HTML code.

* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
  * W3C CSS Validator was used to validate the CSS code.

* [Favicon.io](https://favicon.io/)
  * Favicon.io was used to create the site favicon.

# Testing

## Testing User Stories

## Code Validation

* The [W3C Markup Validator](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) services were used to checl for any code errors or misuse of syntax/elements.

  * The W3C Markup Validator returned a few errors:

    * The use of an aria-label on a div element which containtd a background image. This was overcome by adding an "sr-only" Bootstrap class to a 'p' element which a description of the image.
    * The use of a div element inside a figure element. This was overcome by changing the element to a span and moving it inside the ficcaption element.
    * The use of a 'section' element without a heading. This was overcome by removing it altogether, as it didn't serve a purpose.
    * The form inputs and labels missing ID attributes which were added shortly after.

  * The W3C CSS Validator returned no errors in my code.

# Finished Product

# Deployment

# Credits

# Acknowledgements
