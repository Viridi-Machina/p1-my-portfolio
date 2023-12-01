### Cheatsheets and Auto Generation Tools

Markdown's not all that easy so sometimes you may want to use some tools to make tables. 

- [Markdown Cheatsheet](https://guides.github.com/features/mastering-markdown/)
- [markdown table generator](https://www.tablesgenerator.com/markdown_tables) - used to help with documentation table formatting
- [mardown table of contents generator](https://ecotrust-canada.github.io/markdown-toc/) - used to create table of contents (be weary it does have some bugs if you have dashes or trailing spaces in your headers)
- [readme.so](https://readme.so/) - if you don't want to learn markdown, this tool might help you


# Table of Contents
Copy your readme to http://ecotrust-canada.github.io/markdown-toc/ to make a table of contents.  This will help assessors to see the structure of your readme. Just test it out ast this tool isn't perfect. It tends to mess up with special characters like dashes.

====================================== The Sections you Fill in are below with some instructions ============================== -->

# P1 - My Portfolio

*My Portfolio* is a responsive personal resume designed for two primary user-types:
- Employers screening and looking to hire new developers
- Other developers looking for design inspiriation or looking for collaborative work

Users will be able to intuitively navigate a modern and tasteful landing page where they will find personal information, view a *showcase* project and efficiently contact the developer for enquiries. This site is designed as a personal portfolio for proffessional use that could be used as a template for those wanting full customisation when avoiding the use of a website builder.

  ![am-i-responsive-screenshot](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/56bfb37a-6b36-4eb7-b526-3a11c2d8bad6)

  - Repository for this project can be found via the following link: https://github.com/Viridi-Machina/p1-my-portfolio

  - Deployment of the live site can visited via the following link: https://viridi-machina.github.io/p1-my-portfolio/

## Author
Jacen Green

## Contents

Generate after readme is complete by copying and pasting your readme from this point & below into this tool:
- [mardown table of contents generator](https://ecotrust-canada.github.io/markdown-toc/)
**NOTE:** It does have some bugs if you have dashes or trailing spaces in your headers

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
Therefore, after considering HSL format, oklch colour formatting would be used throughout this project. An article explaining the benefits of oklch can be found in the following link:
https://blog.logrocket.com/oklch-css-consistent-accessible-color-palettes/#:~:text=Understanding%20OKLCH%20syntax,-The%20oklch()&text=L%20%3A%20Lightness%20defines%20how%20close,with%20a%20more%20saturated%20color.

### Typography
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/27540bbb-74f1-4901-8c13-25b9b5b16e29)

The chosen font, **'Figtree'**, is intended to provide a comfortable read for the user by providing clarity and removing unnecessary information. It is a sans-serif font with rounded features that aims to be accessible to all users, though specifically aimed towards demographics of the past two generations. 
It is supposed to look modern without being over-stylised. The font was obtained from Google Fonts at: [https://fonts.google.com/](https://fonts.google.com/specimen/Figtree?preview.text=This%20is%20a%20preview%20of%20the%20Figtree%20font)

Overall the same font is consistently used throughout the site. However, differences in use for different header and text elements are subject to text transformations and letter spacing.
For example the h1 element is capitalised as it was thought that the logo should be displayed as one would write their own name, whereas other header elements are uppercased to demand attention and spaced more for readibility.
Line height and letter spacing is used to provide distinctive difference between all text elements on different screen sizes, mainly for paragraph elements containing large ammounts of text.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/dfa7693e-37b8-4518-a90f-6654ba32a752)

Originally, as the site is a developer portfolio, the desired font was intended to be similar to what may be used on IDEs - which explains the similarity to the font within this README.

### Imagery
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/dfe0acd8-d6cb-47cd-ba79-dc0412bb6132)

The above screenshot shows the drop-down navigation menu, in mobile format, with it's corresponding icons. 
Each fonticon was obtained from https://fontawesome.com/ and is used to indicate further clarity to each option without having to read; when using the site after repeated use it becomes second nature to navigate the other pages.

The icon used in the top-right corner is used to toggle the drop-down menu. To reinforce the developer theme the '</>' icon would be another subtle hint towards this. 
Furthermore, the menu items were originally wrapped in '<>' brackets to indicate the active page. However there was difficulty with formatting and the idea was exchanged for a simple greater-than sign. 

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/b06f5148-cad7-42bc-ac84-75a7e2897fae)

The above images shows the bottom of the form on the contact page - reset and check-mark icons are used inplace of text. 
Although understandable that accessibility becomes a concern with icons alone it was a conscious choice to maintain this aesthetic for the form.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/49d6f105-76f4-4e6c-be6d-6fcec817993c)

Above is a full-size version of the hero image on the index page. The image in particular was chosen because of 3 core elements relatable to the author:
- The image is somewhat abstract in nature, and created with a geometric style that is favoured by the author.
- The colour palette in the image was what the author was looking for, and helped to define the colour pallette of the rest of the site.
- The naturalistic art style involving a mountain evokes feelings of liberation and beauty, and that one can do anything - relating to the author aspiring to be a developer and having ambition towards aesthetic design.
- Ultimately the image symbolises the characteristics of the author; the love for maths, graphic/computer design and to challenge oneself.

![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/6188fb52-612e-420f-afb0-9bb474566f22)

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
![image](https://github.com/Viridi-Machina/p1-my-portfolio/assets/146846939/88ae27ad-97e3-457e-bcde-7128b7bf4b9d)

The wireframe used to sketch out the concept of the site was created via Balsamiq Wireframes. The screeenshots above show the general structure and desired elements of various pages at 2 screen sizes; mobile and tablet. Larger screen sizes would expand on the structure used to display the site on a tablet and scaled up for the most part.

## mobile wireframes
🚀 **merit & beyond**

## tablet wireframes
🚀 **merit & beyond**

## desktop wireframes
🚀 **merit & beyond**

# Features
🚨**Required** 

In this section, you should go over the different parts of your project, and describe each in a sentence or so and how they tie into  your user stories.

## Implemented Features
🚨**Required** 

It's easiest to break this section down into the header, footer, and each page/layer/signification section of your website. Call out any differences for mobile vs desktop presentations, include a screenshot of the implemented feature.

Don't forget your 404 error page.

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

## Future Features
🚀 **merit & beyond**

Use this section to discuss plans for additional features to be implemented in the future

If you end up not developing some features you hoped to implement, you can include those in this section too.


## Testing
🚨**Required** 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the Features section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Validation Testing
🚨**Required** 

In this section you should write up any websites you used to validate your code and include screenshots.

**Validation issues are an automatic failure** You should run these about 3 times:
- when you first deploy your site
- just when you think you are done testing
- right before you submit because 😼, ⚽, 🐶 & 👼 can eliminate a closing tag or curly bracket without you noticing.

### CSS Validation
🚨**Required** 

If you only have one CSS file used on all pages, you only need to run this once for your deployed url, but if you have different files for different pages, run it by direct input per file.

- include a screenshot for each CSS file which includes the Green no ERRORS bar,  two check marks

[CSS validator](https://jigsaw.w3.org/css-validator/)

**styles.css**
![img.png](documentation/images/css-validation.png)

### HTML Validation
🚨**Required** 

If you only have one HTML file for your project, you only need to run this once for your deployed url, but if you have different files even for a thankyou or 404, run it by direct input per file or by deployed url per file.

- include a screenshot for each HTML file with the Blue Nu Html checker down to the blue checking complete bit. It's ok to have info and warnings. 
- You may need a scrolling screenshot to capture this one. I tend to use the [GoFullPage extension in chrome](https://chrome.google.com/webstore/detail/gofullpage-full-page-scre/fdpohaocaechififmbbbbbknoalclacl):

[HTML Validator](https://validator.w3.org/)

**index.html**
![img.png](documentation/images/index-html-validation.png)

**404.html**
![img.png](documentation/images/404-html-validation.png)

## Compatibility and Responsive Testing
🚨**Required** 

Minimally you should use dev tools and emulators to try to test you site on various screen sizes and browsers and note it in a table:

I ensured my site was worked well, and looked nice on a variety of devices & browsers as noted in the table below:

| TOOL / Device                 | BROWSER     | OS         | SCREEN WIDTH  |
|-------------------------------|-------------|------------|---------------|
| real phone: motog6            | chrome 78   | android 8  | XS 360 x 640  |
| browser stack: iPhone5s       | safari  13  | iOs        | XS 320 x 568  |
| dev tools emulator: pixel 2   | firefox  69 | android 8  | SM 411 x 731  |
| browserstack: iPhone 10x      | Chrome 78   | iOs 11     | SM 375 x 812  |
| browserstack: nexus 7 - vert  | Chrome 78   | android 7  | M 600 x 960   |
| real tablet: ipad mini - vert | safari  13  | iOs 6      | M 768 x 1024  |
| browserstack: nexus 7 - horiz | firefox 69  | android 7  | LG 960 x 600  |
| chrome emulator: ipad - horiz | safari 13   | iOs        | LG 1024 x 768 |
| browserstack windows PC       | Chrome 78   | windows 10 | XL 1920 x 946 |
| real computer: mac book pro   | safari 12.1 | Mohave     | XL 1400 x 766 |
| browserstack windows pc       | IE Edge 88  | windows 10 | XL 1920 x 964 |


🚀 **merit & beyond**
Document why you chose the devices:

1. Visit https://gs.statcounter.com/browser-market-share to figure out the most popular browsers & operating system combos seen across the web for the geographic region, and platform(s) and screen sizes you expect your users to belong to. 

2. Include a sentence about why you chose the combinations you did.

3. Create a table that lists out what devices, browsers, and operating system you tested your application on and a brief description of why you chose the mixture you did. The point is to prove that you looked at the site across various browsers, operating systems, and viewport breakpoints.

4. if you can't find the browser/device/OS combinations you want on Browserstack with your GitHub student webpack (or you didn't activate that in time), note what you'd ideally test on then what you ended up testing on as a compromise. 

5. Build a table to summarize the choices you made [markdown table generator](https://www.tablesgenerator.com/markdown_tables)

The combinations above were chosen because of the following information I gathered  from [ga.statcounter.com]( https://gs.statcounter.com/browser-market-share) for the US from Aug-Oct 2021:
**browser Version Market Share**:
  - safari iphone: 26.32%
  - chrome for android: 21.32%
  - Chrome 105.0: 15.77%
  - Chrome 104.0: 6.28%
  - Edge 105: 4.99%
  - Safari 15.6 3.76%
**browser Market Share**
  - chrome: 50.28%
  - Safari: 34.65%
  - Edge: 6.37%
  - Firefox: 3.52%
  - Samsung Internet: 2.04%
  - Opera: 0.89%
**platform breakdown**
  - mobile: 51.26%
  - desktop: 45.73%
  - tablet: 2.97%
  - console: 0.03%

## Manual Testing
🚨**Required** 

For any scenarios that have not been automated, test the user stories/features manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios in markdown such as:

**Manual Testing For Contact Form**
1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

Or you can use markdown check boxes and write them up per feature:

**Manual Testing For Contact Form**
- [x] try to submit 
- [x] Try to submit the empty form and verify that an error message about the required fields appears
- [x] Try to submit the form with an invalid email address and verify that a relevant error message appears
- [x] Try to submit the form with all inputs valid and verify that a success message appears.
- [x] no console errors
- [x] submit goes to code institute data dump page in new tab
- [x] looks good on mobile (one column)
- [x] looks good on tablet (two columns)
- [x] looks good on desktop (two columns but not SUPER HUGE)

Or you can use a spreadsheet
    
Here is a [Manual Testing Template](https://docs.google.com/spreadsheets/d/1vc1IVL-ydQwWeWMqnk_GRox6HE6qxDLpchGse8Crayo/edit#gid=296578096) that you can use as a starting point to keep track of your testing efforts. Make a copy of it in your own account and update as needed to reflect the browsers you are testing and features.  

It's ok to spot check specific functionality across devices and browsers but each page should be viewed as a whole for each device/browser combo at least once.

A quick way to check if items are exceeding the screen width of a project is to run this javascript in the console for various screen emulations:

```
var docWidth = document.documentElement.offsetWidth;
[].forEach.call(document.querySelectorAll('*'),function(el){if(el.offsetWidth > docWidth){console.log(el);}});
```

## Defect Tracking
🚨**Required** 

Try to create issues in real time as it better reflects the daily life of a developer.

The easiest way to track defects is by using GITHUB's Issues to track these as it's really easy to copy/paste screenshots in and then write up how you closed them. At this stage you don't need a custom template or labels, that comes in P4.

Here's a quick [overview of creating GitHub issues](Defects.md)

You can also just bullet point them here, or create a google spreadsheet and link to that here.

## Defects of Note
🚀 **merit & beyond**

Some defects are more pesky than others. Highlight 3-5 of the bugs that drove you the most nuts and link to them directly here. The accessors really like to know the struggle is real and that by doing this you picked up more skills.


## Outstanding Defects
🚨**Required** 

It's ok to not resolve all the defects you found as long as:
- it does not impact a user from completing a vital function on the website
- it only affects a very small subset of users
- is an extreme edge case that very few users would try
- there is an open issue against a framework, browser or technology used

If you know of something that isn't quite right, create an issue and link to it here and explain why you chose not to resolve it. 

Sometimes it's as simple, word wrapping issue that makes the site look odd at a certain screensize that you just didn't have time to fix due to the impending deadline it's best to mention it but note why you allowed it to go live: "Yes it looks odd, but it doesn't impact core functionality of the site." than to let the accessors think you didn't notice it. 

## Core Web Vitals
🚀 **merit & beyond**
SEO is greatly impacted by your core web vitals. The readout from https://web.dev/measure/ which is essentially a lighthouse audit gives your site scores in 4 categories. Ideally you want your site to be in the green for all 4 scores. web.dev has dedicated servers to test deployed sites without extensions that skew the results, so it's best to get results from this site.
 You should talk about the results for each section pay attention to 


## Accessibility Testing
🚨**Required** 

Accessibility testing is aimed to make sure that those with visual or physical disabilities can still browse your website. Some users have had strokes or accidents that make it difficult to use a mouse, so they use keyboard keys to tab through sites. Others use screen readers that rely on HTML tags to help the user navigate quickly through the site to find information they want, others have color blindness or contrast issues. It's the law to provide services 
Here's a [site](https://www.w3.org/WAI/fundamentals/accessibility-intro/#:~:text=Accessibility%20is%20Important%20for%20Individuals%2C%20Businesses%2C%20Society,-The%20Web%20is&text=That%20is%2C%20the%20accessibility%20barriers,older%20people) where you can learn more about accessibility and the internet.

### Accessibility Audits
🚨**Required** 

Accessibility audits run through the HTML and determine if the parts of the WCAG (web content accessibility guidelines ) that are implemented through HTML tags and attributes are present. They can do some checking for low vision/contrast stuff too.

You should run your deployed website pages through  at least on auditing tool. lighthouse's audit to check performance, accessibility, best practices and SEO scores. You should aim to get 85 or higher score on accessibility. 

**You should fix issues associated with:**
- contrast 
- aria labels
- alt text
- large images
- skewed images

**Lighthouse**
https://web.dev/measure/  If you have lower scores, read the report and follow the links to address the flagged issues. You can run this tool from Chrome Dev Tools too against your local machine, but chrome extensions can sometimes give you missing alt text on things like the grammarly plug in tracking pixel.

You want a score in the green for accessibility and should look at ways to get it to 100.



**[WAVE chrome](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh?hl=en-US) extension**
Wave is developed by webaim.org and does a bit better at contrast issues and uses 2.1 guidelines

**Contrast Checkers**
- https://webaim.org/resources/contrastchecker/
- https://color.a11y.com/

### Keyboard Navigation
🚀 **merit & beyond**

Another way to accessibility test your site is to try to click on the browser URL and see what happens if you use the tab, arrow and enter keys. Does it work well or does the user get stuck? Check this in a couple browsers as the focus & active outlines are typically styled by the browser

The expected results for various keyboard entries and field types can be found [here](https://webaim.org/techniques/keyboard/#testing)

You can take a video of this testing if you want and convert it to a gif and paste that into your readme. Record something to yourself in a Slack direct message, then download it. Then you can use https://cloudconvert.com/mp4-to-gif to convert the mp4 to a gif and just paste it into the readme via GiHu, and it'll resolve itself.


### Chrome Vox Reader
🚀 **merit & beyond**

If you are really ambitious, you can use the [VoxReader](https://chrome.google.com/webstore/detail/screen-reader/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en) extension in chrome to see what your site sounds like on a screen reader. It really drives home the need for good aria-labels & semantic HTML.

# Technologies Used
🚀 **merit & beyond**

This section just summarizers tools and programming languages you used.

## Languages
🚀 **merit & beyond**

-write bullet points for the languages you used (HTML & CSS)

## Frameworks, Libraries & Programs Used
🚀 **merit & beyond**

List out the tools you used with a link and a short description (this helps others figure out where to get the bonus points & reminds you what you used for your next project
- Balsamiq
- Coolors.co
- fontawesome
- gitpod
- github
- google fonts
- font awesome
- amiresponsive
- table of contents creator
- markdown table generator


# Deployment
🚨**Required** 

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages).

-Enumerate steps and use screenshots to make the instructions are clear.

You may want to re-watch the [initial deployment in gitpod video](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/9b06129195c64fada6783de9cfe82d60/) when writing up this section.

## Deploy to GitHub Pages
🚨**Required** 

Write out steps you would take and test them to deploy your code to GitHub Pages, include screenshots if you think they would make the process easier.

## Forking The Repository
🚀 **merit & beyond**

A fork creates a completely independent copy of Git repository. In contrast to a fork, a Git clone creates a linked copy that will continue to synchronize with the target repository, so if you want to ensure other people don't commit to your public repo, you might want to tell them to fork the repository :) 

## Run Locally With GitPod
🚀 **merit & beyond**

Enumerate and write the steps of how to run a project locally via gitPod. Include Screenshots to maximize the impact of the instructions.

# Credits
🚨**Required** 

To avoid plagiarism amd copyright infringement, you should mention any other projects, stackoverflow, videos, blogs, etc. that you used to gather imagery or ideas for your code even if you used it as a starting point and modified things. Giving credit to other people's efforts and ideas that saved you time acknowledges the hard work others did.  The accessors expect something here, there is no way you didn't have to get help on making such a nice project.

## Content
🚨**Required** 

Use bullet points to list out sites you copied text from and cross-reference where those show up on your site. If you truly are an expert in the content you provided, say that due to your exposure/experience of the topic covered, you created the content on your own.

## Media
🚨**Required** 

Make a list of sites you used images, icons & youtube, & audio files from. If you used several sites try to match up each image to the correct site. This includes attribution for icons if they came from font awesome or other sites, give them credit. If you took the images yourself, give yourself credit.

You should not be using images taken from copyrighted sites, but only royalty free ones. Try typing `!copyright` in slack and see what help it gives you for this topic.

## Acknowledgments
🚀 **merit & beyond**

This is the section where you refer to code examples, mentors, blogs, stack overflow answers and videos that helped you accomplish your end project. Even if it's an idea that you updated you should note the site and why it was important to your completed project.

If you used a CodeInstitute Example project as a starting point. Make note of that here.
