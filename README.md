# PPMA BEST

Stream One Project: User-Centric Frontend Development - Code Institute

As a current employee of the PPMA Group of Associations a need has been highlighted to update the exisiting website for the charitable branch of the organisation - PPMA BEST.

The existing site was created a number of years ago and as such, is dated in its appearance and is not responsive for smaller screens.

The current PPMA BEST website can be found [here](http://www.ppmabest.org.uk/).
 
## Demo

A live demo can be found [here](https://pengols.github.io/Milestone-1/).

![Desktop Demo](https://raw.githubusercontent.com/pengols/Milestone-1/master/mockups/website-mockup.PNG "Desktop Demo")

## UX

This website is designed for organisations that are members of, or are at least related to the Processing, Packaging or Machinery industries in the United Kingdom who employ or are interested in employing apprentices.  It is also aimed at apprentices that work for the aforementioned organisations who are interested in investigating the available grants and subsidies available to assist in their education.

The website aims to provide this often complex information in as clear and concise manner as possible, provide an easy method to contact PPMA BEST for further information and to enforce the Charity's branding by using complimentary colours.

### User Stories

1. As a potential or existing employer of apprentices, I want to see the grants that are available to my organisation to assist with their development and the costs to me.

2. As an apprentice, I want to see the grants that I am able to apply for for equipment to assist my apprenticeship.

3. As an active member of the Processing, Packaging and Machinery Association I would like to be able to contact PPMA BEST to see how I can get involved.

### Wireframes

Wireframes were created using [balsamiq](https://balsamiq.com/), and the mockups can be found [here](https://raw.githubusercontent.com/pengols/Milestone-1/master/mockups/Milestone1wireframe.pdf).

## Features

### Home

Strong branded page with a synopsis of the charity and it's goals.

### Events

A responsive table of all upcoming events that PPMA BEST is undertaking in the near future.

### News

A list of the most recent updates from PPMA BEST and links to further information.

### Programmes

Information on the four different subsidies and grants provided by the charity and links to further information.

### Contact

A contact form to initiate a dialogue with the charity.

### Features Left to Implement
- a gallery from past events.
- make the charity's social media availble in feeds

## Technologies Used

### Languages

- HTML
- CSS

### Libraries

- [Bootstrap](https://getbootstrap.com/)
- [FontAwesome](https://fontawesome.com/)
  - Provides icons for footer
- [Google fonts](https://fonts.google.com/)
  - Provides Barlow & Roboto fonts


### Other tools

- [CSS Gradient](https://cssgradient.io/)
  - used to create gradient of background
- [Adobe Color](https://color.adobe.com/create)
  - used to find compatible colors with brand logo #007270

## Testing

### Browsers

The website has been tested physically on the following devices / browsers:
- Desktop Windows 10 / Mozilla Firefox
- Desktop Windows 10 / Microsoft Edge
- Desktop Windows 10 / Google Chrome
- Macbook Pro / Safari
- Motorola G4 / Google Chrome
- Samsung S8 / Google Chrome
- Samsung S8 / Samsung Internet

The website performs well on all browsers mentioned above and scales to smaller screens without issue.

### Testing tools

The website was tested using the following tools:
- [W3C Markup Validation Service](https://validator.w3.org/)
  - cleaned up stray closing div and stray closing hr tags that were unnecessary.
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) Autoprefixer CSS online
  - no changes to CSS reported.
- [Autoprefixer CSS online](https://autoprefixer.github.io/)
  - used to apply vendor specific prefixes to CSS for multiple browser support
- [Google Lighthouse](https://developers.google.com/web/tools/lighthouse/)
  - used to check performance of site in desktop and mobile format.  Reduced image sizes to under 300kb to improve site response.

### Additional notes

- the contact form located in contact.html was tested with incorrect details in the name and email fields with browsers returning the correct error messages and not allowing the form to be submitted.

### Bugs encountered

- There is a strange bug in IE11 that moves the centered content in the jumbotron on all pages to the right.  This remains unaddressed at this point.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

This website is deployed using GitHub pages and is available [here](https://pengols.github.io/Milestone-1/).

To deploy the website, the following steps were taken:
 - Navigate to the [GitHub Repository](https://github.com/pengols/Milestone-1) for this project.
 - Click settings tab
 - Scroll down to GitHub pages section
 - Select source as "master branch"

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for index.html, events.html, programmes.html & news.html was copied from the existing PPMA BEST [website](http://www.ppmabest.org.uk/) with permission.

### Media
- The photos used in this site were obtained from [PPMA BEST](http://www.ppmabest.org.uk/) with permission, and [Shutterstock](https://www.shutterstock.com/)

### Acknowledgements

- I received inspiration for this project from X
