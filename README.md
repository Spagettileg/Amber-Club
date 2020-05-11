# bootstrap | whiskey-drop

***
[Direct link to GitHub Repo](https://github.com/Spagettileg/Whiskey-Drop)

[Direct link to Live Project](https://spagettileg.github.io/Whiskey-Drop/) 

***

This project is designed to showcase a front end design built with the following 

 - [HTML](https://html.spec.whatwg.org/multipage/) | [Bootstrap](https://www.bootstrapcdn.com/) | [CSS](https://www.w3.org/Style/CSS/) | [jQuery](https://jquery.com/)

***
![](assets/img/whiskey-glass-image.png)

Whats not to like about whiskey? This website is built for the whiskey connoisseur who enjoys the finer things in life, like minded consumers give their feedback on premium products and opportunities to purchase whiskey at discounted prices.

The user experience centres upon signing up to an incentive based web design and the user is able to click on link buttons to access more feature information and sign up to promotion. 


***
## Table of Contents

1. [UXD Considerations](#uxd-considerations)
    * [User & Business Objectives](#user-&-business-objectives) 
    * [Wireframes](#wireframes)
    * [User Stories](#user-stories)
    * [CSS Framework](#css-framework)
    * [Colour Palette](#colour-palette)
    * [Typography](#typography)
    * [Icon Graphics](#icon-graphics)
    * [Navbar Design](#navbar-design)

2. [Technologies Applied](#technologies-applied)
    * [Languages](#languages)
    * [Libraries](#libraries)
    * [Tools](#tools)

3. [Features](#features)

4. [Tests](#tests)
    * [Compatibility](#compatibility)
    * [Test Observations](#test-observations)

5. [Deployment](#deployment)
    * [How to run this project locally](#how-to-run-this-project-locally) 

6. [Credits](#credits)
    * [Content](#content)
    * [Media](#media)
    * [Acknowledgements](#acknowledgements)

## UXD Considerations

### User & Business Objectives

#### User
- The user belongs to a community of whiskey enthusiasts
- Great product offerings and guidance upon a broad range of products made available
- Access to well known and lesser known products to help expand the users range
- Understand the background to Whiskey-Drop via all published media types
- Happy to browse products, without obligation to purchase

#### Business
- Promotion of latest products to generate customer demand 
- Advanced notice of new product offerings to help leverage customer interest. Early product reservations is the business objective here 
- Links provided for the user to understand Whiskey-Drops members favourite products 
- Offering free product samples to build customer trust, goodwill and the impression that value for money is being created.  
- Social media link access to further promote Whiskey-Drop and encourage member intra-communications

#### Next Stage Generation
- Increase product density through expanding scope of products, accessories, distillery tours, etc
- Leverage footfall data to attract commercial online advertising, with resultaqnt revenues used to maintain and grow website
- Affiliate with whiskey distilleries to encourage exclusivity on new products  
- Explore new social media channels to promote 'Whiskey-Drop'

### Wireframes
My wireframe mock-up design have been created in [Balsamiq](https://balsamiq.com/) to showcase the 'Whiskey-Drop' website responsiveness on mobile, tablet and desktop devices.

•	[Whiskey-Drop](https://github.com/Spagettileg/music-promotion-pbf/blob/master/wireframe/music-promotions-pbf_final.zip)


### User Stories
* Important updates on products and offerings to be made readily available
* Customer quotes that set out their own personal experience of Whiskey-Drop is important to view  
* An overview of the websites features such as a viewing gallery, guidance on shopping and ways to connect with Whiskey-Drop  
* Monthly favourites as voted for by registered members
* An understanding of Whiskey-Drops background and messages to get both new and existing customers excited 
* Information on product image, product name, product origin, price and tasting notes are required
* Ability to filter products by country will be helpful
* Access to Whiskey-Drops social media sites will be helpful to understand news and views from fellow whiskey fans
* Secure registration and user authentication process
* Secure payments process with a trusted online payments vendor
* Straightforward process to contact Whiskey-Drop
* A clear FAQ page that helps support enjoyment of using Whiskey-Drop and save on sending unecessary message
* Users privacy, extending to treatment of data being full respected by Whiskey-Drop
* A clear message on cookie usage when the user interacts with Whiskey-Drop website
* Full terms & conditions to be made available for all users

### CSS Framework
Bootstrap was the chosen framework for styling my project. I used the Bootstrap grid extensively to support responsiveness on mobile, tablet and desktop devices. 

### Colour Palette
Colours used in this project were sourced from [Colour Hunt](https://colorhunt.co/). Essentially, the colours are seeking to capture key attributes of whiskey through warmth, soft notes, citric, nutty, peppary & woody

Colour         | Hex Code
---------------|----------
Yellow         | #F78A00
Orange         | #F05F40
Charcoal Grey  | #343A40
Pencil Grey    | #BFBFBF
White          | #FFFFFF

### Typography
[Roboto](https://fonts.google.com/) font wwas used throughout this project.

### Icon Graphics
Font Awesome 5 icon graphics were used in conjunction with Bootstrap 4, primarily to support the features section, as viewed in `index.html` page 

Page                   | Function                            | Font  
-----------------------|------------------------------------ |-------
index.html             | features                            | `fas fa-glass-whiskey`

### Navbar Design
For tablet and desktop views, the navbar offers 6 functions on show. For mobile devices, all the same options collapse into a 'hamburger' design. 

- Navbar Brand
- Home
- About
- Gallery
- Sign In
- Register

## Technologies Applied

### Languages
•	[HTML](https://html.spec.whatwg.org/multipage/) used as the markup language

•	[CSS](https://www.w3.org/Style/CSS/) used to style the HTML

•   [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) used mostly for DOM manipulation

### Libraries
•	[Bootstrap](https://www.bootstrapcdn.com/) used to enable styling of front page and support aesthetic design

•	[jQuery](https://jquery.com/) used The integrity and crossorigin attributes are used for Subresource Integrity (SRI) checking. This allows browsers to ensure that resources hosted on third-party servers have not been tampered with. 

### Tools
•	[AWS Cloud9](https://aws.amazon.com/cloud9/) a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser.

•	[Balsamiq](https://balsamiq.com/) is a small graphical tool to sketch out user interfaces, for websites and web / desktop / mobile applications and used to visualise my project through mock-up design.

•	[Git](https://git-scm.com/) is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

•	[GitHub](https://github.com/) is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

•	[Jigsaw - CSS validation](https://jigsaw.w3.org/css-validator/) this validator checks the markup validity of CSS style sheet and ensure coding convention is upheld

•	[JS Hint](https://jshint.com/) a tool that helps to detect errors and potential problems in the javascript code

•	[W3C - HTML validation](https://validator.w3.org/) this validator checks the markup validity of HTML web documents


## Features

### index.html

Navbar (repeated on all pages) has been designed to include a clickable icon image that is synonymous with the bands brand. The user will always return to the home page with. In addition, the navbar allows the user to navigate to ‘about’and ‘gallery’ pages. A ‘hamburger’ design has been built to collapse the navbar for Mobile devices.

A full image of a full whiskey glass is on show from the header through to the first container ‘customer quotes’. Attractive narrative and a site register button are on show. Minimal colour palette used to help draw the users eye to the full glass of whiskey.    

‘Announcement’ is central to the home page. Users are notified up front of a reward when signing up to Whiskey-Drop

Customer quotes provides an image of the customer, occupation and a brief quote narrative

'Features' container includes 'Gallery', 'Shopping' and 'Connect'. There is a very social theme throug together to make user feel that are part of something special. Each feature is supported by a introduction narrative together with a button, when clicked, takes user to a modal window with image and further narrative    

'Monthly Favourites' tbale is a top 5 list of Whiskey-Drop members favourite product. Each product has a name, origin and rating score. The product name, when clicked, takes the user to a modal window where a full product image and detailed description can be viewed

Footer (repeated on all pages) includes please drink responsibility narrative and link to external website. Trading links to gallery and shopping. Social media links and fonts secured from bootstrap / font awesome5. The links are wired to Whiskey-Drops' respective social media sites. Again, the .hover pseudo class has been used to provide a background colour change (pencil grey to yellow) and font colour change too. Site links allow the use to access about, contact us, cookies, faqs, privacy policy and terms & conditions. The lower footing allows for Whiskey-Dropp' business operating years, powered by Javascript, copyright and web designer information.    

### about.html

Navbar (repeated on all pages) has been designed to include a clickable icon image that is synonymous with the bands brand. The user will always return to the home page with. In addition, the navbar allows the user to navigate to ‘about’and ‘gallery’ pages. A ‘hamburger’ design has been built to collapse the navbar for Mobile devices.

A bootstrap parallax design provides the foundation of a story of what Whiskey-Drop is and where users benefit from registering as a member

Barrel images appear at top and bottom of the parallax range, with a full whiskey glass and large stock of whiskey bottles postioned in between

Other containers are sandwiched between the above images to showcase Whiskey-Drops' access to global range of products and to introduce free sampling for undecided customers   

Footer (repeated on all pages) includes please drink responsibility narrative and link to external website. Trading links to gallery and shopping. Social media links and fonts secured from bootstrap / font awesome5. The links are wired to Whiskey-Drops' respective social media sites. Again, the .hover pseudo class has been used to provide a background colour change (pencil grey to yellow) and font colour change too. Site links allow the use to access about, contact us, cookies, faqs, privacy policy and terms & conditions. The lower footing allows for Whiskey-Dropp' business operating years, powered by Javascript, copyright and web designer information.    

### gallery.html

Product filter allows the user to view all products, or, view by country of origin. This graphic filter appears under the navbar

- Countries in spotlight, as follows:
    - Ireland
    - Scotland
    - USA
    - Japan
    - China
    - Rest of the World (Random collection on show)

All products are presented with a matching style in bootstrap grid design.

1. Product Image
2. Product Name
3. Price in GBP
4. Country Origin

User can hover over the product image to view tasting notes. There is sufficient opacity to ensure the user can see the product in the background. The tasting notes fall into 3 categories:

1. Appearance
2. Aroma
3. Taste

Important- The products on show are for illustration purposes only and have not been wired to a formal ordering and payments process. This upgrade is planned for a future release. 

## Tests

### Compatibility

### Test Observations

## Deployment

### How to run this project locally

## Credits

### Content

### Media

- [Barrel](https://hipwallpaper.com/barrel-backgrounds/) wallpaper image that provides the backdrop to `gallery.html` page
- [Customer](https://pixabay.com/images/search/people/) images that support the customer quotes featuring in `index.html`page
- [People connect images](https://www.thedigitaltransformationpeople.com/channels/customer-engagement/connecting-on-social/) to support club members interaction in `index.html` page
- [Whiskey Wallpapers](https://wallpapercave.com/whiskey-wallpapers) featuring in about.html page
- [Whiskey products](https://www.thewhiskyexchange.com/) sourced from The Whiskey Exchange and feature in gallery.html page 

### Acknowledgements
