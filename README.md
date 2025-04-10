# TechMart E-Commerce Website

## Overview
TechMart is a responsive e-commerce website template for selling technology products. It features a clean, modern design with a purple color scheme and is built using Bootstrap 5. The website includes a homepage and five category pages Laptops, Smartphones, Accessories, Smart Home, and Gaming.



## Features
- Responsive design that works on mobile, tablet, and desktop
- Purple-themed color scheme
- Bootstrap 5 framework for layout and components
- Product category pages with 5 products each
- Interactive navigation with dropdown menus
- Newsletter signup form
- Contact form
- About section
- Footer with social media links and site navigation

## Technologies Used
- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons
- JavaScript [minimal, via Bootstrap]



### Setup Instructions
1. Open the project folder in your code editor
2. Open `index.html` in your web browser to view the website


## File Structure

TechMart/
├── index.html          # Homepage
├── laptops.html        # Laptops category page
├── smartphones.html    # Smartphones category page
├── accessories.html    # Accessories category page
├── smart-home.html     # Smart Home category page
├── gaming.html         # Gaming category page
└── README.md           # Project documentation

## Usage

### Viewing the Website
Open `index.html` in your web browser to view the homepage. From there, you can navigate to different category pages using the navigation menu.

### Navigation
- The main navigation bar at the top allows users to access different sections of the website
- The "Products" dropdown menu provides access to all product categories


### Changing Colors

```css
:root {
    --primary-color: #8b5cf6;  /* Main purple color */
    --primary-dark: #7c3aed;   /* Darker purple for hover states */
    --primary-light: #a78bfa;  /* Lighter purple for accents */
    --secondary-color: #6d28d9; /* Secondary purple color */
    --light-color: #f8f9fa;    /* Light background color */
    --dark-color: #212529;     /* Dark text color */
}
