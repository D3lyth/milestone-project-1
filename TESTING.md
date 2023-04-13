# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files. I have validated using the live, deployed site using the live site links shown below.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FD3lyth.github.io%2Fmilestone-project-1%2Findex.html) | ![screenshot](documentation/html-validation-home.png) | No errors: Img-fliud errors and duplicate ids found and fixed |
| Information | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fd3lyth.github.io%2Fmilestone-project-1%2Finformation.html) | ![screenshot](documentation/html-validation-info.png) | No errors: Img-fluid errors found and fixed |
| Clubs | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FD3lyth.github.io%2Fmilestone-project-1%2Fclubs.html) | ![screenshot](documentation/html-validation-clubs.png) |No Errors, but warning for section (form) lacking h2-h6 headings  |
| Sign Up Complete | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FD3lyth.github.io%2Fmilestone-project-1%2Fsignupcomplete.html) | ![screenshot](documentation/html-validation-signupcomplete.png) | No Errors, but warning for section (form) lacking h2-h6 headings  |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files. I copied and pasted the css code into the validator using this link (to ensure that it was only my code and no external libraries/frameworks were included): https://jigsaw.w3.org/css-validator/#validate_by_input

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2FD3lyth.github.io%2Fmilestone-project-1) | ![screenshot](documentation/css-validation-style.png) | Pass: No Errors. There were warnings, but these have come from the Bootstrap code. |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](documentation/browser-chrome.png) | Works as expected |
| Firefox | ![screenshot](documentation/browser-firefox.png) | Works as expected |
| Edge | ![screenshot](documentation/browser-edge.jpg) | Minor css differences and scaling issues |
| Safari | ![screenshot](documentation/browser-safari.png) | Works as expected |
| Brave | ![screenshot](documentation/browser-brave.png) | Works as expected |
| Opera | ![screenshot](documentation/browser-opera.png) | Works as expected|

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| Mobile (iPhone14) | ![screenshot](documentation/responsive-mobile.png) ![screenshot](documentation/responsive-mobile2.png) | Works as expected |
| Tablet (iPadAir) | ![screenshot](documentation/responsive-tablet.png) ![screenshot](documentation/responsive-tablet2.png) ![screenshot](documentation/responsive-tablet3.png) | Works as expected |
| Desktop (Macbook 13") | ![screenshot](documentation/responsive-desktop.png) ![screenshot](documentation/responsive-desktop1.png)| Works as expected |
| XL Monitor (DevTools) | ![screenshot](documentation/responsive-xl.png) | Scaling starts to have minor issues - text is small|
| 4K Monitor (DevTools) | ![screenshot](documentation/responsive-4k.png) | Noticeable scaling issues - cannot read the text |
| Galaxy Fold (DevTools) | ![screenshot](documentation/responsive-galaxyfold.png) | Due to small screen, x-scrollbar comes into effect and some scaling issues|

## Lighthouse Audit
I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](documentation/lighthouse-home-mobile.png) | Slow response time due to large images |
| Home | Desktop | ![screenshot](documentation/lighthouse-home-desktop.png) | Slow response time due to large images |
| Information | Mobile | ![screenshot](documentation/lighthouse-info-mobile.png) | Some minor warnings |
| Information | Desktop | ![screenshot](documentation/lighthouse-info-desktop.png) | No issues |
| Clubs | Mobile | ![screenshot](documentation/lighthouse-clubs-mobile.png) | Slow response time due to large images |
| Clubs | Desktop | ![screenshot](documentation/lighthouse-clubs-desktop.png) | No issues |
| Sign Up Complete | Mobile | ![screenshot](documentation/lighthouse-signupcomplete-desktop.png) | No issues |
| Sign Up Complete | Desktop | ![screenshot](documentation/lighthouse-signupcomplete-desktop.png) | No issues |

## User Story Testing

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to be able to navigate easily around the site, so that I can find what I need easily. This can be done clicking on the navigation links and the log will always take the user back to the homepage.| ![screenshot](documentation/feature01.png) |
| As a new site user, I would like to find out information about the school houses, so that I can interact with the site and prepare for the school year. Information about all houses can be found by clicking on the cards that rotate to show the information regarding the characteristics. Clicking ont these will allow users to rad up about the four houses. | ![screenshot](documentation/feature02.png) |
| As a new site user, I would like to be able to navigate to the school's various social links, so that I can keep up to date with all the annoucements and details regarding the school. The links at the bottom will send the user to various social media sites. The link have all been tested and open correctly in a new tab. | ![screenshot](documentation/feature03.png) |
| As a new and returning site user, I would like to be able to navigate the site on a smaller device, so that I can access the information on a mobile phone. The toggle button allows the user to be able to do this intuitively and without having to make the font too small. The toggle button has been tested on various screen sizes to allow for ease of navigation through the site. | ![screenshot](documentation/feature04.png) |
| As a new and returning site user, I would like to view the books that will be required to study at Hogwarts, so that I can then see what I'm looking for and what the books look like. A selection of the book covers can be scrolled through a carousel so that the user can view the book covers without too much scrolling and images overwhelming a space all at once. The carousel has been tested on various screen sizes and returns to the starts whenn all the books have been scrolled through. | ![screenshot](documentation/feature05.png) |
| As a new and returning site user, I would like to fill in a form to be able to join clubs without spending time filling out a lengthy sign-up, so that I can easily see which clubs are available at the school. The form has been tested so that each part has a input type. The form has been tested so that if the email address field does not include an "@" the form will ask the user to input again. The form has been tested so that if any of the required fields have not been copleted, the form will not be submitted and the required fiels must be filled. | ![screenshot](documentation/feature06.png) |
| As a returning site user, I should be able to navigate the site easily to find the sign-up form, so that I can come back and re-join clubs and fill in a permission slip - there is a clearly marked drop down menu to allow year 3 and above students to indicate permission for Hogsmede visits. The dropdown menu has been tested so that a 'do' or 'do not' option will need to be selected. | ![screenshot](documentation/feature07.png) |
| As a returning site user, I would like to be able to view a message after filling in the form, so that I can know that I have submitted it correctly. The submit button has been tested so that a 'Thank you for signing-up' page appears after pressing the sign-up button. | ![screenshot](documentation/feature08.png) |

## Bugs

I encountered a few bugs along the way - which I have outlined below and shown how it was fixed.

- Toggle (Burger button) disappeared at 992px and links were not not visible either.

    ![screenshot](documentation/bug01.png)

    - To fix this, I adjusted the media query for `.dropdown` to be `min-width: 993px` like below:

```css
@media screen and (min-width: 993px) {
  .dropdown {
    display: none;
  }
}
```

- Text on certain parts of the pages (the book and author information on the caurosel and the book lists on the information page) were small and the font weight was thin, making it difficult to read.

    - To fix this, I increased the font size to 18px. The font-weight was still a bit light, but changing the font weight wasn't yielding results. To overcome this I imported a the same font (Quicksand) with a greater weight (400) and this made the text bolder and more readable.

- Carousel indicator buttons would not change colour when trying to restyle them in css. Due to the colour of the background, the indicator buttons were very hard to see.

    - To fix this, I used Stack Overflow to find someone that had come across the same issue and followed one of their fixes, which was to use `invert` in css like below:

    ```css
    .carousel-control-prev {
  left: 0;
  filter: invert(1); }

    ```css
    .carousel-control-next {
    right: 0;
    filter: invert(1);
    }
    ```
- Initially, the images within the flip cards were extending beyond the cards when changing the size of the screen.

    ![screenshot](documentation/bug02.png)

    - To fix this, I used [PhotoPea](https://www.photopea.com) to edit the images to allow for more white space around the photos.
    - I also changed the size of the cards to make sure that they did not change shape when checking for responsiveness using the css below

    ```css
    .flip-card {
  max-width: 250px;
  height: 250px;
  margin: 0 auto;}
  ```

- The 'Return to Homepage' link on the signupcomplete page when hovered upon was causing some x-scrolling issues. This was due to me putting the transition and transform selectors on the sections rather than the link.

    - To fix this, I changed the css to ensure that the transform and transition values were targeting the correct selectors.

- The homepage was experiencing some overflow-x scrolling issues. This was due to the hero image and the 'Headmaster's Address section spanning 100% of the view port but various padding and margin values were causing the sections and images to span beyond the viewport.

    - To fix this, I went through my css and used chrome developer tools to change some padding and margin values to auto or zero on various selectors, and this rectified the problem.

- The performance indicator on Lighthouse was showing as amber with quite a few of my pages, and indicating that image loading was having an effect on the performance.

    - To fix this, I used [TinyPNG](https://tinypng.com) to compress the images used on the site and this increased the Performance of the website on all pages.

- The carousel when clicking on the prev/next toggles was causing a an overflow-x scrolling issue do to the carousel spanning the whole view port.

    - To fix this I removed the following css and this rectified the problem.
    ```css
    .carousel-inner {
  overflow: visible;}
  ```
  The fix was then tested due to the possibility of the carousel indicators vanishing when removing the overflow, but I tested the fix on the follwong browsers: chrome/edge/brave/opera/safari adn it was still visible. I also tested on Macbook, ThinkPad, iPad, iPhone 14, iPhone X and OnePlus Nord 2 and the scrolling issue has gone and the indicators still appear.

## Unfixed Bugs

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.

- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/html-validation-clubs.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

Other than the bugs mentioned above, there are no other remaining bugs that I am aware of.
