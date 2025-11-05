# CS648 Assignment 10 - jQuery Plugins & jQuery UI Integration

## Overview

This project enhances the Vecta Corp website by integrating various jQuery plugins and jQuery UI components to create a more interactive and user-friendly experience.

## Features Implemented

### General Enhancements (All Pages)

- **Tooltip Widget**: Added descriptive tooltips to all navigation menu items

  - Implemented using `$(document).tooltip()`
  - Each menu item displays unique descriptive text on hover
  - Examples:
    - Home: "Vecta corporation Home page."
    - About Us: "Vecta corporation Team details."
    - Solutions: "Vecta Corp. offers 3 solutions for prospecting, converting, and retaining customers."
    - Support: "We are here for your help"
    - Contact Us: "The vecta corp contact details is here."

- **Mobile Menu**: Responsive navigation using custom `mobileMenu()` plugin
  - Converts navigation to dropdown select menu on screens < 480px
  - Implemented on all pages with `$('#responsive-menu').mobileMenu()`

### Home Page (index.html)

#### 1. Tabbed Interface for Solutions

- Implemented jQuery UI Tabs widget for the 3 Vecta Corp solutions
- Horizontal tabbed navigation under "Our Solutions" heading
- Three tabs: vProspect 2.0, vConvert 2.0, vRetain 1.0
- Each tab displays solution logo and description
- JavaScript: `$("#tabs").tabs()`

#### 2. Client Testimonials Accordion

- jQuery UI Accordion widget for 2 client testimonials
- Collapsible sections for testimonials from Iona Ford and Robin Banks
- Located under "Client Testimonials" heading
- Smooth expand/collapse animations
- JavaScript: `$("#accordion").accordion()`

### About Us Page (aboutus.html)

#### 1. Management Team Vertical Tabs

- jQuery UI Tabs widget styled as vertical navigation
- Displays 5 Vecta Corp managers: Agnes, Damon, Herbert, Mike, and Wilbur
- Each tab shows manager's role and biography
- Custom CSS styling for vertical tab layout
- JavaScript:

```javascript
$("#tabs").tabs().addClass("ui-tabs-vertical ui-helper-clearfix");
$("#tabs li").removeClass("ui-corner-top").addClass("ui-corner-left");
```

#### 2. Headquarters Image Slideshow

- Auto-rotating slideshow using Cycle 2 plugin
- Features 5 images of the new Vecta Corp headquarters
- Manual navigation with Previous/Next buttons
- Configuration:
  - Effect: `scrollHorz` (horizontal scroll)
  - Speed: 200ms
  - Pause on hover enabled
- HTML5 data attributes for configuration

### Solutions Page (solutions.html)

#### 1. Solutions Content Display

- Detailed content for all three solutions (vProspect, vConvert, vRetain)
- Each solution in its own div with unique ID for navigation

#### 2. Quick Nav Sidebar

- Sticky navigation panel using `jquery.sticky.js` plugin
- Accordion widget for organizing Quick Nav links
- Links to each solution section: vProspect 2.0, vConvert 2.0, vRetain 1.0
- Remains visible while scrolling
- JavaScript: `$("#sticky").sticky()` and `$("#accordion").accordion()`

#### 3. Back to Top Functionality

- Custom "Back to Top" button using `jquery.goTop.js` plugin
- Appears after scrolling down 100px
- Smooth scroll animation to page top (1000ms)
- Fade in/out effects (1000ms fade in, 500ms fade out)
- JavaScript: `$('#goTop').goTop()`

### Contact Us Page (contactus.html)

- Enhanced form with jQuery UI widgets:
  - Radio buttons styled with `checkboxradio()`
  - Checkboxes styled with `checkboxradio()`
  - Select menu enhanced with `selectmenu()`
  - Submit button styled with `button()`
- Form validation with HTML5 attributes (required, pattern, etc.)

### Support Page (support.html)

- Basic page with tooltip navigation
- Contact email link with pre-filled subject line
- Minimal jQuery implementation (just tooltips and mobile menu)

## Technologies Used

- **jQuery 1.11.0 / 3.4.1 / 3.7.1**: Core JavaScript library
- **jQuery UI 1.12.1 / 1.13.2**: UI components (Tabs, Accordion, Tooltip, Checkboxradio, Selectmenu, Button)
- **Cycle 2 Plugin**: Image slideshow functionality
- **jquery.sticky.js**: Sticky positioning for sidebar navigation
- **jquery.goTop.js**: Smooth scroll-to-top functionality
- **jquery.mobilemenu.js**: Custom responsive navigation plugin

## Key jQuery Plugins Used

### 1. Mobile Menu Plugin (Custom)

```javascript
$("#responsive-menu").mobileMenu();
```

### 2. jQuery UI Tabs

```javascript
$("#tabs").tabs();
```

### 3. jQuery UI Accordion

```javascript
$("#accordion").accordion();
```

### 4. jQuery UI Tooltip

```javascript
$(document).tooltip();
```

### 5. Cycle 2 Slideshow

```html
<div
  class="cycle-slideshow"
  data-cycle-fx="scrollHorz"
  data-cycle-pause-on-hover="true"
  data-cycle-speed="200"
></div>
```

### 6. Sticky Plugin

```javascript
$("#sticky").sticky();
```

### 7. Go Top Plugin

```javascript
$("#goTop").goTop();
```
