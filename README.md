BY: Tristin Watkins
9/24/2025
CS408 

# Accessible Nature Article — Bear Facts

This project is a fictional nature site that displays an article about bears.  
The starting version of the site had multiple accessibility issues, which were explored and fixed as part of this assessment. The goal was to make the site easier to navigate, more inclusive, and compliant with accessibility best practices

---

## Project Overview

- **Type:** Static website (HTML, CSS, minimal JavaScript)
- **Focus:** Improving accessibility of an existing site
- **Content:** A factual article about bears, with navigation, images, audio, a comments section, and a data table.

---

## Accessibility Improvements

### Color and Contrast
-Making minor changes to the color sceheme and overall structuce of the CSS file, will change the websites ideal look. So we can rewrite it to give it a more natural look.

### Semantic HTML
- Replaced deprecated `<font>` tags with semantic headings `<h1>`, `<h2>`, `<h3>`.
- Replaced `<div class="nav">` with a proper `<nav>` element.
- Introduced `<main>` for the main article and `<aside>` for secondary content.
- Improved keyboard navigation: tabbing now follows a clear, logical order.

### Images
- When it comes to the images we add the alt tag in order to properly show it on the website and then show it.

### Audio
-This website uses a transcript for people who are deaf and can audio describe it.

## How to Run the Project
1. Clone or download this repository.
2. Open `index.html` in your browser.
3. No build tools or servers are required — it is pure HTML/CSS with minimal JavaScript All that is needed is to change the HTML style to fix the mimimum amount of changes and the CSS file to change the color and theme contratsts.

---

## Reflection
This project highlighted how many small issues (color choices, missing labels, improper markup) can add up to create major accessibility barriers. By fixing these problems:
- Screen reader users can now understand the structure of the page.
- Keyboard users can fully navigate and interact with all controls.
- Users with visual impairments benefit from improved color contrast.
- Users with hearing impairments have equal access to the audio content.

Overall this project, was fun and interesting, It just goes to show how much CSS style can change how much a website looks and functuions properly.
