# CS648 Assignment 10 - jQuery Plugins & jQuery UI Integration

## Overview

This project enhances the Vecta Corp website by integrating various jQuery plugins and jQuery UI components to create a more interactive and user-friendly experience.

## Features Implemented

### General Enhancements

- **Tooltip Widget**: Added descriptive tooltips to navigation menu items
  - Each of the 5 menu items displays unique text about Vecta Corp's solutions
  - Tooltips appear on hover: "Vecta Corp. offers 3 solutions for prospecting, converting, and retaining customers"

### Home Page

#### 1. Tabbed Interface for Solutions

- Implemented jQuery UI Tabs widget to organize the 3 Vecta Corp solutions
- Horizontal tabbed navigation for easy access
- Content displays dynamically when users click on each tab
- Positioned directly under "Our Solutions" heading

#### 2. Client Testimonials Accordion

- Added jQuery UI Accordion widget for the 2 client testimonials
- Collapsible sections with product images
- Located under "Client Testimonials" heading
- Smooth expand/collapse animations

### About Us Page

#### 1. Management Team Tabs

- jQuery UI Tabs widget dividing the 5 Vecta Corp managers
- Each tab displays individual manager bio and photo
- Positioned in the Management Team section under "Meet the Managers" heading

#### 2. Headquarters Image Slideshow

- Auto-rotating slideshow using Cycle 2 plugin
- Features the new Vecta Corp headquarters
- Includes user-friendly navigation controls
- Allows manual cycling through images with next/previous buttons
- Smooth transition effects between slides

### Solutions Page

#### 1. Solutions Content Display

- Formatted and enhanced content under "Our Solutions" heading
- Implemented Quick Nav feature for easy navigation between solutions

#### 2. Quick Nav Implementation

- Developed using jQuery Slideshow plugin
- Stays visible and playable when clicked
- Smooth scrolling navigation between different solutions
- Does not automatically advance

#### 3. Back to Top Functionality

- Integrated Google's jQuery Back to Top plugin
- Smooth scroll animation to page top
- Provides easy navigation for long content pages

### Contact Us Page

- Enhanced contact form with jQuery validation and styling
- Improved user experience with interactive form elements

## Technologies Used

- **jQuery**: Core JavaScript library for DOM manipulation
- **jQuery UI**: UI components (Tabs, Accordion, Tooltip)
- **Cycle 2 Plugin**: Image slideshow functionality
- **jQuery Slideshow Plugin**: Quick navigation feature
- **Back to Top Plugin**: Smooth scroll-to-top functionality
