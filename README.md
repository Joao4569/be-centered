# BeCentered

BeCentered is a site that hopes to provide useful information for centering one's body and mind. The site is aimed at users who are beginners, that are seeking methods to centre their body and mind, while also providing users in Zürich, Switzerland with an option to be able to get in touch with other like minded individuals.

The site will be useful by providing users with an introduction to various possible methods of acheiving their goals by means of valuable informational text and videos as well as having a monthly updated schedule for users in the local area to meet up for weekly group sessions. There will also be an option to sign up to a monthly mailing list.

![Responsive Layout](/assets/images/responsive-layout.png)

## Features

### Existing Features

- __Navigation Bar__

  - Featured on all four pages, the fully responsive navigation bar includes links to the Home page, BeBalanced page, BeMindful page and the Sign Up page and is identical in each page to allow for easy navigation. The logo also acts as a link to the home page.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

![header](/assets/images/header.png)

- __The Landing Page Image__

  - The landing page includes a photograph as its Hero image with a text overlay containing a quote relevant to the theme of BeCentered. 
  - This section introduces the user to BeCentered with an eye catching animation to grab their attention.

![hero-image](/assets/images/hero-image-sample.png)

- __The Introduction Section__

  - The introduction section will introduce the user to the three pillars of BeCentered as its heading which also act as internal links to the relevant sections on the landing page. 
  - This also contains a short paragraph describing the owners vision and the sites purpose to users.

![introduction](/assets/images/introduction-section.png)

- __The Tile Display Section__

  - The tile display section introduces the user to various techniques of balance and mindfulness by means of images and short introductory paragraphs.

![tile-display-techniques](/assets/images/tile-display-techniques.png)

  - There is also an introductory paragraph and image relevant to users in the greater Zürich area who are interested in participating in social sessions.

![tile-display-community](/assets/images/tile-display-community.png)

  - Each tile row contains a link to more detailed information on each technique or to sign up for a newsletter.

- __The Group Sessions Section__

  - This section will allow the user to see exactly when the social sessions will happen, where they will be located and if there is a cost involved. 
  - This section will be updated monthly to keep the user up to date.

![group-sessions](/assets/images/group-sessions.png)

- __The Footer__

  - The footer section includes links to the relevant social media pages for BeCentered, all links will open on a new tab to allow easy of use for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media.

![footer](/assets/images/footer.png)

- __The Technique Pages__

  - BeCentered contains two technique pages, one dedicated to balance techniques and another dedicated to mindfulness techniques.
  - Each page contains two techniques relevant to the page topic, which contain a scrollable detailed description section.
    - Each detailed description includes long term benfits of the technique as well as an emphasized link at the end for the user to go to the sign up page in order to register for a monthly newsletter relevant to their individual interests.



## Testing

- Found bug with navigation menu order, it is displaying in reverse order - **Resolved** by researching information on [Web Developer Diary](http://nambiara.blogspot.com/2010/10/float-right-without-changing-order.html).
- Found that the Hero image did not cover entire screen width - **Resolved** by using original image size instead of re-sized image.
- Found that the tile display for the method introductions did not display as planned - **Resolved** by adding additional div elements and floating their children as needed.
- Found solution for how to make an image fit it's parent element while retaining it's aspect ratio on [w3schools](https://www.w3schools.com/css/css3_object-fit.asp).
- Made use of background colors for testing of container structure, function and layout.
- Tested all internal links - All are functioning as intended.
- Tested all embedded videos - All are functioning as intended.
- Found an issue with technique pages, technique description divs were overflowing content - **Resolved** by setting overflow to auto so that if the text needs to overflow then the content is still fully visible by means of scrolling.
- Sourced most common media breakpoint widths on [www.freecodecamp.org](https://www.freecodecamp.org/news/css-media-queries-breakpoints-media-types-standard-resolutions-and-more/.)
  - Mobile devices: 320px — 480px
  - iPads, Tablets: 481px — 768px
  - Small screens, laptops: 769px — 1024px
  - Desktops, large screens: 1025px — 1200px
  - Extra large screens, TV: 1201px and more
- Used Google dev tools for previewing and testing new concepts for media query design as well as UX aspects.
- Found bug with loading first image to README.md, file path incorrect - **Resolved**, found error in file path.
- Found bug with the group sessions readme image link - **Resolved** found error in file path.

### Validator Testing

- Initial validator test for index.html results:
  - 3 Bad Value errors for having spaces in image names - **Resolved** by re-naming images accordingly.
  - 1 Warning for using an H1 tag incorrectly - **Resolved** by replacing it with an unordered list.

- Initial validator test for be-balanced.html results:
  - Found 4 errors referring to usage of height and width attributes in iframe tags with values of "100%" - **Resolved** by removing attributes and styling with CSS.
  - Found 2 warnings for the use of H1 tags - **Resolved** by replacing with H2 tags and styling accordingly.

- Initial validator test for be-mindful.html results:
  - Found 4 errors referring to usage of height and width attributes in iframe tags with values of "100%" - **Resolved** by removing attributes and styling with CSS.
  - Found 2 warnings for the use of H1 tags - **Resolved** by replacing with H2 tags and styling accordingly.

- Initial validator test for sign-up.html results:
  - Found 1 warning for the use of H1 tags - **Resolved** by replacing with H2 tags and styling accordingly.

### Unfixed Bugs

## Deployment

## Credits

### Content

- The font pairing chosen was taken from [Font Pair](https://www.fontpair.co/all).
- Navigation menu reverse order sequence solution found on [Web Developer Diary](http://nambiara.blogspot.com/2010/10/float-right-without-changing-order.html).
- Code for Hero image overlay text was taken from "Love Running" walkthrough project and modified for this application.
- Overlay quote on Hero image taken from [Quotefancy.com](https://quotefancy.com/quote/1488144/Rajneesh-Enjoyment-is-just-the-sound-of-being-centered).
- Introduction text sourced from [bodymindlife.com](https://www.bodymindlife.com/about) on their "Our Purpose" section.
- Tile display and technique pages text content sourced from [bodymind-training.ch](https://www.bodymind-training.ch/techniken/mind-balancing/)
- Method for coding group sessions timetable on home page taken from "Love Running" walkthrough project.
- Social media icons sourced from [Font Awesome](https://fontawesome.com).
- Code for arranging social media icons in footer taken from "Love Running" walkthrough project.
- Media queries for home page at a screen width less than 769px was taken from "Love Running" walkthrough project and modified accordingly.

### Media

- All images sourced from [Pexels](https://www.pexels.com).
- Hero image sizing suggestions sourced on [Hubspot](https://blog.hubspot.com/marketing/hero-image).
- Information for optimizing images for web design found on [jimdo](https://www.jimdo.com/blog/optimize-website-images-for-better-design-seo/).
- All images resized using [TinyPNG](https://tinypng.com/).
- Code for Hero image zoom animation taken directly from "Love Running" walkthrough project.
- Method for embedding Youtube video learnt on [GeeksforGeeks](https://www.geeksforgeeks.org/html-adding-youtube-videos/).
- Learn about object-fit CSS property on [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit).