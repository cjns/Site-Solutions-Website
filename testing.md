# Testing & Validation

The following tools were used to validate the project.
- HTML: [W3C Markup Validator](https://validator.w3.org/)
- CSS: [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- Accessibility: [WAVE (Web Accessibility Evaluation Tool)](https://wave.webaim.org/)
- Web Page Quality: [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) (via the chrome developer tools)


## HTML, CSS, Accessibility, and Performance

|Page|HTML|WAVE|Lighthouse Mobile|Lighthouse Desktop|
|-|-|-|-|-|
|index.html|[valid](./assets/images/testing/index-html-validation.webp)|[valid](./assets/images/testing/index-wave.webp)|||
|seo.html|[valid](./assets/images/testing/seo-html-validation.webp)|[valid](./assets/images/testing/seo-wave.webp)|||
|social-media.html|[valid](./assets/images/testing/social-media-html-validation.webp)|[valid](./assets/images/testing/social-media-wave.webp)|||
|about.html|[valid](./assets/images/testing/about-html-validation.webp)|[valid](./assets/images/testing/about-html-validation.webp)|||
|contact.html|[valid](./assets/images/testing/contact-html-validation.webp)|[valid](./assets/images/testing/contact-wave.webp)|||


[CSS validation can be viewed here.](/assets/images/testing/css-validation.webp)

### Summary

#### HTML & CSS Validation
validation was all valid without errors.

#### Accessibility

#### Lighthouse Performance
- Opportunities
    - Eliminate render-blocking resources.
- Diagnostics
    - Serve static assets with an efficient cache policy.
    - Avoid serving legacy JavaScript to modern browsers.


## Testing User Stories from User Experience (UX) section

- First Time Visitor Goals
- Returning Visitor Goals
- Frequent User Goals

### Further Testing

#### Home Page

|Feature|Expected Outcome|Testing Performed|Result|Pass/Fail|
|-|-|-|-|-|
|Nav: Home page link|Home page loads|Clicked link|Home page loads|Pass|
|Nav: SEO page|SEO page loads|Clicked link|SEO page loads|Pass|
|Nav: Social Media page|Social Media page loads|Clicked link|Social Media page loads|Pass|
|Nav: About Us page|About Us page loads|Clicked link|About Us page loads|Pass|
|Nav: Contact Us page|Contact Us page loads|Clicked link|Contact Us page loads|Pass|
|Nav: Link hover|All link text is black on hover|Hovered cursor over links|Text is black|Pass|
|Hubspot link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Bright Local link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Think With Google link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|SEO card link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Social Media card link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: Facebook link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: LinkIn link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: YouTube link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|

### SEO Page
|Feature|Expected Outcome|Testing Performed|Result|Pass/Fail|
|-|-|-|-|-|
|Nav: Home page link|Home page loads|Clicked link|Home page loads|Pass|
|Nav: SEO page|SEO page loads|Clicked link|SEO page loads|Pass|
|Nav: Social Media page|Social Media page loads|Clicked link|Social Media page loads|Pass|
|Nav: About Us page|About Us page loads|Clicked link|About Us page loads|Pass|
|Nav: Contact Us page|Contact Us page loads|Clicked link|Contact Us page loads|Pass|
|Nav: Link hover|All link text is black on hover|Hovered cursor over links|Text is black|Pass|
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||
|Footer: Facebook link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: LinkIn link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: YouTube link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|

### Social Media Page
|Feature|Expected Outcome|Testing Performed|Result|Pass/Fail|
|-|-|-|-|-|
|Nav: Home page link|Home page loads|Clicked link|Home page loads|Pass|
|Nav: SEO page|SEO page loads|Clicked link|SEO page loads|Pass|
|Nav: Social Media page|Social Media page loads|Clicked link|Social Media page loads|Pass|
|Nav: About Us page|About Us page loads|Clicked link|About Us page loads|Pass|
|Nav: Contact Us page|Contact Us page loads|Clicked link|Contact Us page loads|Pass|
|Nav: Link hover|All link text is black on hover|Hovered cursor over links|Text is black|Pass|
|Footer: Facebook link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: LinkIn link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: YouTube link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|

### About Us Page
|Feature|Expected Outcome|Testing Performed|Result|Pass/Fail|
|-|-|-|-|-|
|Nav: Home page link|Home page loads|Clicked link|Home page loads|Pass|
|Nav: SEO page|SEO page loads|Clicked link|SEO page loads|Pass|
|Nav: Social Media page|Social Media page loads|Clicked link|Social Media page loads|Pass|
|Nav: About Us page|About Us page loads|Clicked link|About Us page loads|Pass|
|Nav: Contact Us page|Contact Us page loads|Clicked link|Contact Us page loads|Pass|
|Nav: Link hover|All link text is black on hover|Hovered cursor over links|Text is black|Pass|
|Footer: Facebook link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: LinkIn link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: YouTube link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|

### Contact Us Page
|Feature|Expected Outcome|Testing Performed|Result|Pass/Fail|
|-|-|-|-|-|
|Nav: Home page link|Home page loads|Clicked link|Home page loads|Pass|
|Nav: SEO page|SEO page loads|Clicked link|SEO page loads|Pass|
|Nav: Social Media page|Social Media page loads|Clicked link|Social Media page loads|Pass|
|Nav: About Us page|About Us page loads|Clicked link|About Us page loads|Pass|
|Nav: Contact Us page|Contact Us page loads|Clicked link|Contact Us page loads|Pass|
|Nav: Link hover|All link text is black on hover|Hovered cursor over links|Text is black|Pass|
|Contact Form|Can only submit when all fields have valid entries|Tested submission with empty fields|All fields required for submission. Telephone field has to be a number.|Pass|
|Telephone number link|Opens or gives the option to open an application to call the number when clicked|Clicked on the link|Opens up the relevant application|Pass|
|Email link|Opens or gives the option open an email application|Clicked on the link|Provides option to open email client|Pass|
|Google Map|Clicking on the relevant link takes you to the correct destination in a new window|Clicked on the links|Correct pages open in a new window|Pass|
|Footer: Facebook link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: LinkIn link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: YouTube link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|


### Known bugs

### Fixed bugs

### Unfixed bugs
