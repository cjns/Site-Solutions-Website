# Testing & Validation

The following tools were used to validate the project.
- HTML: [W3C Markup Validator](https://validator.w3.org/)
- CSS: [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- Accessibility: [WAVE (Web Accessibility Evaluation Tool)](https://wave.webaim.org/)
- Web Page Quality: [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) (via the chrome developer tools)

## HTML & CSS Validation, Accessibility, and Performance

|Page|HTML|WAVE|Lighthouse Mobile|Lighthouse Desktop|
|-|-|-|-|-|
|index.html|[valid](./assets/images/testing/index-html-validation.webp)|[valid](./assets/images/testing/index-wave.webp)|[96 100 100 100](./assets/images/testing/index-lighthouse-mobile.webp)|[100 100 100 100](./assets/images/testing/index-lighthouse-desktop.webp)|
|seo.html|[valid](./assets/images/testing/seo-html-validation.webp)|[valid](./assets/images/testing/seo-wave.webp)|[97 100 100 100](./assets/images/testing/seo-lighthouse-mobile.webp)|[100 100 100 100](./assets/images/testing/seo-lighthouse-desktop.webp)|
|social-media.html|[valid](./assets/images/testing/social-media-html-validation.webp)|[valid](./assets/images/testing/social-media-wave.webp)|[95 100 100 100](./assets/images/testing/social-lighthouse-mobile.webp)|[100 100 100 100](./assets/images/testing/social-lighthouse-desktop.webp)|
|about.html|[valid](./assets/images/testing/about-html-validation.webp)|[valid](./assets/images/testing/about-html-validation.webp)|[95 100 100 100](./assets/images/testing/about-lighthouse-mobile.webp)|[100 100 100 100](./assets/images/testing/about-lighthouse-desktop.webp)|
|contact.html|[valid](./assets/images/testing/contact-html-validation.webp)|[valid](./assets/images/testing/contact-wave.webp)|[98 100 92 100](./assets/images/testing/contact-lighthouse-mobile.webp)|[100 100 92 100](./assets/images/testing/contact-lighthouse-desktop.webp)|
|404.html|[valid](./assets/images/testing/404-html-validation.webp)|[valid](./assets/images/testing/404-wave-changes.webp)|[98 100 100 100](./assets/images/testing/404-lighthouse-mobile-changes.webp)|[99 100 100 100](./assets/images/testing/404-lighthouse-desktop-changes.webp)|
|thank-you.html|[valid](./assets/images/testing/thank-you-html-validation.webp)|[valid](./assets/images/testing/thankyou-wave-changes.webp)|[99 100 100 100](./assets/images/testing/thankyou-lighthouse-mobile-changes.webp)|[99 100 100 100](./assets/images/testing/thankyou-lighthouse-desktop-changes.webp)|

[My style.css file was valid and can be viewed here.](/assets/images/testing/css-validation.webp)

### Validation, Accessibility, and Performance Summary
- HTML and CSS validation pass without any issues.
- All WAVE assessments are without error.
    - Initially, I implemented a `http-equiv='refresh'` on the [404.html](./assets/images/testing/404-wave.webp) and [thank-you.html](./assets/images/testing/thank-you-wave.webp) after receiving some advice. However, this negatively impacted the WAVE and Lighthouse score so I chose to remove it, which resolved the WAVE errors and increased the Lighthouse score (the latest result being in the table above).
        - 404.html WAVE assessment [with the refresh active](./assets/images/testing/404-wave-intended-refresh.webp).
        - 404.html [Lighthouse scores](./assets/images/testing/404-lighthouse-mobile.webp) with the [refresh active](./assets/images/testing/404-lighthouse-mobile-accessibility.webp).
        - thank-you.html WAVE assessment [with the refresh active](./assets/images/testing/thank-you-wave-intended-refresh.webp).
        - thank-you.html [Lighthouse scores](./assets/images/testing/thankyou-lighthouse-mobile.webp) with the [refresh active](./assets/images/testing/thankyou-lighthouse-mobile-accessibility.webp).
- Some of the scores for performance, mostly mobile, are less than 100. This appears to be due to the use of Bootstrap, which carries a lot of unused JavaScript and CSS since I only used the library for the navigation, which is evidenced [here](./assets/images/testing/index-lighthouse-mobile-opportunities.webp) and [here](./assets/images/testing/contact-lighthouse-mobile-performance.webp). This was the culprit for all performance drops over the entire site. Creating a nav purely out of CSS or using a lighter UI library should resolve the issue. Although Bootstrap was helpful in creating a responsive nav bar with ease it comes with the tradeoff of loading additional, potentially unused, scripts and css.

## Testing User Stories from User Experience (UX) section

| Opportunity/Problem                                                              | Evidence of meeting user story |
| -------------------------------------------------------------------------------- | -------------------------------|
| 1. Find out about Site Solutions.                                                | []()                           |
| 2. Follow Site Solutions for updates and promotions.                             | []()                           |
| 3. Have contact info. available to encourage enquiries/leads.                    | []()                           |
| 4. Establishing credibility and showcase expertise in seo.                       | []()                           |
| 5. Provide quick access to services and explain how they help businesses grow.   | []()                           |
| 6. Providing industry insights                                                   | []()                           |
| 7. Measuring success metrics                                                     | []()                           |
| 8. I want to be able to navigate the site easily to find the information I need. | []()                           |

### User Story Discussion
1.
2.
3.
4.
5.
6.
7.
8.


## Further Testing

### Home Page

|Feature|Expected Outcome|Testing Performed|Result|Pass/Fail|
|-|-|-|-|-|
|Nav: Home page link|Home page loads|Clicked link|Home page loads|Pass|
|Nav: SEO page|SEO page loads|Clicked link|SEO page loads|Pass|
|Nav: Social Media page|Social Media page loads|Clicked link|Social Media page loads|Pass|
|Nav: About Us page|About Us page loads|Clicked link|About Us page loads|Pass|
|Nav: Contact Us page|Contact Us page loads|Clicked link|Contact Us page loads|Pass|
|Nav: Link hover|All link text is black on hover|Hovered cursor over links|Text is black|Pass|
|HubSpot link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Bright Local link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Think With Google link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|SEO card link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Social Media card link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: Facebook link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: LinkIn link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Footer: YouTube link|Link opens in a new window|Clicked link|Page opens in a new window|Pass|
|Mobile responsive: iPhone12 Pro|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: Pixel 5|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: iPad Air|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Browser responsive: Google Chrome|Page is responsive|Navigate with Google Chrome|Responsive|Pass|
|Browser responsive: Mozilla Firefox|Page is responsive|Navigate with Mozilla Firefox|Responsive|Pass|

### SEO Page
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
|Mobile responsive: iPhone12 Pro|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: Pixel 5|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: iPad Air|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Browser responsive: Google Chrome|Page is responsive|Navigate with Google Chrome|Responsive|Pass|
|Browser responsive: Mozilla Firefox|Page is responsive|Navigate with Mozilla Firefox|Responsive|Pass|

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
|Mobile responsive: iPhone12 Pro|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: Pixel 5|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: iPad Air|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Browser responsive: Google Chrome|Page is responsive|Navigate with Google Chrome|Responsive|Pass|
|Browser responsive: Mozilla Firefox|Page is responsive|Navigate with Mozilla Firefox|Responsive|Pass|

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
|Mobile responsive: iPhone12 Pro|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: Pixel 5|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: iPad Air|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Browser responsive: Google Chrome|Page is responsive|Navigate with Google Chrome|Responsive|Pass|
|Browser responsive: Mozilla Firefox|Page is responsive|Navigate with Mozilla Firefox|Responsive|Pass|

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
|Mobile responsive: iPhone12 Pro|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: Pixel 5|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: iPad Air|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Browser responsive: Google Chrome|Page is responsive|Navigate with Google Chrome|Responsive|Pass|
|Browser responsive: Mozilla Firefox|Page is responsive|Navigate with Mozilla Firefox|Responsive|Pass|

### 404 & Thank You Pages
|Feature|Expected Outcomes|Testing Performed|Result|Pass/Fail|
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
|Mobile responsive: iPhone12 Pro|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: Pixel 5|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Mobile responsive: iPad Air|Page is mobile responsive|Chrome Dev Tools|Responsive|Pass|
|Browser responsive: Google Chrome|Page is responsive|Navigate with Google Chrome|Responsive|Pass|
|Browser responsive: Mozilla Firefox|Page is responsive|Navigate with Mozilla Firefox|Responsive|Pass|

### Fixed bugs
1. Firefox has a placeholder opacity different from 1, which caused the text to be muted. I preferred this to the light text it was supposed to be and carried it over to Chrome by specifying an opacity of 0.6, which you can see on line 586 of the [style.css](./assets/css/style.css) file.

### Unfixed bugs
1. No known bugs at the time of writing this.