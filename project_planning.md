# PROJECT PLANNING

## Personal Goals
In this first portfolio project I aim to demonstrate a strong grasp of HTML, CSS, and Bootstrap to develop a visually appealing static webpage that showcases my abilities to potential employers whilst meeting the assessment criteria for the project.

I hope to demonstrate proficiency in:
- PROJECT PLANNING - informed by business goals and user stories, prioritising features using must/should/could model 
- UX DESIGN - intuitive navigation, visually appealing, interaction feedback (e.g. hover buttons, form submissions etc.), responsive across different devices
- INDUSTRY BEST PRACTICES - SEO, accessibility (for screen readers etc.)
- TECHNICAL COMPETENCE - clean and  bug-free code utilising HTML, CSS, and Bootstrap

I intend to use this project as an opportunity to focus more explicitly on aspects related to project planning and monitoring (through the use of GitHub Projects), designing appropriate graphics (brand logo, icons, etc.) and in furthering my skills with the Bootstrap toolkit.

## Project Scenario

A (fictitious) company specializing in package ski / snow-boarding holidays wants a website to increase brand awareness and sales.

### Business Goals

The primary business goal is to:
- Increase the number of customers buying package holidays and therefore increase total revenue

Secondary business goals are to:
- Raise public awareness by presenting themselves as a reliable and professional company that delivers excellent package holidays at good prices
- Gain the trust of potential customers by demonstrating their legitimacy as a company, their knowledgability / contacts in the industry and their care for customers
- Showcase their most popular package deals and provide essential information about their packages to potential customers

The main Call to action (CTA) is:
- **Book Your Holiday** (a button leading to an online order form)

There will also be a **Make an Enquiry** button as a secondary CTA to encourage customers who are not yet ready to commit to buying a holiday to connect with the company.

---

### User Personas

The primary target audience for the website is potential customers who are looking for a ski holiday package.

These users may fall into one or more of the categories below. Each category of user has been assigned a priority rating in line with the companies business strategy
- first-time skiers **HIGH**
- experienced skiers (of differing abilities) **HIGH**
- families of different ages (including children) **HIGH**
- friendship groups (e.g. young adults, students) **MEDIUM**
- snowboarders **MEDIUM**
- organized groups (work, clubs, societies, school trips)  **LOW**

---

## Project Planning and Monitoring With GitHub Projects

*The information below is a copy of the User Stories, Acceptance Criteria, and Tasks that were added to the GitHub Project board during the planning stage. Each feature was assigned a label (must-have, should-have, could-have) to prioritise the different features and ensure they are completed in a timely manner.*

### User Story 1 (MUST HAVE)

As a potential customer, I want to find essential information about the packages on offer so that I can decide whether to book my next holiday with this company

**Acceptance criteria**
- Essential information (name of resort, location, dates, number of people, total price) about popular packages is visible from the homepage with links to further details about all packages
- Further details about all packages are listed in different sections on a separate "All Packages" page in alphabetical order 
- Each package description should include the essential information about the
  - **resort** - picture, name of resort, location, types of slopes / terrains, other distinguishing features and amenities (e.g. ski schools, cafes, restaurants, accessibility of ski lifts etc.)
  - **accommodation** - picture, type of accommodation (hotel, chalet, apartment), room options (single/double/family) and any other note-worthy amenities (wifi, hot tubs)
  - **package** - dates, duration, transport to and from the resort, number of people, total price, what else is included (e.g. lift passes, equipment rental, ski school, full/half-board)
- Each package description should use visual icons which allow users to quickly identify whether a package is suitable for them. These icons should be explained using a key and used consistently across the site to show at a glance:
  - resort information (types of slopes) - *capability to expand later if desired*
  - recommendations (for beginners, intermediates, and/or experts) - *capability to expand later if desired*
- All information about packages can be found easily by intuitive navigation through a top navigation bar and links from the Popular Packages section on the homepage
- The homepage and "All Packages" page are responsive on different devices

**Tasks**
- Use mobile-first responsive design principles with Bootstrap throughout the site to ensure clear presentation on multiple devices
- Design a navigation bar to be used on every page on the website which stays fixed at the top of the screen and includes the company logo (left) and a collapsible navigation menu (Home, All Packages, Info, About Us) to link to relevant parts of the site later
- Add a "popular-packages" section near the top of the homepage which includes the essential information about these packages (including images) on consistently sized cards
- Design the "All Packages" page which includes all the information (stated above) for at least 8 different packages - each package should be in its own section (so that it can be linked to later) and listed in alphabetical order
- Design / choose visual icons for quickly identifying packages which are most suitable for different types of customers, write a key at the top of the "All Packages" page and add each icon to the relevant packages
- Include a clearly visible "Find Out More" button on each Popular Package card on the homepage which links to the relevant section of the "All Packages" page
- Include a "Browse All" button near the top of the "popular-packages" section on the homepage which links to the top of the "All Packages" page
- Ensure that the "All Packages" navigation item links to the top of the "All Packages" page

### User Story 2 (MUST HAVE)
As a first-time customer, I want to find information about the company so that I can be sure that they are trustworthy and have a proven track record of delivering quality holidays

**Acceptance criteria**
- The home page includes information about the company including details about their wealth of experience and contacts within the industry alongside a photo of the team and any awards they have achieved
- The homepage includes testimonials from previous customers to further build the trust of potential customers

**Tasks**
- Add an "About Us" section to the homepage which includes information about the company, awards they have achieved and an image showing the team
- Ensure the relevant navigation item links to the "About Us" section
- Add a Testimonials section immediately beneath the "About Us" section of the homepage which shows comments (and names) of previous customers rotating on a carousel which users can also control through navigation buttons

### User Story 3
As a potential customer, I want to be able to contact the company so that I can make inquiries about packages and book my next holiday

**Acceptance criteria**
- Every page of the website includes contact information (including postal address, phone, email, social media links) and Call-To-Action buttons ("Book Your Holiday" and "Make An Enquiry")
- The main Call-To-Action button ("Book Your Holiday") is found easily on every page of the website and links to a form where users can indicate which holiday package they want to purchase and fill in their personal contact details 
- The "Make An Enquiry" button is present in the "Contact Us" section on every page and encourages customers who may not feel ready to commit to purchasing a holiday package yet to connect with the company
- The Booking Form should have the following:
  - **required fields**: which package, preferred starting date, preferred airport, number of children, number of adults, full name, full address, email, phone, preferred method of communication (dropdown)
  - **optional fields**: any special requirements (text area), best time for communication (text area)
  - **tick box**: opt-in for advertising
  - **SUBMIT**: "Send"
- The Enquiry Form should have the following:
  - **required fields**: message, phone, email, preferred method of communication (dropdown)
  - **tick box**: opt-in for advertising
  - **SUBMIT**: "Send"
- On submission of these forms, the user should be directed to a page showing a message which confirms that the information has been sent successfully with a link to return to the homepage

**Tasks**
- Design a "Contact Us" section to show the relevant contact information and add it to the footer section of every page of the website
- Design the "Booking" page which includes the fields described above
- Design the "Enquiry" page which includes the fields described above
- Design the "Success" page (shown when a form has been submitted) which includes a message confirming the information has been sent successfully alongside an obvious link back to the homepage
- Add a "Book Your Holiday" button to the "Contact Us" section and the top navigation bar which links to the Booking page
- Add a "Make an Enquiry" button to the "Contact Us" section which links to the Enquiry page
- Ensure that each form works as expected and presents clearly on different devices

### User Story 4 (SHOULD HAVE)
As a first time skier, I want to learn about what ski holidays are like so I can decide if this type of holiday is for me

**Acceptance criteria**
- The homepage includes a section for FAQs as well as images / videos showing skiers in idyllic locations to entice first-time customers.
- Further information about what to expect on a ski holiday and which packages are tailored for beginners is organised on another page and a link to this page is clearly signposted on the home page

**Tasks**
- Include a hero video (tablet and laptop) or hero image (phone) near the top of the homepage
- Add a Learn More section on the homepage which contains visual cards that link to the relevant section of the "Info" page which contains useful information for those who are unfamiliar with ski holidays
- Design the "Info" page and add a section containing information that is relevant and useful for beginners
- Add a "FAQ" section to the homepage which addresses some of the questions that beginners may have
- Include a testimonial from a beginner in the "Testimonials" section of the homepage
- Design / choose an icon for indicating whether particular packages are appropriate for beginners and include this icon in the icons key (at the top of the "All Packages" page) and when giving information about packages (on the homepage and the "All Packages" page)
- Find / create high quality images showing skiers in beautiful surroundings and incorporate across the website, especially when advertising packages and in the "Learn More" sections
- Ensure navigation links on all pages are updated (especially the Info item directing to the "Info" page)



### User Story 5 (SHOULD HAVE)
As an experienced skier, I want to find information about different resorts so I can decide whether the slopes are suitable for my ability

**Acceptance criteria**
- Further information about the types of slopes and how to identify packages recommended for experienced skiers is organised on the "Info" page and a link to this page is clearly signposted on the homepage
- Package information includes visual icons to show which slopes are available at that resort

**Tasks**
- Design / choose icons for showing the different types of slopes available at each resort
- Include a section on the "Info" page about the different types of slopes (green, blue, red and black) and which icons are used to quickly identify slope types and recommended packages for experienced skiers
- Add a visual card to the "Learn More" section of the homepage which links to the relevant section on the "Info" page
- The "All Packages" page contains the visual icons showing what slopes are available at each resort

### User Story 6 (SHOULD HAVE)
As a family with children, we want to find out which resorts/packages cater well for children so we can ensure that the whole family will enjoy the holiday

**Acceptance criteria**
- Information about which packages cater well for children is organised on another page and a link to this page is clearly signposted on the home page.
- This information will include details about accommodation, food, difficulty of slopes, availability during school holidays and any other facilities
- Information relevant to families is contained within the FAQ and Testimonials sections on the homepage

**Tasks**
- Add a section to the "Info" page which includes the information for families (specified above) ensuring that this section contains images that would appeal to different ages
- Add a visual card to the "Learn More" section on the homepage which links to the relevant section on the "Info" page
- Include at least one family-related question in the FAQ section of the homepage
- Include at least one positive testimonial describing how the trip was enjoyed by the whole family

### User Story 7 (COULD HAVE)
As a friendship group of young adults, we want to find out which resorts have a lively night life / cafe culture so that we can socialise with others and meet new people

**Acceptance criteria**
- Information about which resorts have the most active night life is shown on another page and a link to this page is clearly signposted on the home page
- Information relating to night life is contained within the FAQ and Testimonials sections on the homepage and a visual icon is included with package information for quickly identifying recommended packages

**Tasks**
- Design / choose an icon to use for indicating which packages are recommended for those seeking social activities and a good night life and add it to the key at the top of the "Info" page and with all relevant packages on the homepage and "All Packages" page
- Add a section to the "Info" page which includes information about the night life at different resorts and the icon used to quickly identify recommended packages. Ensure that this section contains images that would appeal to young adults
- Add a visual card to the "Learn More" section on the homepage which links to the relevant section on the "Info" page
- Include at least one question in the FAQ section of the homepage which relates to social activities off the slopes
- Include at least one positive testimonial describing the night life at a particular resort

### User Story 8 (COULD HAVE)
As a snowboarder, I want to find resorts that cater well for snowboarders as well as skiers so that I can choose the best resort for my next trip

**Acceptance criteria**
- A dedicated section on the "Info" page shows information about which resorts are especially well suited to snowboarding and a link to this section is clearly signposted on the home page
- Information on the "Info" page will include details about lift types, snowboard friendly slopes, terrain parks and half-pipes and the icon being used to highlight this information on the "All Packages" page
- The "All Packages" page includes the relevant icon to indicate if a resort is well suited for snowboarding along with further details about the snowboard-specific amenities available
- The homepage features at least one testimonial from a snowboarder which describes their positive experience snowboarding at a particular resort

**Tasks**
- Add Snowboarding section to the "Info" page which includes the information specified above.
- Add a card to the "Learn More" section of the home page with a title of "Snowboarding" and a visually appealing image of a person snowboarding. Ensure that it links to the Snowboarding section on the "Info" page.
- Design / choose an icon for showing which resorts are well suited for snowboarding and add to the key at the top of the "Info" page
- Include the icon with all relevant packages on the "All Packages" page and homepage
- Add a testimonial from a snowboarder to the other testimonials shown on the homepage

### User Story 9 (COULD HAVE)
As a group organiser, I want to see which resorts / packages can accommodate larger groups within the same hotel / accommodation so that we can all stay together

**Acceptance criteria:**
- Information about which resorts and hotels are able to accommodate larger groups is shown on another page and a link to this page is clearly signposted on the home page
- An icon for quickly identifying which packages are able to accommodate larger groups is added to all relevant packages

**Tasks**
- Design / choose an icon that can be used for quickly identifying which packages / resorts can accommodate larger group sizes and add it to the key (top of "Info" page) and all relevant packages (on homepage and "All Packages" page)
- Add a section to the "Info" page which includes information relevant to those organising larger groups
- Add a visual card for Group Organisers to the "Learn More" section on the homepage which links to the relevant section on the "Info" page

### User Story 10 (COULD HAVE)
As a group organiser, I want to know about safety protocols so that I can carry out a risk assessment effectively

**Acceptance criteria:**
- Information about where to find further information about issues relating to health and safety (such as risk assessments) is included in the most obvious section of the website

**Tasks**
- Add information about where risk assessments can be found for the different resorts alongside other health and safety information in the section relating to group organisers on the "Info" page