# PPMA BEST

Stream One Project: User-Centric Frontend Development - Code Institute

As a current employee of the PPMA Group of Associations a need has been highlighted to update the exisiting website for the charitable branch of the organisation - PPMA BEST.

The existing site was created a number of years ago and as such, is dated in its appearance and is not responsive for smaller screens.

The current PPMA BEST website can be found [here](http://www.ppmabest.org.uk/).

## Demo

A live demo can be found [here](https://pengols.github.io/Milestone-1/).

![Desktop Demo](https://raw.githubusercontent.com/pengols/Milestone-1/master/mockups/websitemockup.PNG "Desktop Demo")

## UX

This website is designed for organisations that are members of, or are at least related to the Processing, Packaging or Machinery industries in the United Kingdom who employ or are interested in employing apprentices.  It is also aimed at apprentices that work for the aforementioned organisations who are interested in investigating the available grants and subsidies available to assist in their education.

The website aims to provide this often complex information in as clear and concise a manner as possible, provide an easy method to contact PPMA BEST for further information and to enforce the Charity's branding by using complimentary colours.

### User Stories

1. As a potential or existing employer of apprentices, I want to see the grants that are available to my organisation to assist with their development and the costs to me.

2. As an apprentice, I want to see the grants that I am able to apply for, for equipment to assist my apprenticeship.

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

### Footer

The footer contains contact information and links to social media.

### Features Left to Implement

- A gallery from past events
- Make the charity's social media available in feeds
- A modal to confirm successful completion of the contact form

## Technologies Used

### Languages

- HTML
- CSS

### Libraries

- [Bootstrap](https://getbootstrap.com/)
  - Open source toolkit for building mobile-first, responsive websites
- [FontAwesome](https://fontawesome.com/)
  - Provides icons for footer
- [Google fonts](https://fonts.google.com/)
  - Provides Barlow & Roboto fonts

### Other tools

- [CSS Gradient](https://cssgradient.io/)
  - Used to create gradient of background
- [Adobe Color](https://color.adobe.com/create)
  - Used to find compatible colors with brand logo #007270
- [TinyPNG](https://tinypng.com/)
  - Used to compress images to below 300kb
- [GitHub](https://github.com/)
  - Used for version control and hosting the project repository
- [markdownlint](https://dlaa.me/markdownlint/)
  - A Node.js style checker and lint tool for Markdown/CommonMark files

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

The website performs without issue on all browsers mentioned above.

### Testing tools

The website was tested using the following tools:

- [W3C Markup Validation Service](https://validator.w3.org/)
  - Cleaned up stray closing `</div>` and stray closing `</hr>` tags that were unnecessary.
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
  - No changes to CSS reported.
- [Autoprefixer CSS online](https://autoprefixer.github.io/)
  - Used to apply vendor specific prefixes to CSS for multiple browser support.
- [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools)
  - Used to test the responsiveness of the site across multiple screen sizes and test changes in page before committing.
- [Google Lighthouse](https://developers.google.com/web/tools/lighthouse/)
  - Used to check performance of site in desktop and mobile format.  Reduced image sizes to under 300kb to improve site response.
- [Responsinator](http://www.responsinator.com/)
  - Used to check the responsiveness of the site in various devices and screen sizes.

### Additional notes

- The contact form located in contact.html was tested with incorrect details in the name and email fields with browsers returning the correct error messages and not allowing the form to be submitted.

### Bugs encountered

- There is a bug in IE11 that moves the centered content in the jumbotron on all pages to the right.  This remains unaddressed at this point.

## Deployment

### GitHub pages

This website is deployed using GitHub pages and is available [here](https://pengols.github.io/Milestone-1/)

To deploy the website, the following steps were taken:

- Navigate to the [GitHub Repository](https://github.com/pengols/Milestone-1) for this project.
- Click settings tab
- Scroll down to GitHub pages section
- Select source as "master branch"

### GitHub clone

To clone the repository to create a local copy on your computer:

- Navigate to the [GitHub Repository](https://github.com/pengols/Milestone-1) for this project
- Click the clone or download button under the repository name
- To copy using HTTPS click the copy icon next to the URL
- Open Git Bash in your IDE
- Change the current working directory to the location where you want the cloned directory to be made
- Type `git clone`, and then paste the URL you copied in Step 3

    `git clone https://github.com/pengols/Milestone-1.git`

- Press Enter. Your local clone will be created.

## Credits

### Content

- The text for index.html, events.html, programmes.html & news.html was copied from the existing [PPMA BEST website](http://www.ppmabest.org.uk/) with permission.

### Media

- The photos used in this site were obtained from the [PPMA BEST website](http://www.ppmabest.org.uk/) with permission, and [Shutterstock](https://www.shutterstock.com/).

### Acknowledgements

- I received inspiration for this project from Danny Reed at PPMA BEST and assistance from SamFix G in the #peer-code-review channel in the CodeInstitute Slack, my mentor AntonioRodriguez_mentor and my Wife for providing QA and tea.
