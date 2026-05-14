# Go Camping – First‑Time Camping Guide

Click **[LIVE SITE LINK](https://kaloyanjk.github.io/First-assignment-HTMLL-CSS-Bootstrap/index.html)** to view the deployed website.

## Table of Contents
- [Mockups](#mockups)
- [Project Overview](#project-overview)
- [Project Updates](#project-updates)
- [Goals & Objectives](#goals--objectives)
- [Target Audience](#target-audience)
- [User Goals](#user-goals)
- [User Experience (UX)](#user-experience-ux)
- [User Stories](#user-stories)
- [Site Structure](#site-structure)
- [Design Decisions](#design-decisions)
- [Pages Overview](#pages-overview)
- [Technologies Used](#technologies-used)
- [AI Usage Declaration](#ai-usage-declaration)
- [Testing & Validation](#testing--validation)
- [Limitations & Future Improvements](#limitations--future-improvements)
- [Screenshots](#screenshots)
- [Figma Designs & Wireframes](#figma-designs--wireframes)

---

## Mockups
![Responsive Mockup – Home page](assets/mockups/home.png)

<details>
  <summary>Click to view more mockups</summary>

  <p align="center">
    <img src="assets/mockups/prepare.png" alt="Responsive Mockup – Prepare Page"><br>
    <img src="assets/mockups/advice.png" alt="Responsive Mockup – Advice Page"><br>
    <img src="assets/mockups/places.png" alt="Responsive Mockup – Places Page">
  </p>

</details>

---

## Project Overview

**Go Camping** is a static, beginner‑focused website created to help **first‑time campers in the UK** feel confident and prepared. The site explains what camping at organised campsites involves, how to prepare effectively, and how to follow basic campsite safety and etiquette rules.

The primary aim of this project is to **reduce anxiety for beginners** and provide clear, practical guidance in a friendly and accessible format.

The website was built using **HTML, CSS, and Bootstrap**, with a strong focus on **responsive design, usability, and accessibility**.

---

## Project Updates

- Fully responsive layout tested across all Bootstrap breakpoints
- Consistent navigation across all pages with active‑link styling
- Accordion components used to manage large blocks of content
- Clear call‑to‑action buttons guiding users through the site
- Improved text contrast and readability on image backgrounds
- Image optimisation using WebP format to improve performance

---

## Goals & Objectives

- Explain what camping at an organised campsite is like
- Provide simple preparation guidance for beginners
- Reduce fear of doing something wrong
- Encourage confident and realistic expectations about camping

---

## Target Audience

- Complete beginners to camping
- UK residents planning their first campsite trip
- Users looking for clear, non‑technical guidance
- People feeling nervous about safety, equipment, or etiquette

---

## User Goals

- Understand campsite life and expectations
- Know what to bring and how to prepare
- Learn basic safety rules and campsite behaviour
- Navigate information easily on mobile and desktop devices

---

## User Experience (UX)

The website uses calm, nature‑inspired colours, clear spacing, and friendly language to reassure beginners. Content is broken into manageable sections using accordions and cards to avoid overwhelming users.

Navigation is consistent across all pages, and each page provides a logical **“next step”** to guide users through their camping preparation journey.

---

## User Stories

**User Story 1**  
As a first‑time camper, I want to understand what camping involves, so I can decide if it is right for me.

**User Story 2**  
As a beginner, I want a simple preparation guide, so I know what to pack.

**User Story 3**  
As a nervous camper, I want to learn safety and etiquette rules, so I don’t worry about doing something wrong.

---

## Site Structure

Primary user flow:  
**Home → Prepare → Advice → Places**

Each page can be accessed independently but is designed to work as part of a clear learning sequence.

---

## Design Decisions

### Colour Palette
- Forest green tones to reflect nature, trust, and calmness
- Earth colours for stability and outdoor themes
- Orange accents used for call‑to‑action buttons
- Neutral backgrounds to improve readability


<table>
<tr>
<th>Colour</th>
<th>Preview</th>
<th>Hex</th>
</tr>

<tr>
<td>Primary</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#2F4A2E;border-radius:4px;"></span></td>
<td><code>#2F4A2E</code></td>
</tr>

<tr>
<td>Primary Dark</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#243A23;border-radius:4px;"></span></td>
<td><code>#243A23</code></td>
</tr>

<tr>
<td>Accent</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#C47A2C;border-radius:4px;"></span></td>
<td><code>#C47A2C</code></td>
</tr>

<tr>
<td>Accent Light</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#E2A45E;border-radius:4px;"></span></td>
<td><code>#E2A45E</code></td>
</tr>

<tr>
<td>Main Background</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#F3E9C6;border:1px solid #ccc;border-radius:4px;"></span></td>
<td><code>#F3E9C6</code></td>
</tr>

<tr>
<td>Soft Background</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#FAF5E4;border:1px solid #ccc;border-radius:4px;"></span></td>
<td><code>#FAF5E4</code></td>
</tr>

<tr>
<td>Main Text</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#1E2A1E;border-radius:4px;"></span></td>
<td><code>#1E2A1E</code></td>
</tr>

<tr>
<td>Light Text</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#F7F0D6;border:1px solid #ccc;border-radius:4px;"></span></td>
<td><code>#F7F0D6</code></td>
</tr>

<tr>
<td>Border</td>
<td><span style="display:inline-block;width:120px;height:24px;background:#D4C89E;border-radius:4px;"></span></td>
<td><code>#D4C89E</code></td>
</tr>

</table>

### Typography
- System sans‑serif fonts for accessibility
- Clear heading hierarchy (`h1` → `h2` → `h3`)
- Comfortable line height to improve readability

### UI Components
- Accordions to manage large amounts of information
- Cards to highlight key topics and benefits
- Buttons to guide user progression through the site

---

## Pages Overview

### Home – *Is Camping for You?*
- Introduction and reassurance content
- Accordion sections explaining camping basics
- Call‑to‑action linking to the preparation page

### Prepare – *What to Pack & How to Get Ready*
- Beginner checklist and preparation guidance
- Clear distinction between essential and optional items
- Interactive checklist layout

### Advice – *Safety & Campsite Etiquette*
- Safety rules explained in simple language
- Environmental responsibility guidance
- Reassurance for common beginner worries

### Places – *Where to Camp*
- Embedded Google Maps iframe showing beginner‑friendly camping locations across the UK
- Visual exploration of campsites before planning a trip
- Highlights key UK regions such as England, Wales, and Scotland

---

## Technologies Used

- **HTML5** – semantic markup and page structure
- **CSS3** – custom styling and layout control
- **Bootstrap 5** – responsive grid system and UI components

---

## AI Usage Declaration

AI tools were used as **supporting tools** during development, primarily for:
- Logo generation
- Clarifying Bootstrap behaviour
- Structuring documentation
- Assisting with content drafts

All generated content was reviewed, edited, and adapted to meet project requirements.

Tools used:
- **[Microsoft Copilot](https://copilot.microsoft.com/)**

---

## Testing & Validation

Testing details, screenshots, and validation results are documented in a separate file:

➡ **[VIEW VALIDATION REPORT](VALIDATIONS.md)**

## Identified Issues
Lighthouse audits highlighted several areas where the website could be improved, particularly in:

- Performance score. Large background images and multiple image assets affect initial load time.
Best Practices / Accessibility warnings
Minor warnings related to image optimisation and third‑party embeds.

- These issues were identified during validation but were not fully resolved within the project timeframe.

---

## Limitations & Future Improvements

### Limitations
- No backend or database functionality
- Static content only
- Beginner‑level depth by design

### Future Improvements
- FAQ page for common beginner questions
- Downloadable PDF packing checklist
- Improved animations and transitions
- Beginner confidence checklist or quiz

---

## Figma Designs & Wireframes

Design planning, wireframes, and mockups created in Figma are documented in a separate file:

➡ **[VIEW FIGMA DESIGNS](FIGMA.md)**
