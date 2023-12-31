# P1 - My Portfolio
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/e7581d64-d23a-4cd1-81d1-beea0aaba843)

## Visit the repository [here](https://github.com/Viridi-Machina/p1-my-portfolio) or view the live site [here](https://viridi-machina.github.io/p1-my-portfolio/)

## Summary
*My Portfolio* is a responsive personal resume designed for two primary user-types:
- Employers screening and looking to hire new developers
- Other developers looking for design inspiriation or looking for collaborative work

Users will be able to intuitively navigate a modern and tasteful landing page where they will find personal information, view a *showcase* project and efficiently contact the developer for enquiries. This site is designed as a personal portfolio for proffessional use that could be used as a template for those wanting full customisation when avoiding the use of a website builder.

## Author
Jacen Green

## Contents
<details>
 <summary>View Contents</summary>
 
- [P1 - My Portfolio](#p1---my-portfolio)
  * [Summary](#summary)
  * [Author](#author)
  * [Contents](#contents)
  * [UX](#ux)
    + [Target Audience](#target-audience)
    + [Project Goals](#project-goals)
    + [User Stories](#user-stories)
      - [Employer](#employer)
      - [Experienced Developer](#experienced-developer)
      - [New Developer](#new-developer)
    + [Owner Stories](#owner-stories)
  * [Design Choices](#design-choices)
    + [Colors](#colors)
    + [Typography](#typography)
    + [Imagery](#imagery)
    + [Animations and Transitions](#animations-and-transitions)
  * [Site Structure](#site-structure)
  * [Design Elements](#design-elements)
  * [Wireframes](#wireframes)
  * [Implemented Features](#implemented-features)
    + [Navigation](#navigation)
  * [Header](#header)
  * [Footer](#footer)
  * [Home Page](#home-page)
  * [Contact Page](#contact-page)
  * [404 Page](#404-page)
  * [Future Features](#future-features)
    + [Features not present](#features-not-present)
  * [Testing](#testing)
    + [CSS Validation](#css-validation)
    + [HTML Validation](#html-validation)
  * [Compatibility and Responsive Testing](#compatibility-and-responsive-testing)
  * [Manual Testing](#manual-testing)
  * [Defect Tracking](#defect-tracking)
  * [Defects of Note](#defects-of-note)
  * [Outstanding Defects](#outstanding-defects)
  * [Core Web Vitals](#core-web-vitals)
  * [Accessibility Testing](#accessibility-testing)
    + [Keyboard Navigation](#keyboard-navigation)
- [Technologies Used](#technologies-used)
  * [Languages](#languages)
  * [Frameworks, Libraries & Programs Used](#frameworks--libraries---programs-used)
- [Deployment](#deployment)
  * [Deploy to GitHub Pages](#deploy-to-github-pages)
  * [Forking The Repository](#forking-the-repository)
- [Credits](#credits)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)
</details>

## UX

### Target Audience
My Portfolio is targeted towards modern front-end developer employers who will likely use this to aid in their decision when recruiting, or by other developers looking for project partners in collaborative efforts.

Incidentally it could also be used by other front-end enthusiasts who might take inspiration for their own projects.

The style and general theme of the site is designed to be gender neutral, with aestheitics and interactions that provoke comfort and curiosity through colour and style.

### Project Goals
This site presents:
- A Home page with a summary of the author.
- A CV page which shows work history and skills obtained through past experience.
- A Contact page with a submission form that allows the selection of an enquiry type and a text-area for typing extra information regarding the enquiry.
- A Portfolio page which showcases completed projects.

All pages present a fixed header with a dropdown menu which expands into a traditional navigation bar on tablet screen sizes and above.
A footer at the bottom of each page offers links to the author's Github project portfolio, Linkedin profile and on larger screens there is also space for contact details.
For larger screen sizes, such as laptops and desktop monitors, hover and hover-transition effects have been implemented to further improve the user experience and provide clarity of action.
The site aims to be responsive for most common screen sizes and has been created with a mobile-first deisgn philosophy in mind.
 
The key goal of the site however is a proof-of-concept personal portfolio which will be branched from; it will be expanded upon and generally improved as the author learns more coding languages and unlocks new possibilities with regards to deisgn and interactivity.

### User Stories
#### Employer
- "As an employer, I need a developer that can quickly showcase their skills and abilites, so that I can make a more straightforward and confident decision when recruiting"

#### Experienced Developer
- "As a font-end developer, I want to collaborate and seek help with my own projects, so that I can meet my own goals / deadlines and increase my social circle"

#### New Developer
- "As an aspiring developer learning HTML and CSS, I want to find inspiration, so that I can further my own skillset and create my own projects"

### Owner Stories
- "As an aspiring developer, I want to showcase my work and portfolio in a way that gives me an edge over other possible candidates, so I have the best chance of getting my desired role"
- "As an aspiring developer, I want other developers to see my work and contact me, so that I may gain experience through collaborative efforts and increase my portfolio and social circle"

## Design Choices

### Colors
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/1e41ee34-d1e7-4ed1-ac10-de5866c4e44c)

The site uses a lot of texture in colour with backgrounds that cover each page, as well as blur-filters and transparency to highlight content - as a result it is difficult to select a definitive colour pallet. 
The pallet shown above however attempts to simplify the colour theme of the site; each page has a distinctive colour-theme with hue variations to indicate that the user is on a different page but still within the same site.

The home page is an exception; it contains beautiful background art which would be used to set the theme of the rest of the site. Solid colours were specifically ommited and gradients were used overall to make the site as intersting to look at as possible.
The desired effect is for uses of the site to feel comfortable and enjoy what they are looking at as they navigate the site, which in turn aims to improve user retention.

After researching into what colour format would work best, oklch was discovered as an effective tool for creating colours which are comfortable to look at while having the potential to adjust the true hue of a colour based on how the human eye sees colour. 
Therefore, after considering HSL format, oklch colour formatting would be used throughout this project. An article explaining the benefits of oklch can be found in this [link.](https://blog.logrocket.com/oklch-css-consistent-accessible-color-palettes/#:~:text=Understanding%20OKLCH%20syntax,-The%20oklch()&text=L%20%3A%20Lightness%20defines%20how%20close,with%20a%20more%20saturated%20color.)

### Typography
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/27540bbb-74f1-4901-8c13-25b9b5b16e29)

The chosen font, **'Figtree'**, is intended to provide a comfortable read for the user by providing clarity and removing unnecessary information. It is a sans-serif font with rounded features that aims to be accessible to all users, though specifically aimed towards demographics of the past two generations. 
It is supposed to look modern without being over-stylised. The font was obtained from [Google Fonts](https://fonts.google.com/specimen/Figtree?preview.text=This%20is%20a%20preview%20of%20the%20Figtree%20font)

Overall the same font is consistently used throughout the site. However, differences in use for different header and text elements are subject to text transformations and letter spacing.
For example the h1 element is capitalised as it was thought that the logo should be displayed as one would write their own name, whereas other header elements are uppercased to demand attention and spaced more for readibility.
Line height and letter spacing is used to provide distinctive difference between all text elements on different screen sizes, mainly for paragraph elements containing large ammounts of text.

<details>
 <summary>View example</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/dfa7693e-37b8-4518-a90f-6654ba32a752)
</details>

Originally, as the site is a developer portfolio, the desired font was intended to be similar to what may be used on IDEs - which explains the similarity to the font within this README.

### Imagery
<details>
 <summary>View drop-down menu (mobile)</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/dfe0acd8-d6cb-47cd-ba79-dc0412bb6132)
</details>

The above screenshot shows the drop-down navigation menu, in mobile format, with it's corresponding icons. 
Each fonticon was obtained from [fontawesome](https://fontawesome.com/) and is used to indicate further clarity to each option without having to read; when using the site after repeated use it becomes second nature to navigate the other pages.

The icon used in the top-right corner is used to toggle the drop-down menu. To reinforce the developer theme the '</>' icon would be another subtle hint towards this. 
Furthermore, the menu items were originally wrapped in '<>' brackets to indicate the active page. However there was difficulty with formatting and the idea was exchanged for a simple greater-than sign. 
<details>
 <summary>View form screenshot</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/b06f5148-cad7-42bc-ac84-75a7e2897fae)
</details>

The above images shows the bottom of the form on the contact page - reset and check-mark icons are used inplace of text. 
Although understandable that accessibility becomes a concern with icons alone it was a conscious choice to maintain this aesthetic for the form.
<details>
 <summary>View hero image (full-size)</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/49d6f105-76f4-4e6c-be6d-6fcec817993c)
</details>

Above is a full-size version of the hero image on the index page. The image in particular was chosen because of 3 core elements relatable to the author:
- The image is somewhat abstract in nature, and created with a geometric style that is favoured by the author.
- The colour palette in the image was what the author was looking for, and helped to define the colour pallette of the rest of the site.
- The naturalistic art style involving a mountain evokes feelings of liberation and beauty, and that one can do anything - relating to the author aspiring to be a developer and having ambition towards aesthetic design.
- Ultimately the image symbolises the characteristics of the author; the love for maths, graphic/computer design and to challenge oneself.

<details>
 <summary>View alternate hero image</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/6188fb52-612e-420f-afb0-9bb474566f22)
</details>

Lastly, the above image is the hero background used on all pages other than the home page. It has characteristics of the index page image but simplified for use as a texture so that it does not distract from the page content.
It retains elements of colour gradients and geometric styling so that it still remains consistent with the overlall theme. This image has a filter(hue-rotate) applied to it on the portfolio and contact pages to differentiate them by colour.

The hero images used as backgrounds across the site are intended to tell a visual story about the author, and what they can expect from them either in a career or collaborative role.

### Animations and Transitions
The contact page contains hover-states for a mouse cursor over any of the input fields (including radio buttons) to indicate what is an interractable element. A 1px border-colour similar to orange is used using oklch to contrast against the green-hue background.
Furthermore, a hover-transition is used as a pseudo-animation without the need for JavaScript; of which is used to highlight nav-bar elements, the interactable footer icons as well as the reset and submit form buttons.
Please see the embedded video below shich showcases this in effect:

https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/a3d5bc01-934b-49f3-817a-48294006ecce

## Site Structure
The site is split across 4 pages, and will load the home (about me) page by default.
Navigating to the other pages can be done via the dropdown navigation menu (on mobile-portrait view) or via the nav-bar displayed on tablet screens and larger.
Examples of these have been shown in images above.

## Design Elements
The kay interactive elements on the site can be broken down into the following:
- Dropdown nav-menu showing active page.
- Nav-bar showing active page with hover-transition effects on mouse cursor.
- Contact page form with inputs, interactable radio selection, text area, reset and submit buttons.
- Footer links with hover-transition effects on mouse cursor.
- Portfolio page video showcasing the entire site as a form of tutorial.

## Wireframes
Mobile-wireframe
<details>
 <summary>View mobile wireframe</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/88ae27ad-97e3-457e-bcde-7128b7bf4b9d)
</details>

Tablet-wireframe
<details>
 <summary>View tablet wireframe</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/db07b777-86e7-410e-9e58-6c5cd48c6cb9)
</details>

The wireframe used to sketch out the concept of the site was created via Balsamiq Wireframes. 
The screeenshots above show the general structure and desired elements of various pages at 2 screen sizes; mobile and tablet. 
Larger screen sizes would expand on the structure used to display the site on a tablet and scaled up for the most part.

## Implemented Features

### Navigation

## Header
<details>
 <summary>View mobile header</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/aed8def9-9fd1-43f8-bef3-4ac706f13117)
</details>

<details>
 <summary>View mobile header (collapsed)</summary>
 
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/48ff40c7-b720-47b9-ad25-d1d6e74560b6)
</details>

<details>
 <summary>View larger header</summary>

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/565450c2-4dfb-4319-936e-ad730e10d103)
</details>

- <strong>Fixed header:</strong> The site features a fixed header that remains in place when scrolling, so the user can always navigate to another page or back to the top.
- <strong>Drop-down menu:</strong> On mobile screens the site features a drop-down menu with icons and active-page styling to allow intuitive navigation of other pages using touchscreens.
- <strong>Nav-bar:</strong> On tablets and larger screens a fixed horizontal nav-bar shows all page links with icons and active-page styling. On even larger monitors the max-width of the nav-bar is fixed so that it doesn't stretch too much.

## Footer
<details>
 <summary>View mobile footer</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/df150f1b-47f2-4956-a790-64d3b9c96f35)
</details>

<details>
 <summary>View tablet footer</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/3628ecda-04d4-4820-957d-fbedf3ccfc39)
</details>

<details>
 <summary>View laptop footer</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/b466619a-1436-4217-8fbf-e59f166f17eb)
</details>

<strong>Responsive footer:</strong> The footer goes through 3 stages when increasing in screen size:
- Mobile: With less screen space a simplified footer only shows social network links with icons.
- Tablet: Contact details are added with between the icons.
- Laptop and larger: Contact details are given a divider, flexed into a horizontal row and re-ordered to before the icons.

## Home Page
<details>
 <summary>View home page content (mobile)</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/c2c6e1c1-b4aa-416a-85e9-3c6da007f8b2)
</details>

<details>
 <summary>View home page content (tablet)</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/64e0286c-fda6-46ad-b420-bf15de84b7bf)
</details>

<details>
 <summary>View home page content (laptop)</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/0da1e9c9-95fa-4549-9933-9d7f438f6304)
</details>

<strong>Responsive content:</strong> The text boxes go through 3 stages when increasing in screen size:
- Mobile: With less screen space the text box touches the edges of the screen.
- Tablet: Max-width is set.
- Laptop and larger: Higher max-width is set.

## Contact Page

<details>
 <summary>View CV page (mobile)</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/20cf1ca6-eb74-4b97-a7d7-66daff62f4f9)
</details>

<details>
 <summary>View CV page (tablet)</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/d0d26a81-4173-4082-9a2c-f65f56ac58f3)
</details>

<details>
 <summary>View CV page (laptop)</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/40e0f237-66ad-4d56-8c48-f23e27c47efd)
</details>

<strong>Responsive content:</strong> The text boxes go through 3 structural changes when increasing in screen size:
- Mobile: With less screen space the text box touches the edges of the screen and flows as a column.
- Tablet: Content is displayed in a grid layout.
- Laptop and larger: Left-hand content is fixed as a side-bar while the remaining content scrolls. Max-width and margins are also set to shift content into available space without disrupting the format.

## 404 Page

<details>
 <summary>View 404 error page</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/6542f254-244f-457d-abb1-514331950170)
</details>

## Future Features

- **Priority-low:** With the use of JavaScript this project will aim to have subtle animations that improve the overall style and user experience even further.
- **Priority-Medium:** A 'thank you' page in the same format and style as the site, which displays after successfully submitting a form.
- **Priority-Medium:** Form submission functionality that sends data to the author for analysis and response.
- **Priority-High:** Add to the portfolio page with multiple projects as the author's portfolio increases over time.
- **Priority-High:** Responsive video functionality to the portfolio page, where other projects will be displayed.

### Features not present
Due to the scope of the project, the portfolio page content was ommited from this site as it was dependent on the finished site before working on. 
With the large ammount of styling and bugs along the way not enough time was reserved to coomplete this.

## Testing

### CSS Validation

<details>
 <summary>View style.css validation</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/8f01fa61-cd4d-4972-8a4e-d7a47059d090)
 </details>

***!NOTE!*** the CSS file would actually pass with [this](https://jigsaw.w3.org/css-validator/) CSS validator. 
Upon inspection of the errors 33/33 of them are a result of colour formatting either using **oklch** values, or variables which contain **oklch** values.
Oklch is a browser-compatible with almost all browsers as shown below:
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/bd2559bb-e474-45cd-80e7-207167750088)
Furthermore, StatCounter also shows that a majority of people are using the latest browsers available:
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/6d47de12-4ea5-4453-bf02-d52daeef760d)
Lastly, **caniuse.com** also shows widespread use of the oklch colour platform.

As a result these validation errors will be ignored and the file will be considered a pass as it appears to works as intended.

### HTML Validation

All .html files pass file validation using the [Nu Html Checker](https://validator.w3.org/).

<details>
 <summary>View index.html validation</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/9d2acd39-1fc4-4df1-ad07-30a16d44e3c3)
</details>

<details>
 <summary>View portfolio.html validation</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/950afeef-f388-47b7-bc39-c17875f01563)
</details>

<details>
 <summary>View cv.html validation</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/448e02f2-7615-4f64-bd68-9230c430c99e)
</details>

<details>
 <summary>View contact.html validation</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/82481ab0-6efc-40c7-aadb-31b62adb6309)
</details>

<details>
 <summary>View 404.html validation</summary>
 
 ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/3ad5ecb1-853c-4ca6-b14b-d4ca8cca0e75)
</details>

## Compatibility and Responsive Testing

The site has been tested on a variety of screen sizes shown in the table below:

| TOOL / Device                   | BROWSER     | OS         | SCREEN WIDTH     |
|---------------------------------|-------------|------------|------------------|
| dev tools emulator: Galaxy fold | chrome      | android    | XS  280  x 653   |
| real phone: galaxy S20+         | chrome      | android    | M   360  x 800   |
| dev tools emulator: Pixel 7     | chrome      | android    | M   412  x 915   |
| dev tools emulator: iPad Mini   | chrome      | ios        | L   768  x 1024  |
| dev tools emulator: 'Laptop'    | chrome      | win11      | XL  1440 x 1335  |
| real monitor: desktop           | chrome      | win11      | XXL 2560 × 1440  |

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/691cb75b-2825-44e9-82f7-6bff9070b862)

The above image shows a graph from [statcounter.com](https://gs.statcounter.com/browser-market-share) of the most used browsers worldwide, which in this case is predominantly google chome. 
Ideally testing would be carried out over multiple operating systems, browsers as well as screen sizes however due to the short length of this project it was out of scope to complete a more thourough analysis.
As a compromise testing has been conducted only with the most used browser.

## Manual Testing

**Contact Form**
- [x] Go to the "Contact" page.
- [x] Try submitting the empty form and verify an error message appears for a missing name field.
- [x] Try to submit the form with an invalid email address and verify that a relevant error message appears.
- [x] Try to submit the form valid name and email fields and verify an error message appears for missing text.
- [x] Press the reset button to ensure the form refreshes.
- [x] Fill out the form fully and submit, verify a new tab opens to a codeinstitue form-dump page.

**404 Page**
- [x] Try adding a random character to the browser address window, verify that the 404 page displays.
- [x] Navigate back to the main site using the nav-bar, verify that it still functions as expected.

**Nav-bar**
- [x] In mobile format, try selectin the icon in the top right corner, verify it opens the drop-down menu.
- [x] When open, verify the current page is actively displayed in the nav-bar.
- [x] Press each of the links and repeat steps 1-2.
- [x] On a larger screen size such as a laptop, hover over each menu element and verify that it changes colour.
- [x] Click on each of the links and verify the current page is actively displayed in the navbar.

**Footer**
- [x] Click on the icons for github and linkedin, verify that they open in new tabs.

## Defect Tracking
- Background image for entire page not working as expected. **Resolved**
- Header position not sticking to top of page, interacting strangely with main content below when toggling nav-bar. **Resolved**
- Cannot align text and center radio buttons in contact form. **Resolved**

## Defects of Note
- **Creating a working background image for an entire page** - this was one of the first major hurdles that reuired hours of research, testing, trial and error to get right.
  Initially the plan was too ambitious and too much was attempted at the same time; originally the goal was to have a perspective scroll for the background image as it is a large portrait.
  Having to set the height was causing issues with the footer and generlaly ruining the flow of the whole page, if it even displayed correctly.
- **Fixing the position of the header and nav-bar** - 'position: fixed' was forgotton and thus casued major headache tring to figure out why the content was flowing a particular way.
  Again, hours spent troubleshooting only to realise one line of code would solve it.


## Outstanding Defects
- Index page contact me section - fonticons misaligned since adjusting font-size (need to be lowered)
- Profile image doesn't increase in size with screen width.
- Navbar on larger screens - although aligned with logo text it is still too close to the top of the page.
- Portfolio page missing main content
- CV page formatting needs work on larger screen sizes to reduce empty space.
- CV page work history text-padding needs increasing, and has slight overflow at bottom.

There are some minor fixes that would overall improve the detailing finess of the site, however the core functionality of the site - the home page and the contact page - remains in good form.

## Core Web Vitals

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/0857aef5-81b1-464a-ac91-895112e031c1)

The above screenshot was taken from [web.dev](https://web.dev/measure/) where the deployed site was entered for testing. The scoring was as follow:
- **Best Practices 100%**
- **SEO 100%**
- **Performance 94%** - The score here was reduced mainly because of the large image size used for the home page - however this is not something that can be compromised as it is an integral part of the page.
- **Accessability 89%** - This score is reduced because of apparent contrast issues with the white text over a dark background.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/580f735f-8292-49c9-81bf-68f2db462386)

The above image shows 2 key reasons why the score has been affected.
1. There is no label for the form element input-type: checkbox, but this is because the content contained must be a fonticon.
2. There are apparent contrast issues with the white text. In this case however, I believe that this hsa been flagged as a false-positive.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/00268972-3659-4709-ae50-cfffd3262cfa)

Using the Colour Contrast Analyzer linked on **web.dev** contrast accessabnility can be manually tested; using the dropper tool for colour selection on a variety of different background spots all yield the same result - minimum AA PASS.
The font size meets the minimum requirements for large text and even then it is difficult to find colour spots where the contrast ratio is near or below 4.5:1.
I believe that because the blur filter is being used and overlayed with a background colour (for contrast), the testing tool is having difficulty determining an accurate response and flagging all text as low contrast even though it can be clearly read.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/75e757f7-ca08-4c51-97d2-c00f87c6ba9b)

Note that the background has also been darkened further, but is still flagging the exact same issues.

## Accessibility Testing

### Keyboard Navigation
Care has been taken to ensure that keyboard functionality remains an option. For example, a decision was made to reduce the opacity of the radio bullets in the contact page rather than **display:none;** so that they could still be selected and navigated with the arrow keys.
Likewise the nav-bar has kept the nav-toggle bullet but with reduced opacity so that it is invisible yet functional.

https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/0e4cfc25-cc8c-4e5b-861a-a1dd1dcd861c

# Technologies Used

## Languages
- HTML5
- CSS3

## Frameworks, Libraries & Programs Used
- [Balsamiq](https://balsamiq.com/wireframes/) - A powerful tool for creating wireframes.
- [Coolors.co](https://coolors.co/) - Used to creat colour pallette for demonstration.
- [fontawesome](https://fontawesome.com/) - Large library with icons for almost anything.
- [google fonts](https://fonts.google.com/) - Vast array of chrome supported fonts that can be imported through the browser.
- [amiresponsive](https://ui.dev/amiresponsive) - Allows quick showcase of any site, with interactable screens.
- table of contents creator
- VSCode - Primary IDE.


# Deployment

## Deploy to GitHub Pages

1. To deploy a repository to GitHub Pages, first navigate to repository's main page.
2. Navigate to the settings button in the top nav-bar.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/716e6449-caf7-45c8-9148-53a41efeebf4)

3. Under 'Code and automation' navigate to 'Pages' in the left-hand side-bar.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/6496640f-4056-4b3c-b603-166a09c336ca)

4. Ensure that the 'Source' is set to 'Deploy from a branch', 'main' branch is selected and /(root) folder is selected. Hit save.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/184c61b2-8f92-43d1-a198-8e64447a6149)

5. Navigate back to <> Code, and on the right-hand side of the screen there should be a new 'deployments' section.
   Do note that this could take a few minutes for the repository to deploy.

   ![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/d4e25b5b-29be-48dc-8887-73efeaf3bba1)

7. Finally, cick on the 'Deployments' header and you can view your live site from any platform.

Write out steps you would take and test them to deploy your code to GitHub Pages, include screenshots if you think they would make the process easier.

## Forking The Repository

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/b6011d57-cc6f-4d54-8331-d2cc79ada78f)

To fork a repository you must not be the owner of it already. If you are looking at someone else's repo you will be able to navigate to the fork button indicated in the image above.

# Credits

- [StackOverflow](https://stackoverflow.com/) - Multiple issues over many threads have been explained from the help given on this site. It has proven to be an exceptional resource for troubleshooting and trying new ways of coding.
- [Kevin Powell](https://www.youtube.com/@KevinPowell) on youtube - Kevin's tutorials and genuine enthusiasm for coding with CSS specifically have helped tremendously with topics such as positioning and responsive deisgn.
- [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified) on youtube - Another content creator who walks-through and offers guides on many css topics of frustration, as well as general tips and tricks.
- [MDN](https://developer.mozilla.org/en-US/) - This site has proven essential throughout the learning process so far regarding html and css standards.

## Content
Some content has been taken from the Love running project to get started with the header, otherwise the rest of the code is my own work which I have spent nearly 5 weeks on to learn all the CSS skills put in place to complete this project.

## Media
- [Etsy Creator](https://www.etsy.com/uk/listing/1434066291/geometric-lake-and-mountain-3-digital?gpla=1&gao=1&&utm_source=google&utm_medium=cpc&utm_campaign=shopping_uk_en_gb_e-art_and_collectibles-prints-digital_prints&utm_custom1=_k_CjwKCAjwkY2qBhBDEiwAoQXK5YtFF5RTxpAGHCvKSo4PhYEXfdH-GG6y6nd_EiV-a7fY0t7YmXeDERoC_YwQAvD_BwE_k_&utm_content=go_12576524531_120383100700_507649705825_pla-328046931108_c__1434066291engb_102858184&utm_custom2=12576524531&gad_source=1&gclid=CjwKCAjwkY2qBhBDEiwAoQXK5YtFF5RTxpAGHCvKSo4PhYEXfdH-GG6y6nd_EiV-a7fY0t7YmXeDERoC_YwQAvD_BwE) - From whom I purchased the rights for using the artwork for the home page background.
- [Royalty Free site Pixabay](https://pixabay.com/illustrations/color-triangle-geometric-textured-2174049/) - Here the geometric background image for other pages in the site was found.

## Acknowledgments
- **Code Institute Love Running Project** - The Love Running Project was used as a backbone to get started with fundamentals such as the boilerplate code and some good practices to get a home page set up with a fixed header and footer at the bottom of the page.
