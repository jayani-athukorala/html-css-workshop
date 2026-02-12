# SL Café Website

This is a simple website built with **HTML** and **CSS**, hosted on GitHub Pages:  
[Live Demo](https://jayani-athukorala.github.io/html-css-workshop/)

---

## Project Overview

SL Café website is designed to showcase a cozy Sri Lankan café. The website includes:

- **Intro Section:** Hero section with café name, tagline, and a welcome message.  
- **Menu Section:** Displays beverages with images and prices in a table layout.  
- **About Section:** Provides information about the café.  
- **Contact Section:** Allows to view contact information and send messages through a simple form.

The website is fully responsive and uses CSS Grid and Flexbox to organize sections and content.

---

## Steps Completed to Build the Project

### 1. HTML Structure

- Created a **fixed navbar** linking to each section (`#intro`, `#menu`, `#about`, `#contact`).  
- Used `<section>` elements for each major area: Intro, Menu, About, Contact.  
- For content grouping, wrapped text and images inside `<div>` containers.  
- Menu items are displayed using `<table>` for clear rows of images and descriptions.  
- Contact form uses `<form>` with `<input>` and `<textarea>` for user messages.  
- Footer placed at the bottom of the Contact section using a `<footer>` element.

### 2. CSS Styling

- **Global styles:**
  - Applied `scroll-behavior: smooth` for smooth scrolling.  
  - Set a consistent font (`Georgia`) for body text while keeping `h1` distinct.  
- **Navbar:**
  - Fixed at the top using `position: fixed`.  
  - Links styled with color, spacing, and hover effects.  
- **Intro Section:**
  - Used Flexbox to center content vertically and horizontally.  
  - Applied a semi-transparent background to the text container for readability.  
- **Menu Section:**
  - Used CSS Grid to create two columns for menu items.  
  - Menu header spans both columns.  
  - Each `.menu-items` div wraps a table and shrinks to fit its table size.  
- **About Section:**
  - Grid layout with two columns; content aligned in the second half.  
  - Semi-transparent background applied to text for contrast against background image.  
- **Contact Section:**
  - Grid layout with two columns: contact information and email form.  
  - Added `padding-top` to avoid overlap with fixed navbar.  
  - Form inputs styled with only bottom borders for modern look.  
  - Button styled with café theme color (`#CC9966`).  
- **Footer:**
  - Spans both columns and centered at the bottom of the section.

### 3. Responsive Design

- Sections use `min-height: 100vh` for full-screen effect.  
- Flexbox and CSS Grid ensure content centers properly across different screen sizes.  
- Tables and divs use `width: max-content` or `inline-block` to shrink to fit content.  

---

## Features

- Smooth scroll navigation between sections  
- Modern café-style layout with semi-transparent text backgrounds  
- Menu tables with images and prices  
- Contact form with minimalist underline-only inputs  
- Fixed navbar that stays visible while scrolling  

---

## Technologies Used

- **HTML5**: Semantic structure for sections, tables, and forms  
- **CSS3**: Grid, Flexbox, styling, backgrounds, hover effects  
- **GitHub Pages**: Hosted live site  

---

## How to View Locally

1. Clone the repository:

```bash
git clone https://github.com/jayani-athukorala/html-css-workshop.git
