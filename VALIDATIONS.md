# Go Camping – Testing & Validation Report

This document outlines the testing process and validation results for the **Go Camping** website. Validation was carried out using W3C validation tools and manual accessibility and responsiveness checks.

---

## HTML Validation

All main pages were validated using the **W3C HTML Validator**. Validation was performed by URI after deployment to GitHub Pages. No critical HTML errors were found.

### Validation Evidence

#### Home Page
![HTML Validation – Home Page](assets/testing_data/validtor_data/home_html.png)

#### Prepare Page
![HTML Validation – Prepare Page](assets/testing_data/validtor_data/prepare_html.png)

#### Advice Page
![HTML Validation – Advice Page](assets/testing_data/validtor_data/advice_html.png)

#### Places Page
![HTML Validation – Places Page](assets/testing_data/validtor_data/places_html.png)

#### Success Page
![HTML Validation – Success Page](assets/testing_data/validtor_data/success_html.png)

---

## CSS Validation

Custom stylesheets were tested using the **W3C CSS Validator**. No errors were detected. Any warnings were related to vendor prefixes and external frameworks, which are acceptable for compatibility purposes.

### Validation Evidence

#### Main Stylesheet
![CSS Validation – Styles](assets/testing_data/validtor_data/styles_css.png)

#### Prepare Page Stylesheet
![CSS Validation – Prepare Styles](assets/testing_data/validtor_data/styles_prepare_css.png)

#### Advice Page Stylesheet
![CSS Validation – Advice Styles](assets/testing_data/validtor_data/styles_advice_css.png)

#### Places Page Stylesheet
![CSS Validation – Places Styles](assets/testing_data/validtor_data/styles_places_css.png)

---

## Accessibility Testing

Accessibility testing was carried out using a combination of **Lighthouse audits** and **manual keyboard navigation tests**.

The following checks were performed:
- Keyboard navigation using the Tab key
- Visible focus states for interactive elements
- Alt text provided for all images
- Labels correctly associated with form inputs
- Logical heading hierarchy across all pages

---

## Responsive Testing

The website was tested across multiple screen sizes using browser developer tools to ensure responsive behaviour and layout consistency.

### Breakpoints Tested
- 320px (Mobile)
- 576px (Small devices)
- 768px (Tablets)
- 992px (Small desktops)
- 1200px (Large desktops)
- 1400px (Extra large screens)

---

## Lighthouse Testing Summary

Google Lighthouse was used to perform performance, accessibility, best practices, and SEO audits. Minor performance warnings were related to image optimisation and third‑party frameworks, which are acceptable for a static Bootstrap project.

Accessibility, best practices, and SEO scores were consistently high, confirming that the website meets modern front‑end standards.

---

## Conclusion

The **Go Camping** website meets validation, accessibility, and responsiveness requirements appropriate for a static HTML, CSS, and Bootstrap project. All core pages validated successfully, and usability testing confirms the site is accessible and responsive across devices.
