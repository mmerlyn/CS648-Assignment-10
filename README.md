# jQuery Plugins & jQuery UI Integration

_This project shows how to use jQuery plugins and jQuery UI widgets to make a website more interactive. It includes custom plugins, tabs, accordions, tooltips, and form styling on the Vecta Corp website._

## Overview

This project adds interactive features to a corporate website using jQuery. It includes three custom plugins for mobile menus, sticky elements, and scroll-to-top buttons. It also uses jQuery UI widgets like tabs, accordions, and tooltips to improve the user experience.

## Technologies Used

- HTML5
- CSS3
- jQuery 3.7.1
- jQuery UI 1.13.2
- Skeleton CSS (Grid system)
- Cycle 2 Plugin (Image slideshow)

## What I Implemented

### Custom jQuery Plugins (js/)

- **Mobile Menu Plugin**: Changes the navigation menu into a dropdown on small screens
- **Sticky Plugin**: Keeps elements fixed on screen while scrolling
- **GoTop Plugin**: Adds a button that scrolls back to the top of the page

### Home Page (index.html)

- **Tabs**: Shows 3 product solutions in a tabbed layout (vProspect, vConvert, vRetain)
- **Accordion**: Displays client reviews in collapsible sections
- **Tooltips**: Shows helpful text when hovering over menu items
- **Mobile Menu**: Makes navigation work on phones

### About Us Page (aboutus.html)

- **Vertical Tabs**: Lists 5 team members in side-by-side tabs
- **Class Changes**: Used `.addClass()` and `.removeClass()` to style vertical tabs
- **Image Slideshow**: Auto-playing slideshow of 5 building photos using Cycle 2
- **Prev/Next Buttons**: Lets users manually move through slideshow images

### Solutions Page (solutions.html)

- **Sticky Navigation**: Quick Nav menu stays visible while scrolling down
- **Accordion**: Links to jump to different product sections
- **Back-to-Top Button**: Smooth scroll back to page top

### Contact Us Page (contactus.html)

- **Styled Checkboxes**: Made 3 checkboxes look better with jQuery UI
- **Styled Radio Buttons**: Made 4 radio buttons look better
- **Styled Dropdown**: Improved the company size select menu
- **Styled Button**: Made the submit button match the theme

### CSS and Layout

- **Grid System**: 960px wide page with 16 columns
- **Responsive Design**: Works on desktop, tablet, and mobile
- **jQuery UI Theme**: Uses the Smoothness theme for consistent styling

## Learnings

- Building custom jQuery plugins with options
- Using jQuery UI widgets (Tabs, Accordion, Tooltip)
- Changing widget styles using `.addClass()` and `.removeClass()`
- Adding image slideshows with the Cycle 2 plugin
- Making elements stick while scrolling
- Building mobile-friendly navigation menus
- Using `$(document).ready()` to run code when the page loads
- Styling form elements with jQuery UI

---

**Course:** CS 648 - Modern Web Development Frameworks<br>
**University:** San Diego State University (SDSU)<br>
**Author:** Merlyn Mercylona M
