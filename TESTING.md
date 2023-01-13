# Testing
## Code Validation
The Alex Honnold site has be throughly tested. All the code has been run through the [W3C html Validator](https://validator.w3.org/) and the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). Minor errors were found on the home and inspiration pages. After a fix and retest, no errors were returned for both. 

The HTML validator results for each page are below:

* Home page

![W3C Validator test result](assets/docs/testing/home-validation.png)

* Gallery page

![W3C Validator test result](assets/docs/testing/gallery-validation.png)

* Sign Up page

![W3C Validator test result](assets/docs/testing/signup-validation.png)

* Thank you page

![W3C Validator test result](assets/docs/testing/thankyou-validation.png)

The CSS validator results are below:

![CSS Validator test result](assets/docs/testing/css-validation.png)

## Responsiveness Test

* The responsive design tests were carried out manually with [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/) and [Responsive Design Checker](https://www.responsivedesignchecker.com/).

|        | Moto G4 | Galaxy S5 | iPhone 5 | iPad | iPad Pro | Display <1200px | Display >1200px |
|--------|---------|-----------|----------|------|----------|-----------------|-----------------|
| Render | pass    | pass      | pass     | pass | pass     | pass            | pass            |
| Images | pass    | pass      | pass     | pass | pass     | pass            | pass            |
| Links  | pass    | pass      | pass     | pass | pass     | pass            | pass            |

Note: On wide display types the contents of the site are restricted in width to 1440px. This helps the UX by not spreading the content too wide on the extra wide screens.

## Browser Compatibility

The website was tested on the following browsers with no visible issues for the user. 
Google Chrome, Microsoft Edge, Safari and Mozilla Firefox. Appearance, functionality and responsiveness were consistent throughout for a range of device sizes and browsers.

## Known Bugs
* ### Resolved

    * During validation two bugs became known during the validation stage, a brief description is below:

    * Gallery page - 
    ![W3C Validator test result](assets/docs/testing/gallery-bug.png)
This was an oversight from the development phase when the font size was being modified. It was easily fixed by using the correct closing tag, \</h5>.

    * /// - 
    ///

* ### Unresolved
    * ///
    * ///
    

## Additional Testing
### Lighthouse
The site was also tested using [Google Lighthouse](https://developers.google.com/web/tools/lighthouse) in Chrome Developer Tools to test each of the pages for:
* Performance - How the page performs whilst loading.
* Accessibility - Is the site acccessible for all users and how can it be improved.
* Best Practices - Site conforms to industry best practices.
* SEO - Search engine optimisation. Is the site optimised for search engine result rankings.

As an example the results for home page are below:
![Lighthouse test results]()

This part of the testing process showed up that the site was slow to load. 

### Peer review
In addition to the above testing the beta version of the site was put through its paces by peers, both in the software development field and outside. The results highlighted responsive design weakness for a type of mobile device that was rectified with minor CSS amendments. There were also minor spelling and grammar errors that have since been fixed.

Back to [README.md](./README.md#testing).