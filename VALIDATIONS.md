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

Google Lighthouse was used to perform audits covering **Performance, Accessibility, Best Practices, and SEO**.  
Tests were run in a private browser window to minimise the impact of extensions.

Minor performance warnings were mainly related to image optimisation and third‑party frameworks (Bootstrap and Font Awesome), which are acceptable for a static Bootstrap‑based project.

Accessibility, Best Practices, and SEO scores were consistently high, confirming that the website meets modern front‑end standards.

---

## Lighthouse Report Evidence

### Home Page

#### Desktop View
![Home Page Lighthouse – Desktop](assets/testing_data/lighthouse_reports/homeuse_reports/home_mobile.png

---

### Prepare Page

#### Desktop View
![Prepare Page Lighthouse – Desktop](assets/testing_data/lighthouse_reports/prepare_desktop.png)

#### Mobile View
![Prepare Page Lighthouse – Mobile](assets/testing_data/lighthouse_reports/prepare_mobile.png)

---

### Advice Page

#### Desktop View
![Advice Page Lighthouse – Desktop](assets/testing_data/lighthouse_reports/advice_desktop.png)

#### Mobile View
![Advice Page Lighthouse – Mobile](assets/testing_data/lighthouse_reports/advice_mobile.png)

---

### Places Page

#### Desktop View
![Places Page Lighthouse – Desktop](assets/testing_data/lighthouse_reports/places_desktop.png)

#### Mobile View
![Places Page Lighthouse – Mobile](assets/testing_data/lighthouse_reports/places_mobile.png)

---

### Success Page

#### Desktop View
![Success Page Lighthouse – Desktop](assets/testing_data/lighthouse_reports/success_desktop.png)

#### Mobile View
![Success Page Lighthouse – Mobile](assets/testing_data/lighthouse_reports/success_mobile.png)

---


## Conclusion

The **Go Camping** website meets validation, accessibility, and responsiveness requirements appropriate for a static HTML, CSS, and Bootstrap project. All core pages validated successfully, and usability testing confirms the site is accessible and responsive across devices.
