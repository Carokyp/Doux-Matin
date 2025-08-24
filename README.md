# Doux-Matin
<div align="center">
  <img width="710" height="430" alt="Image" src="https://github.com/user-attachments/assets/00d347c2-1490-4f1e-bef6-1a02a37768d7" /><br>
</div>

[Link to Live Website](https://carokyp.github.io/Doux-Matin/)

## About 
Doux Matin, which means 'Sweet Morning' in French, is a fictional brunch and coffee shop inspired by the charm of French cafés and bakeries. The shop serves freshly baked pastries, French-inspired brunch dishes, coffee, a variety of other drinks, and hosts bottomless brunches for special events.
Guests can enjoy their time in the cosy indoor seating area or on the rooftop terrace, perfect for relaxing, socialising, or celebrating special occasions.

## Index – Table of Contents
* [User Experience (UX)](#user-experience-ux)
   * [Strategy](#Strategy)
   * [Scope](#Scope)
   * [Skeleton](#Skeleton)
   * [Structure](#Structure)
   * [Surface](#Surface)

* [Features](#features)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Deployment](#deployment)
* [Credits](#credits)

## User Experience (UX)

### Strategy
The website is designed for residents, tourists, and groups of friends seeking great food, drinks, casual coffee breaks, or lively social gatherings in a relaxed setting. It will provide new visitors with all the essential information about the location, upcoming events, and menu offerings.

#### Business goals of the website are:
* Maximise table reservations.
* Encourage bookings for events (Bottomless Brunches, Birthdays, etc.)
* Increase the number of customers and grow customer loyalty.

#### The customer goals of this website are:
* A fast and easy way to book a table or reserve space for an event.
* Access to the full food and drinks menu.
* Find clear details about opening hours and location.
* Personalised and memorable experience.

#### User stories
* As a First-time visitor, I want easy navigation and a user-friendly design, including a responsive layout for my device, so that I can find information quickly and efficiently without frustration.
* As a customer, I want to see the food and drink options, so that I can decide what I’d like to order before I visit the place.
* As a customer, I want to book a table online using a simple booking inquiry form, so I can easily organise a group visit or a special occasion.
* As a customer, I need to find the location, contact details, social media, and opening hours clearly and concisely, so I can easily plan my visit or get in touch with the café.
* As a customer, I want to see images of the food and drinks, so I can decide if it’s the right atmosphere and suits my taste before visiting the place.
* As a customer, I want to access an about section, so I can learn more about the café, the products it offers, and the people behind the business.

#### MVP Roadmap (Minimal Viable Product)

<p align="center">
  <img width="663" height="465" alt="Image" src="https://github.com/user-attachments/assets/44bd155e-f263-411f-8ade-cd137fe34ec4" />
</p>

### Scope

The scope feature is kept simple. Below is a list of the leading features for this website.

#### In scope Features:
* Home page that shows the users what the website is about
* Two different menus that intuitively open a new page in the browser
* Booking page where users can easily reserve a table and include any special requests or notes with their reservation.
* Confirmation page that thanks users, informs them their reservation has been received, assures them someone will be in touch soon, and provides an option to return to the homepage.
* About page that provides users with the story of the business, details about the ingredients used, and an overview of the company’s mission.
* Provide information on:
    * Contacts
    * Location

#### Out of scope Features:
* **Integrate the newsletter sign-up form** The website contains a sign-up form for the shop newsletter. The sign-up form is placed in the footer on every page, allowing users to easily find it.
* **Testimonials and reviews from other customers** include a section dedicated to displaying customer testimonials and reviews. Testimonials are visible and presented in a format that is easy to read and navigate
* **Implementation of a “View Our Venue” Gallery** the section is available in the navigation bar. Contains a gallery showing photos of the environment, food and drinks and the Bottomless Brunch environment

### Structure
This website will be organised using a 3-tier hierarchical structure, providing a clear and logical navigation from main pages to sub-sections and detailed content. It will contain 5 pages in total (including the home page):

**Level 1 - Home page**

* A homepage with a hero image and a horizontal navigation menu will welcome users. This will lead to pages: Menu, Book Now, Contact and About 
* The homepage features a main section with a layout of images and a text block that highlights the type of food, ambience, and services visitors can expect. 
* Two menu buttons are also available on the main page, showing two different menus: brunch and bottomless brunch.
* To assist users, a map will be inset on the homepage so they can plan their visit
* The footer will contain contact information and social media links to support the website’s strategic objectives.

**Level 2 - Navigation Page**

* The navigation menu and footer will remain consistent across the Book Now, Contact, and About pages, but not on the Menu page, as this will open in a new browser tab.
* The Menu link will open a PDF in a new tab, displaying all available menu items.
* The Book Now link will take the user to a booking form, where all fields must be completed before the form can be submitted.
* The Contact link will navigate the user to the contact section at the bottom of the Home or About page.
* The About link will display detailed information about the business.

**Level 3 - Supporting Elements**

* After completing the Book Now form, the user will be taken to a Thank You page displaying a confirmation message and a “Return to Homepage” button, which redirects the user to the main page.
* The Google Map “View Large Map” option will open in a new tab, allowing the user to see a larger version of the map.
* The footer will include social media links that open the respective external social media pages. Since this website is based on a fictional coffee shop, the links will direct the user to the official main page of each social media platform.

### Skeleton
During this phase, wireframes for all pages were created using [Balsamiq](https://balsamiq.com/) (see samples below).

### Wireframes
The design considered both desktop and mobile users. The website’s responsiveness was built using Bootstrap’s breakpoints, ensuring layouts adapt smoothly across all devices: 
* Extra small (screens smaller than 576px)
* Small (screens 576px and larger)
* Medium (screens 768px and larger)
* Large (screens 992px and larger)
* Extra large (screens 1200px and larger)
* Extra extra large (screens 1400px and larger)

This approach ensures the website displays correctly and remains user-friendly on mobile devices, tablets, and desktop monitors.

This allows the website to display properly and remain user-friendly on all devices and desktop screens.

* __Home Page__  
  <p align="center">
    <img width="900" height="701" alt="Image" src="https://github.com/user-attachments/assets/61c4289d-c455-4a10-bd56-bac1198ae19c" />
  </p>

* __Book Now Page__  
  <p align="center">
    <img width="1019" height="431" alt="Image" src="https://github.com/user-attachments/assets/aec2b9bd-8095-450d-9dcd-b16de3a12ea9" />
  </p>

* __Thank You Page__  
  <p align="center">
    <img width="1032" height="365" alt="Image" src="https://github.com/user-attachments/assets/205c134f-21de-4a7a-aaa9-d1b724e61910" />
  </p>

* __About Page__  
  <p align="center">
    <img width="794" height="551" alt="Image" src="https://github.com/user-attachments/assets/97a1b310-11a8-4002-b9a5-751ac462cdbd" />
  </p>



### Surface

Considering that accessibility was a key design criterion, a consistent colour palette, readable fonts, and a clear layout have been used throughout the design of this website.

#### Visual Style

The visual style of Doux Matin is warm, inviting, and French-inspired, capturing the charm of a cosy café and bakery. The colour palette features soft, muted tones—creamy neutrals, and warm accent colours that create a relaxed and welcoming atmosphere. Photos were picked for their natural lighting and warm hues to highlight freshness, enhancing the overall ambience with a playful yet elegant tone.

#### Colors 
The colour palette was inspired by selections from [Color Hunt](https://colorhunt.co/) to evoke a rich chocolate brown for the depth of freshly baked treats, white for a smooth, fresh contrast, and the very light brown provides a soft, gentle backdrop that wraps the site in a cosy, inviting glow. Together, these tones create a comforting, café-inspired atmosphere.

<p align="center" >
  <img width="316" height="432" alt="Image" src="https://github.com/user-attachments/assets/8fdf5349-f084-4ef1-a9f0-807315b67ed4" />
</p>

#### Menus
The menu's design was created in Photoshop, inspired by mood boards and visual references gathered from [Pinterest](https://www.pinterest.com/). It reflects the overall visual style of Doux Matin, keeping the branding consistent and inviting. The design uses the rich chocolate brown from the website’s primary colour palette, paired with a clean white background and subtle light tones to ensure clarity and readability.

#### Typography

* **Pacifico** Google Font is featured in the hero section and larger headings. Its handwritten, playful style brings a warm and inviting charm, giving the site a distinctive and approachable personality.
* **Onest** Google Font is applied to navigation and body text. As a modern sans-serif font, it provides clarity, legibility, and a clean structure, ensuring smooth readability across all devices.

#### Images
The images used on the website were sourced from [Unsplash](https://unsplash.com/) for their high quality and copyright-free availability. To support accessibility, all images include descriptive alt text.

On the About page, images are optimised for responsive loading. For example, a larger 900px WebP image is served on screens wider than 768px, while a smaller 400px WebP version is used on mobile devices. This approach ensures that the appropriate image size is delivered based on the user’s device, improving both performance and visual quality.

All images are styled with Bootstrap classes to maintain responsiveness and consistent scaling across different screen sizes.

## Features
#### Navigation Bar
Each page features a consistent and responsive navigation bar that includes the following sections: Home, Menu, Book Now, Contact, and About. The navigation bar is sticky, meaning it remains visible at the top of the screen while the user scrolls down the page.

On larger screens, the navigation bar has a blurry background effect, giving it a sleek, modern appearance while maintaining readability over page content.

On smaller screens, the navigation transforms into a hamburger menu. When the user clicks the toggle button, a dropdown menu appears with the different sections displayed over a blurry background. Each time the toggle is clicked, the menu is also visually highlighted to enhance interactivity and user experience.

#### Hero image
Include a top-view photograph of a brunch with a text overlay of the name of the cafe

<img width="1142" height="573" alt="Image" src="https://github.com/user-attachments/assets/aaa50de3-cf13-4195-9a2a-00fd4214dfc7" />

#### Tagline
‘’Doux Matin where mornings unfold softly‘’ tagline appears on the main page below the hero image 
<div align="center">
  <img width="816" height="76" alt="Image" src="https://github.com/user-attachments/assets/8fdc3e58-1d3c-4e2b-93ab-d96baa6b8ca0" />
</div>


#### Home Page
The homepage contains two distinct sections:
* The first section allows users to view the brunch and breakfast menu, giving them a clear idea of the dishes offered.
* The second section provides more details about the bottomless brunches, including available times and pricing.
Both sections feature two images each to visually illustrate and enhance the content, giving users a warm and inviting preview of the experience.<br>

<div align="center">
  <img width="698" height="535" alt="Image" src="https://github.com/user-attachments/assets/6c3f680c-b6c0-45cf-91b1-1ee6354d7c95" />
</div>

#### Menu Page
The menu lists all the food and drinks available at the café. It is divided into multiple sections: Breakfast, Brunch, and Drinks, which include coffee, tea, fresh juices, and Bottomless Cocktails.
The menu opens in a new browser tab in a PDF format to allow users to browse the options without losing their place on the main website—making it easy to return to their booking or previous page at any time.

<div align="center">
  <img width="225" height="455" alt="Image" src="https://github.com/user-attachments/assets/53e00d30-7d81-4a8a-9064-240e6f231eff" />
    <img width="226" height="387" alt="Image" src="https://github.com/user-attachments/assets/69677eba-9878-439f-86bf-5fe5d66bf7bd" />
    <img width="224" height="254" alt="Image" src="https://github.com/user-attachments/assets/940b627e-5884-4edd-bd2f-d32391acad23" />
</div>

#### About us Page
The About Us page provides more details about who created and runs the business, as well as the team behind it. It also emphasises the café’s commitment to high-quality food and fresh ingredients.<br>

<div align="center">
  <img width="666" height="404" alt="Image" src="https://github.com/user-attachments/assets/cb9905b5-d211-42dc-8484-69fe1581582e" />
</div>

#### Booking Page
Users are asked to provide their first name, last name, email address, phone number, event type, number of guests, and the desired booking date. They also have the option to include a message for any additional information or special requests.

<div align="center">
<img width="859" height="508" alt="Image" src="https://github.com/user-attachments/assets/e5a04c07-76a3-45dd-a642-41e88e80a25f" /><br>
</div>

<br>Upon submitting the form, a new tab opens displaying a thank you message along with a button to return to the homepage.

<div align="center">
<img width="822" height="515" alt="Image" src="https://github.com/user-attachments/assets/24c77076-5511-46bc-bed5-1d8303729fbb" />
</div>


#### Footer

The footer is included on the Home, Book Now, Thank You, and About pages. Clicking on the Contact section in the navigation bar automatically scrolls the user down to the footer, where all contact information is located.

On the Home page, the footer contains:

* **Address:** Displays the café’s full address so users can easily locate it for visits or bookings.
* **Opening Hours:** Clearly states the days and times the café is open, helping users plan their visits or reservations.
* **Map:** An embedded Google Map shows the exact location of Doux Matin, making it convenient for users to get directions or view the area.
* **Phone Number** and Email Address: Provides direct contact options for users who may have inquiries, need help with bookings, or want to request more information.
* **Social Media Links:** Icons linking to major social media platforms (e.g., Instagram, Facebook, Twitter).
(Since Doux Matin is a fictional business, these links currently redirect to the main homepages of each respective platform.

On the other pages of the website (Book Now, Thank You, and About), the footer is simplified, only including the phone number, email address, and social media links.

This design ensures that essential contact methods are always accessible, while maintaining a clean and relevant interface that is tailored to each page’s purpose.

#### Meta Data

Metadata has been added to the website’s header section to support search engine visibility and improve traffic. Additionally, each page has been assigned a clear, descriptive title to help users understand their location within the site.

#### Future Features

* **A newsletter sign-up form** allows visitors to subscribe to updates, promotions, and special offers.
* **Reviews from other customers** showcase feedback from previous customers to build trust and credibility.
* **An image gallery** provides a visual gallery highlighting the café, events, food, and drinks to engage visitors and help them plan their visit.

## Technologies Used

__Languages Used__

* [CSS](https://en.wikipedia.org/wiki/CSS)
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [Bootstrap5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
* [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
* 
__Frameworks, Libraries & Programs Used__

* [Google Fonts](https://fonts.google.com/): was used to import the 'Pacifico' and 'Onest' fonts into the style.css 
* [Font Awesome](https://fontawesome.com/): was used to add icons for aesthetic and UX purposes.
* [GitHub](https://github.com/): is used as the repository for the project's code after being pushed from Git.
* [Photoshop](https://www.adobe.com/uk/products/photoshop.html): was used for early design to help having a better idea of wish color and image will suit the website it was also used to resize, eadit picture but also creating the menus and the color pallette
* [Visual Studio Git Source Control](https://learn.microsoft.com/en-us/visualstudio/version-control/git-with-visual-studio?view=vs-2022): was used to commit and push or pull those into GitHub 
* [Balsamiq](https://balsamiq.com/): was used to create the wireframes during the design process.
* [WAVE](https://wave.webaim.org/) & [Lighthouse](https://developer.chrome.com/docs/lighthouse) Used for accessibility testing to ensure that all content is readable and accessible to every user.
* [HTML Validator](https://validator.w3.org/#validate_by_input) Confirmed the HTML code is valid, with no errors detected.
* [CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) Verified the CSS code, with no errors detected.
* [JS-Beautify](https://beautifier.io/) Checked the formatting and structure of the HTML and CSS for consistency and readability.
* [Squoosh](https://squoosh.app) was used in this project to resize, compress, and optimise images for the web, ensuring they load quickly while maintaining visual quality

## Testing 

### Validator Testing 

[HTML Validator](https://validator.w3.org/)

Result for Home Page

<p align="center">
  <img width="743" height="68" alt="Image" src="https://github.com/user-attachments/assets/2442b72e-6501-476d-9c25-fcc50a55c131" />
</p>

Result for Booking Page

<p align="center">
  <img width="743" height="68" alt="Image" src="https://github.com/user-attachments/assets/2442b72e-6501-476d-9c25-fcc50a55c131" />
</p>

Result for Thank You Page

<p align="center">
  <img width="743" height="68" alt="Image" src="https://github.com/user-attachments/assets/2442b72e-6501-476d-9c25-fcc50a55c131" />
</p>

Result for About Page

<p align="center">
  <img width="743" height="68" alt="Image" src="https://github.com/user-attachments/assets/2442b72e-6501-476d-9c25-fcc50a55c131" />
</p>

Full validation results are available on GitHub here :
   * HTML Result - Home Page
   * HTML Result - Booking Page
   * HTML Result - Thank You Page
   * HTML Result - About Page

[CSS Validator](https://jigsaw.w3.org/css-validator/)

Result for style.css

<img width="682" height="92.5" alt="Image" src="https://github.com/user-attachments/assets/44dd7f0d-dfa3-4772-b494-dc10f5a5db05" /><br>

#### CSS Warnings

<img width="920" height="584" alt="Image" src="https://github.com/user-attachments/assets/6741dd4d-93ff-48b4-a667-5241c74ff7ed" /><br>

Full validation results are available on GitHub here :
   * [CSS Validation](https://github.com/Carokyp/Doux-Matin/blob/main/documentation/css-validation/css-validation-result.png)
   * [CSS Warning 1](https://github.com/Carokyp/Doux-Matin/blob/main/documentation/css-validation/css-warning-1.png)
   * [CSS Warning 2](https://github.com/Carokyp/Doux-Matin/blob/main/documentation/css-validation/css-warning2.png)

### CSS Validation Notes: 

During validation, some warnings appeared. These are not critical errors but expected outcomes when using modern CSS practices and ensuring cross-browser support:

**CSS Variables (--custom-variable)**
   * Warning: “Due to their dynamic nature, CSS variables are not statically checked.”

Explanation: This is normal. Validators cannot fully evaluate CSS variables, but they work correctly in modern browsers.


**Vendor Prefixes (-webkit-, -moz-, -ms-, -o-)**
   * Example: -webkit-backdrop-filter, -ms-flexbox, -o-object-fit, etc.

Explanation: These are vendor extensions included to ensure compatibility with older browsers. Validators flag them, but they are standard practice.

**Vendor Placeholder Styles**

   * Example: ::-webkit-input-placeholder, ::-moz-placeholder, :-ms-input-placeholder, ::-ms-input-placeholder

Explanation: These pseudo-classes/elements allow styling placeholders across different browsers. Again, validators flag them as non-standard, but they are necessary for consistent design.

**Autofill Styling**

   * Example: :-webkit-autofill, -webkit-text-fill-color

Explanation: Used to customise autofill input styles in WebKit browsers. These are valid but vendor-specific.

The warnings are expected and do not indicate invalid CSS. They mainly arise from using CSS variables and vendor-prefixed properties to maintain cross-browser compatibility.

**Browser Compatibility**

Testing has been carried out on the following browsers:

   * Google Chrome - Version 139.0.7258.67
   * Firefox - Version 141.0.3 
   * Microsoft Edge - Version 139.0.3405.86
   * Safari on macOS - Version 26.0, Copyright © 2003-2025 Apple Inc.

## Test Cases and Results

The website was thoroughly tested for functionality, usability, and responsiveness across multiple devices. 
Navigation links, interactive elements, forms, and content display correctly, with appropriate feedback for user input. 
The layout, images, buttons, and text remain visible and properly aligned on mobile, tablet, and desktop screens. All tests passed successfully, confirming a user-friendly and fully responsive website.

<img width="1375" height="652" alt="Image" src="https://github.com/user-attachments/assets/3e862090-fe4c-4343-b8f3-a423d23fb978" /><br>

Full results are available on GitHub here:
* [Test case 1](https://github.com/Carokyp/Doux-Matin/blob/main/documentation/test-case-and-result/test-case-1.png)
* [Test case 2](https://github.com/Carokyp/Doux-Matin/blob/main/documentation/test-case-and-result/test-case-2.png)

### Performance

Using Lighthouse within Chrome Developer Tools, each page of the website was evaluated for performance on both desktop and mobile devices. The results are summarised in the tables below. Testing identified a few recurring issues, including large image sizes, noticeable layout shifts, and the use of third-party cookies due to embedded Google Maps.

Images across the site have been optimised to reduce file size; however, the hero image on mobile devices is still flagged as relatively large, despite being under 500px, due to its visual prominence in the layout.

**First test on mobile**

<img width="1186" height="299" alt="Image" src="https://github.com/user-attachments/assets/855db379-5a51-478a-862b-c17bc50bc9c0" />

**After acting on the result of the first test**

<img width="1357" height="233" alt="Image" src="https://github.com/user-attachments/assets/3606e249-7626-4822-8f18-3cb95b343302" />

**First test on desktop**

<img width="1318" height="209" alt="Image" src="https://github.com/user-attachments/assets/17407284-7e2a-4dd6-b441-6ae2813d783b" />

**After acting on the result of the first test**

<img width="1353" height="248" alt="Image" src="https://github.com/user-attachments/assets/2c96ccb6-25e8-478c-9f02-07bccf2f1815" />

### Testing User Stories

User stories were tested to confirm that the website’s key goals have been achieved. A summary of the results is shown below.

**As a First-time visitor, I want easy navigation and a user-friendly design, including a responsive layout for my device, so that I can find information quickly and efficiently without frustration.**
   * All menus and links were tested on desktop, tablet, and mobile. Navigation is intuitive, links open correctly, and users can easily reach all pages.
   * The layout adjusts correctly across different screen sizes. Text, images, buttons, and input fields remain visible and do not overlap.

**As a customer, I want to see the food and drink options, so that I can decide what I’d like to order before I visit the place.**
   * Users can easily switch between different menus (Brunch & Bottomless). All items, prices, and descriptions are clearly visible and easy to read, and users can return to the main site easily.

**As a customer, I want to book a table online using a simple booking inquiry form, so I can easily organise a group visit or a special occasion.**
   * Customers can fill out the form with valid inputs to book a table. Required fields are validated, optional fields do not block submission, and successful submission redirects to a confirmation/Thank You page.

**As a customer, I need to find the location, contact details, social media, and opening hours clearly and concisely, so I can easily plan my visit or get in touch with the café.**
   * Customers can easily view the café’s location, contact details, social media links, and opening hours. All information is clearly displayed and accessible, helping users plan their visit or get in touch.

**As a customer, I want to access an About section, so I can learn more about the café, the products it offers, and the people behind the business.**
   * The About section provides customers with information about the café, its founder, the business’s objectives, and the quality of its products.

## Deployment

This project is hosted **on GitHub Pages**. Updates pushed to the main branch will automatically update the live site. **Please do not make changes directly to this repository**, since updates pushed to `main` will immediately update the live site. Use a fork or clone to make changes safely. Thank You!

1. Log into [my GitHub repository](https://github.com/Carokyp/Doux-Matin)
   
2. Click the "Settings" tab (top of the repository)
   
<div align="center">
<img width="661" height="68" alt="Image" src="https://github.com/user-attachments/assets/de5eca45-661b-42e5-8351-3aa99a6095cd" /><br>
</div>  

3. Click "Pages" from the left-hand side menu.
   
<div align="center">
<img width="635" height="262" alt="Image" src="https://github.com/user-attachments/assets/9a3a775f-4def-4ad1-a062-de6a37ef89be" /><br>
</div>

4. Under the source section, click the Branch dropdown, and switch the selection from ‘None’ to ‘Main’ and choose "/ (root)" folder
   
<div align="center">
<img width="556" height="275" alt="Image" src="https://github.com/user-attachments/assets/55aa0b35-8688-4eef-9cc6-bd82123b4ac6" />
</div>

5. Click "Save"
   
6. Wait 1-2 minutes for deployment, the site will be live at [https://carokyp.github.io/Doux-Matin](https://carokyp.github.io/Doux-Matin)

### Clone this repository

Cloning creates a local copy on your computer linked to the original repository. Any changes you push will be sent to the original repository, which will require approval.

#### Windows

1. Go to [this repository](https://github.com/Carokyp/Doux-Matin) on GitHub
2. Click Code, select HTTPS, and copy the link.

<div align="center">
<img width="542" height="264" alt="Image" src="https://github.com/user-attachments/assets/263a0239-080f-4d6f-8d5f-0db0600cde96" />
</div>
   
3. Open Git Bash.
4. Change the current working directory to the location where you want the cloned directory.
5. Type `git clone`, and then paste the URL you copied earlier.
6. `git clone https://github.com/Carokyp/Doux-Matin.git`
7. Press Enter to create your local clone.

#### Mac

Follow the same steps as Windows, but use Terminal instead of Git Bash.

1. Open Terminal
2. Change the current working directory to the location where you want the cloned directory.
3. Type `git clone`, and then paste the URL you copied earlier.
4. `git clone https://github.com/Carokyp/Doux-Matin.git`
5. Press Enter to create your local clone.

### Run a copy of this repository via Fork

Forking creates a separate copy of the repository under your own GitHub account.
	•	You can make changes freely.
	•	If the original repository is updated, GitHub will notify you, and you can pull updates into your fork.

__Create a new fork__  

1. First, set up Git [Download and install Git on your computer](https://git-scm.com/downloads)
   
2. Go to [Doux-Matin](https://github.com/Carokyp/Doux-Matin) repository
   
3. Click the 'Fork' button on the upper right part of the page.
   
   <div align="center">
     <img width="332" height="106" alt="Image" src="https://github.com/user-attachments/assets/d75c5ad2-f974-4a87-bd1c-f090fefea16b" />
   </div>

4. You now have a fork of the Doux-Matin repository in your GitHub account. Go to your profile, open the forked repository, and upload the required files.
   
5. Above the list of forked files, click the 'Code' button.

<div align="center">
  <img width="314" height="244" alt="Image" src="https://github.com/user-attachments/assets/907cfcb2-eced-4b9b-8d48-d827a2ea020d" />
</div>

6. A drop-down menu will appear. Select the one which applies to your setup. Further details on completing the final step can be found on [GitHub Fork Documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repository).

**Making Changes and Pushing Updates**

1. Create a new branch for your change
* `git checkout -b my-feature-branch`
1. Make your changes in your local repository.
2. Stage and commit your changes:
* `git add .`
* `git commit -m "Describe your changes here"`
3. Push your changes to your remote repository: \
* `git push origin my-feature-branch`

**Pull Request Fork**
1. Go to your fork on GitHub.
   
   <div align="center">
     <img width="812" height="216" alt="Image" src="https://github.com/user-attachments/assets/cb53c34c-4020-4a9e-986f-b3afdf56c605" />  
   </div>
   
2. You’ll see a message: “Compare & pull request”. Click it.
   
   <div align="center">
<img width="848" height="158" alt="Image" src="https://github.com/user-attachments/assets/8382e78a-f05a-4f50-91b5-511241a6fa4e" />
   </div>
   
3. Ensure the pull request is set to merge from your fork/branch → into the original repo/main (or another branch).
   
4. Add a clear title and description of what you changed.
   
   <div align="center">
       <img width="707" height="453" alt="Image" src="https://github.com/user-attachments/assets/35dcac5c-e2c9-4b69-8983-1fbcb1cb442c" />
   </div>
   
5. Click Create Pull Request.

**Pull Request Cloned repo**
1. Open a Pull Request on GitHub (same as above).
2. **Important:** If you cloned and have write access, you can push directly and open a Pull Request. If you cloned but don’t have write access, you must fork first.


## Credits

### Code References

Some parts of the project required utility scripts and styling tweaks. I adapted solutions from the following resources, modifying them to fit the project’s needs.

**Navbar Toggler (Mobile Highlight Removal)**

* Ensures the script only runs after the HTML has fully loaded [JavaScript-Tutorial](https://www.javascripttutorial.net/javascript-dom/javascript-domcontentloaded/)

* Uses a small delay with 'setTimeout' to wait for the collapse to complete before preventing the navbar toggler from staying focused (removes outline after click) [W3shools](https://www.w3schools.com/jsref/met_win_settimeout.asp) and [Stackoverflow](https://stackoverflow.com/questions/42935315/bootstrap-collapsed-menu-toggle-doesnt-un-focus-when-clicked-a-second-time?utm_source=chatgpt.com)

**Navbar Link Active State** 

* Keeps the clicked nav link underlined (active) while removing the style from other links [Stackoverflow](https://stackoverflow.com/questions/55499458/click-a-nav-item-add-a-class-remove-class-from-other-nav-items-vanilla-js)

* Underline effect design inspired by a CSS hover tutorial (adapted for active state, not hover) [ByteGrad YouTube Channel](https://www.youtube.com/watch?v=0uZ_ZnlEJ68)

**Hamburger Icon Customisation**

* Script for changing the Bootstrap hamburger icon colour on mobile
[Stackoverflow](https://stackoverflow.com/questions/42586729/how-can-i-change-the-bootstrap-4-navbar-button-icon-color)

**Disable past dates on datepicker**

* Prevents users from selecting dates earlier than today in the reservation form [Stackoverflow](https://stackoverflow.com/questions/15757918/disable-past-dates-on-datepicker/78561570#78561570)

### Images

__Home page__ 

* Hero Brunch Image: https://unsplash.com/fr/photos/pain-tranche-sur-plaque-de-ceramique-blanche-7N8amvEYF-0 \
Artiste: Colin Michel \
Artiste Profil: https://unsplash.com/fr/@colincyruz

* French Toast: https://emmaduckworthbakes.com/brioche-french-toast/ \
Website: Emma Duckworth Bakes

* Croissants: https://en.julskitchen.com/breakfast/italian-croissants \
Artiste: https://www.instagram.com/julskitchen/ and https://www.instagram.com/tommyonweb/

* People enjoying a meal: https://www.restomontreal.ca/article/mimosas-music-and-brunch-vibes-montreals-top-weekend-picks/2101/en/ \
Website: Restomontreal

* Mimosa and brunch: https://www.restomontreal.ca/article/mimosas-music-and-brunch-vibes-montreals-top-weekend-picks/2101/en/ \
Website: Restomontreal

__Menus__ 

* Lemon Crepe: https://unsplash.com/fr/photos/photographie-a-plat-de-crepe-avec-glacage-jsgJtBOR6jY \
Artiste: Monika Grabkowska \
Artiste Profil: https://unsplash.com/fr/@moniqa

* Coffee: https://unsplash.com/fr/photos/tasse-de-cafe-sur-soucoupe-avec-cuillere-a-cafe-sur-table-rose-X2s8GhnQmds \
Artiste: Natanja Grün \
Artiste Profil: https://unsplash.com/fr/@natanja

* Waffles: https://muttenzer-pizzeria.ch/indulge-in-delicious-creations/ \
Website: Muttenzer

* Egg Burger: https://www.instagram.com/p/CjQyXuQPOMu/ \
Restaurant: Melba Lunn Ave 

__Menu Bottomless Brunch__

* Lemon Cocktail: https://www.liquor.com/lynchburg-lemonade-cocktail-recipe-5199408 \
Website: Liquor.com / Tim Nusog

* Orange Cocktail: (https://unsplash.com/photos/a-colorful-cocktail-garnished-with-a-flower-vfQ-TCKwlC4) \
Artiste: alexanderafan \
Artiste Profil: https://unsplash.com/@alexanderafan

__About Page__

* Porridge Brunch: https://unsplash.com/fr/photos/fruit-salad-on-gray-bowls-HlNcigvUi4Q \
Artiste: Brooke Lark \
Artiste Profil: https://unsplash.com/fr/@brookelark

* Croissants: https://unsplash.com/fr/photos/fourchette-en-acier-inoxydable-sur-plaque-en-ceramique-blanche-hU2ieCpAoDI \
Artiste: montatip lilitsanong \
Artiste Profil: https://unsplash.com/fr/@montatip

* Flour and Eggs: https://unsplash.com/fr/photos/oeufs-et-farine-5evEHNh-Ft4 \
Artiste: Wendy Rake \
Artiste Profil: https://unsplash.com/fr/@wendyrake

### Inspiration

[Allo Mon Coco](https://allomoncoco.com/) The content on the About page and the Hero image layout were the main sources of visual and stylistic inspiration for this project.
