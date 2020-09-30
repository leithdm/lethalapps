# Testing

## Validators

[W3C HTML Markup Validation Service](https://validator.w3.org/)

- Home Page

![Home Page HTML Validator](readme-files/index-validator.PNG)

Result: No Errors or warnings to show.

- Work Page

![Work Page HTML Validator](readme-files/work-validator.PNG)

Result: No Errors or warnings to show.

- Company Page

![Company Page HTML Validator](readme-files/company-validator.PNG)

Result: No Errors or warnings to show.

- Contact Page

![Contact Page HTML Validator](readme-files/contact-validator.PNG)

Result: x1 Error related to the 'frameborder' attribute on the 'iframe' element being obsolete. After removing the attribute entirely, the result was No Errors or warnings to show.

![Contact Page HTML Validator](readme-files/contact-validator-corrected.PNG)

[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)

![CSS Validator](readme-files/css-validator.PNG)

Result: No Errors Found. The validator did find x4 generic warnings related to imported style sheets for google fonts and transform extensions for 'ms', 'moz' and 'webkit'. These warnings are ignored. 


## Compatability - Manual Testing

To ensure a broad range of users can successfully use this site, it was manually tested across the 6 major browsers:

- Chrome v.74
- Edge v.18
- Firefox v.67
- Safari v.12
- Opera v.56
- Internet Explorer v.11

To test site responsiveness the following tools were used:

- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)
- [Responsive Design Checker](https://www.responsivedesignchecker.com/)

Below is a table detailing the results of this testing: 

![Responsive Design](readme-files/responsiveness.PNG)

## Compatability - Automated Testing

Automated testing was performed using [PowerMapper](https://www.powermapper.com/). This tool checks websites for broken links, browser compatibility, accessibility, web standards validation, search engine issues, and general usability. 

![PowerMapper Errors](readme-files/powermapper-errors.PNG)

Result: No Errors Found.

![PowerMapper Errors](readme-files/powermapper-accessibility.PNG)

Result: x4 Level A Errors, x3 Level AA Errors.

All of the errors were corrected except for: 
1. 'A video plays longer than 5 seconds, without a way to pause it'. This is in reference to the header videos that display on each of the main website pages. This is a design consideration. This error is ignored.
2. 'Ensure that text and background colors have enough contrast'. This is a design consideration. This error is ignored. 

![PowerMapper Errors](readme-files/powermapper-compatibility.PNG)

Result: SVG images, CSS filter, and CSS transform are not supported by some older browsers. These compatibility problems are accepted, and are ignored. Most Android devices from 4.4 onwards use Chrome as the default browser instead of the original Android browswer, and IE and Safari <= 9 are *legacy* browsers.

![PowerMapper Errors](readme-files/powermapper-search.PNG)

Result: Offer an HTML site map. 
Using [XML-SiteMaps](https://www.xml-sitemaps.com/) a site-map was created and added to the root directory to remove this error. 

![PowerMapper Errors](readme-files/powermapper-usability.PNG)

Result: a few minor Errors in relation to img width or height. 
These errors were corrected and removed. 


## Testing User stories

Result: All user stories have been successfully implemented, with a :white_check_mark: to denote items that have been implemented in this website. 



"**__As an owner, I__** ______________________________________________"

- :white_check_mark: need to ensure potential customers can use the website to get in contact. The primary metric for return on investment for this website is an increase in the number of enquiries through the contact form. 
- :white_check_mark: need to show potential customers that we are a dynamic, modern, and efficient company. We value clarity, and simplicity and this must be reflected in the design.  
- :white_check_mark: must display a show-case of portfolio work for potential customers to see. 
- :white_check_mark: must let the customer know about our past successes via testimonials. 

"**__As a user, I__** ______________________________________________"

- :white_check_mark: need to be able to view the site from any device (mobile, tablet, desktop).
- :white_check_mark: should be presented with a site that meets accessibility guidelines including contrast between background and foreground colors, and non-text elements with alt text equivalents.
- :white_check_mark: should be presented with a website that has a flow of information-layout and interaction-feedback that is clear and unambiguous.
- :white_check_mark: should have all of my actions confirmed, where appropriate, and feedback should be given at all times.
- :white_check_mark: should be able to view a show-case of previously completed works by the company.
- :white_check_mark: should be able to make further enquiries by filling out an enquiry form.
- :white_check_mark: should be able to see testimonials from other customers that have used the services of this company. 
- :white_check_mark: should be able to read further details on the company, including info on employee, company back-story, company vision, etc. 
- :white_check_mark: my interaction with the site should produce a positive emotional response. I should immediately be drawn-in.

"**__As a developer, I__** ______________________________________________"

- :white_check_mark: must maximise future maintainability through documentation, code structure and organisation.
- :white_check_mark: must document testing fully to include evaluation of bugs found and their fixes and explanation of any bugs that are left unfixed.
- :white_check_mark: must test and deploy a front-end web application to a Cloud platform. HTML/CSS code pass through the official W3C validators with no issues.
- :white_check_mark: must ensure all HTML attribute and CSS rule names are consistent in format, appropriate and meaningful.
- :white_check_mark: must ensure that when displaying media files, the site avoids aggressive automatic pop-ups and autoplay of audio; instead letting the user initiate and control such actions.

## Bugs 


[Go back to README.md file](README.md).

