# SkiArise

SkiArise is a (fictitious) company specializing in package ski / snow-boarding holidays. The company wants a website to increase brand awareness and sales.

The [**Project Planning**](project_planning.md) document outlines the business goals of the company and the user stories which were used to inform the development of the website.

You can visit the deployed website <a href="https://lowrycode.github.io/ski-arise-project/index.html" target="_blank" rel="noopener">**here**</a>.
 
![SkiArise Responsive Design](readme-images/responsive.jpg)

# User Experience Design
The following features contribute to a good User Experience (UX):

## 1. Simple Structure and Intuitive Navigation
The website categorises information into 6 pages:
- **Homepage** - *includes key information about the company and their services*
- **All Packages page** - *lists all the package holidays offered (in alphabetical order)*
- **Info page** - *provides more information about their packages and ski package holidays in general*
- **Booking page** - *includes a form for booking a holiday with the company and leaving contact details for finalising details*
- **Enquiry page** - *includes a form for asking a question and leaving contact details (this feature is to encourage potential customers who are not yet ready to commit to buying a holiday to connect with the company)*
- **Success page** - *when a form is submitted, users are directed to this page to provide feedback that their form was submitted successfully*

Users can easily navigate to these pages through either the top navigation bar or through the contact section in the footer (which are both consistently shown on every page). 

There is also a link to the *About Us* section of the homepage from the top navigation bar.

In addition, there are sometimes links to specific sections of the *All Packages* and *Info* pages when it makes sense to link to these directly within the flow of the content.

## 2. Information Architecture

In addition to how the information is categorised on different pages, information is prioritised with the most important information appearing first.

For example:
- the ordering of items within the top navigation bar reflects the order in which users are likely to be looking for information
- the ordering of sections within the homepage (this is considered in detail in the [Homepage](#homepage) section)
- the keys explaining what icons mean are positioned at the top of the all-packages page

## 3. Interaction Design (IXD)

The website follows standard conventions to make it predictable and easy for users to interact with.

For example:
- the navigation bar is positioned at the top of the screen on every page of the website and is consistently presented on all pages
- the hamburger icon is used for revealing and collapsing navigation items on smaller devices
- contact information is found at the bottom of each page and is consistently presented on all pages
- links to external social media platforms are found in the contact section and are presented using the standard icons used by these platforms
- Call To Action (CTA) buttons are positioned in the most obvious places (the top navigation bar and *Contact Us* footer section) and when applicable within the normal flow of content

The website also provides users with feedback when they hover over buttons (with colour changes) or clickable navigation cards (by enlarging), or when they submit a form (by presenting the user with a success message and a link to return to the homepage).

Content hinting is used (i.e. showing the start of the next section just above the fold) so that users know to scroll down for more content. A good example of this can be seen with the start of the popular package section appearing just underneath the hero image / video on the homepage.

## 4. Accessibility

The website is made accessible for those using screen readers through the use of
- semantic HTML
- form labels and grouping similar elements using fieldsets
- alt text for images
- aria labels for icons

The responsive design makes the website accessible on different screen sizes and the use of relative units (rem) for font sizes (rather than fixed units like px) ensures that the fonts scale well with different zoom settings.

There is good colour contrast between text and background colours and a sans-serif font was chosen for body text to ensure that the text is easily readable for users.

## 5. Responsive Design

Wireframes were produced using Balsamiq at the earliest stages of planning to ensure that the website had a good layout on different devices.

***PUT WIREFRAME IMAGES HERE!!!***

## 6. Visual Design

### Media
Since the website was primarily seeking to attract customers to book a ski holiday, images were used extensively across the site showing people smiling in idyllic winter locations with vivid blue skies and pristine white snow. The hero video captures something of the beauty of the motion of skiing.

### Colour Palette
Colours were carefully selected to complement the images and for good visual contrast.

![Colour palette](readme-images/colour-palette.jpg)

### Typography

Fonts were chosen which gave a professional, modern and friendly impression of the company whilst being easy to read.

For headings, Montserrat (with a fallback to sans-serif) was chosen due to its bold design and its versatility with different font weights. This means it works well for both main section headings and smaller sub-headings, giving a consistency of styling across the whole site.

For the body text, Cabin (with a fallback to sans-serif) was used due to its high legibility and modern look.

The overlay text in the hero image used Merriweather since this was the closest match to the fonts used in the printed advertisements of the company (that appear in the photo of the shop window in the About Us section of the homepage).

![Publicity posters showing in the shop window](readme-images/shop-front.jpg)

### Brand logo

When designing the brand logo, papyrus font was used due to its smooth flowing style and rough edges, reminiscent of a ski slope. The capital "A" was edited (made thicker along the right edge) to look more like a mountain slope and the following "r" was replaced with an illustration of a skier roughly taking the posture of this letter.

![SkiArise brand logo](readme-images/brand-logo-black-bg.jpg)

### Icons

The website uses icons to show which slopes are available at a given resort and which packages the company recommends for different types of customers.

The icons were designed to be intuitive so that their meaning is immediately clear for the user but this key is shown at the top of the All Packages page to alert users to their purpose.

![Key for the icons shown at the top of the All Packages page](readme-images/icons-key.jpg)

The colours of these icons were chosen to enhance their meaning. For example, the beginners icon is green because they will want to access the easiest slopes (which are categorised in Europe by the colour green). Using different colours for each icon also makes it easier to spot when browsing the packages.

## 7. Performance

To ensure that the pages load quickly, all images used on the deployed website were converted to webp format (with jpg fallback) other than those requiring transparency (such as the brand logo and recommendation icons) which were scaled to appropriately sized png files.

A suitable compromise was reached between the resolution of the hero video and its file size to optimise performance.

# Features Overview

## Common Features

The following features are found on all pages of the website.

### Top Navigation bar

On larger screen sizes (laptop and desktop), the full navigation menu is shown.

![Navigation bar on larger screens](readme-images/nav-bar-full.jpg)

On smaller screen sizes (mobile and tablet devices), the navigation menu is hidden and a hamburger icon is shown instead. The menu can be expanded and collapsed by touching / clicking on the hamburger icon.

![Navigation bar on smaller screens](readme-images/nav-bar-collapsible.jpg)

The items are listed in the order of priority that the users are likely to want to visit them and the CTA button is also included here. Clicking on the brand logo provides an alternative method for navigating to the homepage - this may be preferred by mobile and tablet users who would otherwise have to expand the navigation menu.

The default behaviour of the Bootstrap Navbar is retained (i.e. the hover effects and the lighter font showing the active page).

***NOTE:** the **About Us** link navigates to a section on the homepage and therefore the navigation bar currently does not collapse automatically on smaller screens when navigating between the **Home** and **About Us** links. This is a bug with the bootstrap library and requires additional javascript to enforce the correct behaviour.*

### Contact Us Section

This section appears in the footer of every page of the website. It includes the primary CTA ("Book Your Holiday") button but also a secondary CTA ("Make An Enquiry") button. The second CTA button is to encourage users who are not yet ready to commit to buying a holiday to connect with the company.

![Contact Us footer section ](readme-images/contact-us-footer.jpg)

There are also links to the social media pages for the company which open in a new tab (to avoid taking users away from the main site). Since the company does not exist, these links currently just direct to the homepages of each website. The rel="noopener" attribute is used for increased security when navigating to these sites.

### Alternating background colours

On every page of the site, adjacent sections have a subtly different background colour.

![Adjacent sections on the Info page with different background colours](readme-images/alternating-backgrounds.jpg)

This makes it easier for the users to distinguish between different sections of the page as well as improving the aesthetics of the website.

## Homepage

### Hero section

To grab the attention of users when they first arrive at the site, they are presented with a short action video of people skiing which transforms into a hero image of an idyllic ski scene. The decision was made to bypass the video on smaller mobile devices and replace it with the hero image for a better experience for mobile users.

![Hero section shows a static image for mobile devices but a video for tablets and larger screens](readme-images/responsive-hero.jpg)

The overlay text includes the company logo and advertising slogan in similar formatting to how it appears on their printed advertisements.

### Popular Packages Section

This section was placed immediately after the hero section as it closely links with the primary purpose of the site (to showcase best products and gain new customers).

![Popular Package section on tablet screens](readme-images/popular-packages-section.jpg)

The section is highly responsive and the layout changes significantly on different screen sizes. The image above shows how it displays on tablet screens.

Headline details about selected packages are presented alongside buttons which take the user to specific sections of the **All Packages** page where further details can be found.

Images are used to increase emotional engagement. The 5 star ratings are included to increase the credibility of the business and gain the trust of potential customers. The recommendation icons assist users in quickly identifying which packages are most suitable for them.

***NOTE:** the decision was made to not include the icons key here to prevent the homepage from becoming too cluttered. At the point when users start looking more deeply at the website, they will come across the meanings of these icons both in the key at the top of the All Packages page and also in the relevant sections of the Learn More page. If they are using a laptop, they will also see descriptive titles appear when they hover over the icon.*

### Learn More Section

This section logically follows the previous section as it allows users to quickly find the information they are looking for.

![Learn More section on tablet screens](readme-images/learn-more-section.jpg)

Each card includes a key word and related image to grab the attention of the user. On hovering over the card, it expands slightly to indicate to the user that it is clickable. On touching / clicking on a card, the user is taken to the relevant section of the **Info** page.

This section makes navigating the site very streamlined and intuitive for the user and caters for the main user personas that were identified in the [**Project Planning**](project_planning.md) document.

### FAQs Section

This section logically follows on from the Learn More section and answers specific questions that potential customers may have.

The [**Project Planning**](project_planning.md) document identifies those who have never been on a ski holiday before as a target audience in the company's business strategy. This section is primarily aimed at this group.

![FAQ section with a narrow centralised container on larger screen sizes](readme-images/faq-section.jpg)


All answers are hidden by default which allows users to easily skip over this section if they wish. Answers are easily revealed by clicking on either the caret symbol (down arrow) or question text. 

When a different accordion item is opened, any previously opened items will close. This keeps the section tidy and uncluttered.

On larger screen sizes, the width of the container is made narrower than the default container size. This makes it easier for the user as it prevents the caret symbol from being too far away from the question text and is more aesthetically pleasing.

### About Us Section

One of the key business goals stated in the [**Project Planning**](project_planning.md) document is to *"Gain the trust of potential customers by demonstrating their legitimacy as a company, their knowledgability / contacts in the industry and their care for customers"*. This is therefore a key section of the website and why it can be accessed directly from the top navigation menu.

![About section](readme-images/about-section.jpg)

The section includes information which highlights their years of experience and contacts in the industry as well as showcasing the awards that the company has received.

Images of the team and the shop are included to further demonstrate the credibility of the business, increase the trust of potential customers and give them an emotional connection with the company.

### Testimonials Section

This section also seeks to increase the trust of potential customers and shows comments from happy customers rotating on a carousel.

![Testimonials section](readme-images/testimonials-section.jpg)

The navigation buttons remain hidden until the mouse hovers over the quote (or it is touched on a mobile or tablet device) to give the user control while keeping the section clean and visually appealing.

Testimonials from all of the key target groups are included (e.g. families, snowboarders, first-timers).

## All-Packages Page

This page allows users to browse all the package holidays that the company offers. Users arrive at this page either from the top navigation menu or from one of the buttons in the Popular Package section of the homepage.

At the top of the page, users see the main page heading with a supporting description so that they know where they are on the site and what to expect to find on this page. The icon keys are positioned immediately below this.

Information about each of the packages is summarised on a card. It includes further information about the resort and accommodation alongside supporting images.

![A card on the All Packages page as viewed on a laptop](readme-images/package-info-card-laptop.jpg)

A custom grid system was used here (rather than just using the regular Bootstrap grid system) to allow for greater control in the positioning of the "tick lists" on different screen sizes. On larger screens, these lists are positioned with the other text to the right of the images whereas on smaller screens they are positioned below the image.

![A card on the All Packages page as viewed on a tablet](readme-images/package-info-card-tablet.jpg)

## Info Page

This page provides users with more information about the packages and ski holidays in general. Users arrive at this page either from the top navigation menu or by clicking on one of the cards in the Learn More section of the homepage.

![The top of the Info page](readme-images/info-page.jpg)

The main purpose of the page is to engage the different types of users, give them confidence that their requirements are understood by the company and that the packages cater well for these requirements. It also reinforces the purpose of the recommendation icons.

## Booking Page

When users click on the primary CTA button ("Book Your Holiday") they are directed to this page. Here they can fill in a form to express interest in one of the packages. 

![The Booking page](readme-images/booking-page.jpg)

Rather than paying for the holiday at this stage, the form is intended to be the start of the process where users can outline any specific requirements or preferences they have so that the exact details can be later discussed with a member of the team and the package tailored to their requirements.

The form is organised into two general categories
- **Package Information** - for entering details about which package they want to get and any specific requirements / changes they would like to make
- **Contact Details** - for entering essential contact information, choosing their preferred method of communication and optionally opt-in to receive news of special offers.

The form inputs include validation. Assuming that all inputs pass these validation checks, the user is directed to the Success page on submission of the form.

Notice the changed appearance of the CTA button in the navigation bar (and footer). This is to show the user that the button has been disabled since they are already on the Booking page.

## Enquiry Page

When users click on the secondary CTA button ("Make An Enquiry") they are directed to this page. Here they can fill in a form leaving their question, contact details, preferred method of communication and optionally opt-in to receive news of special offers.

![The Enquiry page](readme-images/enquiry-page.jpg)

The purpose of this page is to encourage users who are reluctant to express interest in buying a holiday to connect with the company.

The form inputs include validation. Assuming that all inputs pass these validation checks, the user is directed to the Success page on submission of the form.

Notice the changed appearance of the "Make An Enquiry" button in the footer. This is to show the user that the button has been disabled since they are already on the Enquiry page.

## Success Page

On successful submission of one of the forms, the user is directed to the Success page. This reassures the user that their information has been sent successfully to the company.

![The Success page](readme-images/success-page.jpg)

There is a button to return to the homepage and the top navigation bar also works as normal for users who prefer this.

# Future Features

The following features could be added in the future:

## Javascript Functionality

The aim of this project was to build a static webpage. Therefore, only the javascript required for Bootstrap elements to function correctly was used in this project.

In the future, the following functionality could be added:
- the ability to search and filter packages on the All Packages page by categories (e.g. by price or recommendation icons)
- the ability to pre-populate the first select input (Resort Name) when users click on the "Book Your Holiday" button from within a particular package card
- a fix for the navigation bar not correctly collapsing for same-page navigation on smaller screens

## Error Page

An Error page could be added so that if a page is not found, the user has an option to return to safety (the homepage).

## Backend

In reality, a backend system would be needed to allow for
- form information to be sent via a POST request (currently the GET method is used to make it suitable for deploying with Github Pages)
- customer information to be stored in a secure database

This also allows for HTML to be generated dynamically from backend data (e.g. through Flask). This approach would make the code much more scalable and easier to maintain.

## Additional Content

It would be natural to show multiple images for each ski resort using a carousel. This was not done due to the time taken to generate suitable images but it would make for a better user experience.

The info page is lacking images in the **Beginners** and **Slopes** sections. These could be added to increase user engagement with these sections.

The company may decide to continue to expand their business strategy to target larger group bookings. Therefore, the remaining (could-have) User Stories could be implemented.

# Technologies Used

## Website Development

The website mainly uses **HTML**, **CSS** and **BootStrap Stylesheets** but also includes the default **Bootstrap Javascript** file to enable interactive elements (e.g. carousels).

Most of the code was written in a local copy of **Visual Studio Code** to take advantage of the *Live Preview* extension but **Gitpod** (a cloud based environment) was used in the early stages of development, and for sharing the code in mentor meetings and a tutoring session.

**Git** was used as the version control system and all commits were made to the main branch.

**Github** was used to host the Git repository and for deploying the website. **Github projects** was also used for planning and monitoring the development process.

The wireframes were produced using a local copy of **Balsamiq** (which was downloaded from <a href="https://balsamiq.com/" target="_blank" rel="noopener">**here**</a>).

## Image Generation and Design

Most of the images on the website were AI generated images using:
- **Stable Diffusion** (through <a href="https://github.com/ehristoforu/DeFooocus" target="_blank" rel="noopener">**DeFooocus**</a>) - used for most life-like images
- **Adobe Express** - for generating icons which were then manually edited

For further editing and design work, an open source image editor called <a href="https://www.gimp.org/" target="_blank" rel="noopener">**GIMP**</a> was used.

Images were optimised for the website by converting to webp format using the <a href="https://pixelied.com/convert" target="_blank" rel="noopener">**Pixelied**</a> website.

The favicons were produced using <a href="https://favicon.io/" target="_blank" rel="noopener">**favicon.io**</a> from a custom image.

## Video Editing

The hero video was edited from a longer video and an image (both taken from <a href="https://pixabay.com/" target="_blank" rel="noopener">**Pixabay**</a>) using the <a href="https://www.videosoftdev.com/" target="_blank" rel="noopener">**VSDC Video Editor**</a>. Some fade effects were added for smoother transitions and to give the impression of "waking up" (since the company slogan is "Wake up in your dream location").

## Textual Content

Much of the information included on the website is fictitious (including details of the company and accommodations).

I have never been on a ski holiday myself so **ChatGPT** was used to quickly generate information about ski holidays, resorts and the things that different users would want to learn about on the Info page. These responses were then manually edited to fit the context of the website. Since the website is primarily for demonstrating website design, this information was not checked thorougly for accuracy and therefore may contain some factual errors.

The fonts were sourced from <a href="https://fonts.google.com/" target="_blank" rel="noopener">**Google Fonts**</a> and textual icons were provided by <a href="https://fontawesome.com/" target="_blank" rel="noopener">**Font Awesome**</a>. 

# Testing

The deployed site was manually tested on various devices and web browsers to check that it is fully responsive and consistent in its appearance and functionality. These manual tests were conducted by myself and others.

Form data was checked using the Network Tab in Google Chrome's DevTools. When it was first deployed to Github Pages, an error occured on form submission due to using the POST method on the form. This was subsequently changed to the GET method so that it could be deployed in Github pages but in reality I would use a POST request to securely send data to a backend server.

The code was also checked using validators and the Lighthouse tool in Google Chrome's DevTools.

## Browser Testing

The following browsers were used during testing:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Apple Safari

The Safari testing revealed the need for using jpg fallback images since webp format was often not supported. These changes have since been implemented.

## Device testing

A number of different devices were used in testing:
- Laptops with different screen sizes
- Various generations of iPads (1st, 8th and 9th generations)
- Samsung Galaxy tablet
- Various Android phones
- Various iPhones (including a 1st generation iPhone 5)

A number of bugs were found on the first generation iPad and iPhone (but not for later generations). These involved:
- the hero video not playing (which left a blank white space)
- the carousel navigation behaviour on Safari web browsers (the iPhone did not respond at all and the iPhone had strange behaviour with the *Next* button)
- the scrolling behaviour was not accurate when following navigation links

The first of these bugs was fixed by changing the CSS media query for the hero image so that rather than hiding the image (display: none), it is displayed behind the video. A fade animation is used to prevent an initial flicker before the video starts playing and a -webkit prefix is used for compatability with older browsers.

The second bug was ignored as this is a bug related to the Bootstrap functionality and only affects very old devices. The carousels could still be navigated (on the 1st generation iPad) but only in the reverse direction.

The third bug was also ignored in favour of the modern CSS approach of using variables (which makes the code easier to maintain). It was judged to be a minor imperfection that affects only the oldest devices and therefore did not warrant changing.

## Code Validation

### CSS

When the custom stylesheet was tested using the <a href="https://jigsaw.w3.org/css-validator/" target="_blank" rel="noopener">**W3C CSS Jigsaw Validator**</a>, it initially raised errors about not recognising the font-optical-sizing property (since the validator was testing the code against the CSS Level 3 standards and the font-optical-sizing property was introduced in Level 4 - see <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/font-optical-sizing" target="_blank" rel="noopener">**here**</a>).

Once these font-optical-sizing statements were removed from the stylesheet, it passed the validation.

![CSS Validation Results from W3C CSS Jigsaw Validator](readme-images/css-validator.jpg)

### HTML

Each of the individual HTML pages were tested using the <a href="https://validator.w3.org/" target="_blank" rel="noopener">**W3C Markup Validator**</a>. Here is a summary of the results:

**index.html**
- **ERROR** - identified that a closing div tag was missing from the FAQ section. ***This was corrected***.
- **WARNING** - questioned whether aria-labels were being used correctly with divs containing five-stars reviews. ***No changes made***.
- **WARNING** - questioned whether articles (popular-package cards) were missing headings but h3 headings are in fact used in the header section of these cards. ***No changes made***.
- **WARNING** - identified sections which didn't contain a heading and suggested these be changed to divs. ***These were corrected***.

**all-packages.html**
- **ERROR** - identified **th** opening tags which were paired with **td** closing tags. ***These were corrected***.
- **WARNING** - questioned whether aria-labels were being used correctly with divs containing five-stars reviews. ***No changes made***.
- **WARNING** - identified sections within card footers which didn't contain a heading and suggested these be changed to divs. Although there is some common theme in the information contained, it was judged to be mainly a stylistic grouping. ***These were corrected***.
- **WARNING** - identified sections for packages which didn't contain a heading and suggested these be changed to divs. This was judged to be a valid use of the section element. ***No changed made***.
- **WARNING** - identified sections within the package cards which didn't contain a heading and were more for styling reasons and suggested these be changed to divs. ***These were corrected***.

**info.html**
- **ERROR** - identified stray end tags. ***These were removed***.
- *NO WARNINGS*

**booking.html**
- *NO ERRORS*
- **WARNING** - identified section without heading. On reflection, both the Booking Header section and Booking Form section are more for stylistic separation so were changed to divs.  ***Both sections changed to divs***.

**enquiry.html**
- *NO ERRORS*
- **WARNING** - identified section without heading. On reflection, both the Enquiry Header section and Enquiry Form section are more for stylistic separation so were changed to divs.  ***Both sections changed to divs***.

**section.html**
- *NO ERRORS*
- *NO WARNINGS*

Therefore, all html pages now pass the validation checks without errors.

## Lighthouse Analysis

The Lighthouse tool in Google Chrome's DevTools was used to analyse the homepage of the deployed site, both on mobile view and desktop view.

The results for the **mobile view** were as follows:

![Google Lighthouse analysis on mobile view](readme-images/lighthouse-mobile.jpg)

The results for the **desktop view** were as follows:

![Google Lighthouse analysis on desktop view](readme-images/lighthouse-desktop.jpg)


# Deployment

The website was deployed using Github Pages in the early stages of development to allow for testing on multiple devices.

The following steps were taken to deploy the website using Github Pages:
1. Within the Github repository, click on **Settings** in the top navigation bar
2. Choose **Pages** in the left navigation menu
3. In the Source section, choose **Deploy from a branch**
4. In the branch section, choose **main** (or whichever branch you wish to deploy) and click **Save**

![Steps to deploy the website](readme-images/deployment.jpg)

# Forking and Cloning

**Forking** refers to making a copy of the repository in your own Github account.

To fork this repository:
1. Log in to your Github account
2. Navigate to the repository page, click the caret (down arrow) next to the fork button and choose **Create a new fork**.

![Steps to fork the repository](readme-images/fork.jpg)

**Cloning** a repository refers to making a copy on your local machine and is typically done after forking.

To clone the repository (assuming you already have git installed on your machine):
1. Navigate to the repository page, click on the **Code** button, ensure the **HTTPS** tab is selected in the dropdown and copy the url
2. On your local machine, create the directory for the cloned repository
3. Open up a terminal window (e.g. **Git Bash** or **Command Prompt** on windows) and navigate to the new directory
4. Type **git clone [url]** (replacing [url] with the url address from step 1) and press Enter

![Steps to clone the repository](readme-images/clone.jpg)

# Credits

When writing the code for this project, the standard boiler-plate code (from the <a href="https://getbootstrap.com/docs/5.3/getting-started/introduction/" target="_blank" rel="noopener">**Bootstrap documentation**</a>) was usually used as a starting point when adding the various bootstrap elements.

<a href="https://stackoverflow.com/" target="_blank" rel="noopener">**Stack Overflow**</a> proved to be a useful source of information on a whole range of topics, such as *semantic HTML*, *flexbox styling*, and *compatability issues with Safari*. <a href="https://css-tricks.com/" target="_blank" rel="noopener">**CSS Tricks**</a> was another useful website for questions about styling and best practices when using webp images.

The photograph used in the Hero section of the homepage was provided by Andreas on Pixabay and can be found <a href="https://pixabay.com/photos/winter-ski-to-ski-ski-school-skier-4066634/" target="_blank" rel="noopener">**here**</a>.

The video used in the Hero section combined the above image with a video by Jorgelina Delmagro from Pixabay and can be found <a href="https://pixabay.com/videos/ski-snow-holiday-nature-sunset-186843/" target="_blank" rel="noopener">**here**</a>.

# Acknowledgments

This website was developed as part of the Code Institute Full Stack Development course and was submitted as my first portfolio project. I would like to thank my mentor <a href="https://www.linkedin.com/in/precious-ijege-908a00168/" target="_blank" rel="noopener">**Precious Ijege**</a> for his encouragement and advice, particularly for his recommendations in using a static hero image (rather than a video) on mobile devices to improve user experience.