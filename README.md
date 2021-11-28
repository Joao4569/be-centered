# BeCentered

BeCentered is a site that hopes to provide useful information for centering one's body and mind to users. The site is aimed at users who are beginners, that are seeking methods to centre their body and mind, while also providing users in Zürich, Switzerland with an option to be able to get in touch with other like minded individuals by means of local social sessions.

The site will be useful by providing users with an introduction to various possible methods of acheiving their goals, by means of meaningfull informational text, images and videos as well as having a monthly schedule for users in the local area to meet up for weekly social sessions. There will also be an option to sign up to a monthly newsletter.

![Responsive Layout](/assets/images/responsive-layout.png)

## Conception

- I made use of [Balsamiq](https://balsamiq.com/) to create a wireframe concept for BeCentered.
- The main design of Becentered has changed as I progressed through the development towards a finished product.

### Home Page

- I decided that I preffered not having the introduction heading just say welcome and instead used the three pillars of Becentered as the heading, namely Balance, Mindfulness and Community. I also gave them the function of being internal links to the relevant sections in the tile display section.
- My original design only had the technique introductions displayed as tiles but after discussing my design with my mentor, he suggested adding the commnunity section to the tile dispaly as well, in order to give the page a more uniformed design. I found his input was correct.
- He also suggested having my overlay text on the hero image, positioned in the centre as in the wireframe design, but I decided that it would suite the chosen hero image better if it was placed on the right of the screen. He supported my decision once we had our mid-point consultation and I presented it to him.
- My final design does not include the heading for the footer section, I preffered the design without it and made it uniform throughout all the pages.

![be-centered-wireframe](/assets/wireframe/becentered.png)

### Technique Pages

- In the wireframe, each page had its own logo but I decided against it as I preffered making use of a unifrom logo across all the pages.
- My mentor and I were happy with the structure and design of the technique pages throughout the process and therefore left them unchanged in the final product.

![balance-wireframe](/assets/wireframe/balance.png)

![mindfulness-wireframe](/assets/wireframe/mindfulness.png)

### Sign Up Page

- The BeCentered sign up page has remainded largely unchanged, besides for how I chose to design the fieldsets on the form in the final product.

![sign-up-wireframe](/assets/wireframe/sign-up.png)

### Thank You Page

- The thank you page was not part of my original design.

## Features

### Existing Features

- __Navigation Bar__

  - Featured on all four pages, the fully responsive navigation bar includes links to the Home page, Balance page, Mindfulness page and the Sign Up page and is identical in each page to allow for easy navigation. The logo also acts as a link to the home page.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

![header](/assets/images/header.png)

- __The Landing Page Image__

  - The landing page includes a photograph as its Hero image with a text overlay containing a quote relevant to the theme of BeCentered. 
  - This section introduces the user to BeCentered with an eye catching animation to grab their attention.

![hero-image](/assets/images/hero-image-sample.png)

- __The Introduction Section__

  - The introduction section will introduce the user to the three pillars of BeCentered as its heading which also act as internal links to the relevant sections on the landing page.
  - This is useful to the user as it makes it easier to navigate to the relevant section of interest.
  - This also contains a short paragraph describing the owners vision and the sites purpose to users.

![introduction](/assets/images/introduction-section.png)

- __The Tile Display Section__

  - The tile display section introduces the user to various techniques of balance and mindfulness by means of images and short introductory paragraphs for each technique, under each main topic.

![tile-display-techniques](/assets/images/tile-display-techniques.png)

  - There is also a tile row relevant to users in the greater Zürich area who are interested in participating in social sessions.

![tile-display-community](/assets/images/tile-display-community.png)

  - Each tile row contains a link to more detailed information for each technique topic or to sign up for a monthly newsletter.
  - This is useful to the user as it makes it easier to navigate to the relevant page of interest.

![discover-balance-link](/assets/images/discover-balance-link.png)
![discover-mindfulness-link](/assets/images/discover-mindfulness-link.png)
![sign-up-link](/assets/images/sign-up-link.png)

- __The Group Sessions Section__

  - This section will allow the user to see exactly when the social sessions will happen, where they will be located and if there is a cost involved. 
  - This section will be updated monthly to keep the information relevant and useful to users.

![group-sessions](/assets/images/group-sessions.png)

- __The Footer__

  - The footer section includes links to social media pages for BeCentered, all links will open on a new tab to allow easy use for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media for regular useful information and discussions.

![footer](/assets/images/footer.png)

- __The Technique Pages__

  - BeCentered contains two technique pages, one dedicated to balance techniques and another dedicated to mindfulness techniques.
  - Each page contains two techniques relevant to the page topic, which contain a scrollable detailed description section.
    - Each detailed description includes long term benfits of the technique.
  - Each technique section also has a media section which contains a technique image and an embedded youtube video introduction to the technique.

![technique-page-section-sample](/assets/images/technique-page-section-sample.png)

  - At the end of the detailed technique description there is an emphasized link for the user to go to the sign up page in order to register for a monthly newsletter relevant to their individual interests.

![link-to-sign-up-page](/assets/images/link-to-newsletter-sign-up.png)

- __The Sign Up Page__

  - This page allows the user to register for a monthly newsletter.
  - The user can personalise the information that they sign up for by means of relevant checkboxes.

![link-to-sign-up-page](/assets/images/sign-up-page.png)

- __Thank You Page__

- This page thanks the user for registering to the newsletter.

![thank-you](/assets/images/thank-you.png)

### Features Left to Implement

- __Forum Page__

  - In future I would like to add a forum page for a live forum where users can register and take part in live conversations on related topics in order to add and share valuable information on being a more centered individual.

## Testing

- Found bug with navigation menu order, it is displaying in reverse order.
  - **Resolved** by researching information on [Web Developer Diary](http://nambiara.blogspot.com/2010/10/float-right-without-changing-order.html) and applying it to my design.
- Found that the Hero image did not cover entire screen width.
  - **Resolved** by using original image size instead of a re-sized image.
- Found that the tile display on the home page for the method introductions did not display as planned.
  - **Resolved** by adding additional div elements and floating their children as needed.
- Found solution for how to make an image fit it's parent element while retaining it's aspect ratio on [w3schools](https://www.w3schools.com/css/css3_object-fit.asp).
- Made use of background colors for testing of container structure, function and layout.
- Tested all internal links - All are functioning as intended.
- Tested all external links - All are functioning as intended.
- Tested all embedded videos - All are functioning as intended.
- Found an issue with the technique pages, the technique description conatiners were overflowing content.
  - **Resolved** by setting overflow to auto so that if the text needs to overflow then the content is still fully visible by means of scrolling and it will keep the design uniform across the two pages.
- Sourced most common media breakpoint widths on [www.freecodecamp.org](https://www.freecodecamp.org/news/css-media-queries-breakpoints-media-types-standard-resolutions-and-more/.) and made the site responsive down to minimum width of 320 pixels.
  - Mobile devices: 320px — 480px
  - iPads, Tablets: 481px — 768px
  - Small screens, laptops: 769px — 1024px
  - Desktops, large screens: 1025px — 1200px
  - Extra large screens, TV: 1201px and more
- Made use of Chrome developer tools for previewing and testing new designs for media queries as well as UX aspects.
- Found bug with loading first image to README.md, file path was incorrect.
  - **Resolved**, found error in file path.
- Found bug with the group sessions readme image link.
  - **Resolved** found error in file path.
- Tested all external links in the Readme.md file and all are working as intended.

### Validator Testing

- Made use of the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/) for the CSS file and the official [W3C validator](https://validator.w3.org/) for all HTML file testing.

#### Initial Validator Tests
- Initial validator test for index.html results:
  - 3 Bad Value errors for having spaces in image names.
    - **Resolved** by re-naming images accordingly.
  - 1 Warning for using an H1 tag incorrectly.
    - **Resolved** by replacing it with an unordered list for logical semantic structure.

- Initial validator test for balance.html results:
  - Found 4 errors referring to usage of height and width attributes in iframe tags with values of "100%".
    - **Resolved** by removing attributes and styling with CSS.
  - Found 2 warnings for the use of H1 tags.
    - **Resolved** by replacing with H2 tags for semantic structure.

- Initial validator test for minfulness.html results:
  - Found 4 errors referring to usage of height and width attributes in iframe tags with values of "100%".
    - **Resolved** by removing attributes and styling with CSS.
  - Found 2 warnings for the use of H1 tags.
    - **Resolved** by replacing with H2 tags for semantic.

- Initial validator test for sign-up.html results:
  - Found 1 warning for the use of H1 tags.
    - **Resolved** by replacing with H2 tags for semantic structure.

#### Final Validator tests

- Final validator test for index.html results:
  - 1 Warning for the introduction section not having a heading as it was wrapped in a nav element.
    - **Resolved** by removing the outer nav element as it served no other function.

- Final validator test for balance.html results:
  - No errors or warnings found.

- Final validator test for mindfulness.html results:
  - No errors or warnings found.

- Final validator test for sign-up.html results:
  - No errors or warnings found.

- Final validator test for style.css results:
  - file validates as CSS level 3 + SVG

- Final validator test for thank-you.html results:
  - No errors or warnings found.

- All the pages of BeCentered have passed their validator testing at the time of submission.

### Unfixed Bugs

- The only issue that I have with Becentered is that I feel some containers (for example the technique page headings, detailed descriptions and sign up page heading) are not fully responsive in relation to their content and that a lot of manual adjustments had to be made to assist their responsiveness concerning appearance over the various media queries.
- I started doing some research and I was looking into the issue for this project but unfortunately have not found a proper solution to the problem by the time of submission.

## Deployment

- BeCentered was deployed to GitHub pages, the steps were as follows:
  - While in the GitHub repository, select the settings tab.
  - Then select the Pages tab from the new menu to the left of the viewport.
  - From the source section drop down menu, select Main branch.
  - Once the main branch has been selected, the page will automatically refresh with a detailed ribbon display to indicate the successful deployment.

Here is the live link [BeCentered](https://joao4569.github.io/be-centered/)

## Deploymnet Testing

- Tested all internal and external links, form validation as well as responsivenes of Becentered on deployed site and all are working as intended.

## Credits

- First and foremost I would like to thank my mentor Anthony for his valuable input.

### Content

- Commit comment conventions were taken from [Cheatography](https://cheatography.com/albelop/cheat-sheets/conventional-commits/), I do not totally understand all the vernacular but tried my best to implement it as best I could.
- The font pairing chosen was taken from [Font Pair](https://www.fontpair.co/all).
- Navigation menu reverse order sequence solution found on [Web Developer Diary](http://nambiara.blogspot.com/2010/10/float-right-without-changing-order.html) modified for this application.
- Code for Hero image overlay text was taken from "Love Running" walkthrough project and modified for this application.
- Overlay quote on Hero image taken from [Quotefancy.com](https://quotefancy.com/quote/1488144/Rajneesh-Enjoyment-is-just-the-sound-of-being-centered).
- Introduction text sourced from [bodymindlife.com](https://www.bodymindlife.com/about) on their "Our Purpose" section.
- Tile display and technique pages text content sourced from [bodymind-training.ch](https://www.bodymind-training.ch/techniken/mind-balancing/)
- Method for coding group sessions timetable on home page taken from "Love Running" walkthrough project modified for this application..
- Social media icons sourced from [Font Awesome](https://fontawesome.com).
- Code for arranging social media icons in footer taken from "Love Running" walkthrough project modified for this application..
- Media queries for home page at a screen width less than 769px was taken from "Love Running" walkthrough project and modified accordingly.

### Media

- All images sourced from [Pexels](https://www.pexels.com).
- Hero image sizing suggestions sourced on [Hubspot](https://blog.hubspot.com/marketing/hero-image).
- Information for optimizing images for web design found on [jimdo](https://www.jimdo.com/blog/optimize-website-images-for-better-design-seo/).
- All images on Becentered were resized using [TinyPNG](https://tinypng.com/).
- Code for Hero image zoom animation taken directly from "Love Running" walkthrough project.
- Method for embedding Youtube video learnt on [GeeksforGeeks](https://www.geeksforgeeks.org/html-adding-youtube-videos/).
- Learn about object-fit CSS property on [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit).