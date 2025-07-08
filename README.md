# Brissy Climate Change 🌏🌱

**Brissy Climate Change** is an interactive, educational, and action-driven website designed to raise awareness about climate change impacts specific to Brisbane, Australia.  
This site was developed as part of a **Design Thinking** project to engage citizens, promote climate action, and connect the community with resources and events.

---

## 🌟 Purpose

This website was developed for the **2008ICT: Design Thinking in IT** course. Its objectives include:

- Educating Brisbane locals on the impacts of climate change.  
- Inspiring individual and community-level action.  
- Showcasing upcoming events and donation options.  
- Demonstrating design thinking principles through digital interaction.

---

## 🧩 Features

- **Homepage**: Core climate messages and easy navigation.  
- **Take Action Page**: Interactive layout with icons and animations representing lifestyle changes like conserving energy, using public transport, reducing plastic, and more.  
- **Donate for Climate Wealth**: A dedicated donation section integrated into the site’s main menu.  
- **Events & Community**: Highlights Brisbane-specific eco-events and campaigns.  
- **Visual Appeal**: Uses animated elements, icons, and modern UI styling.  
- **Prototyping Process**: Includes low-fidelity sketches and user journey development.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (with animations), JavaScript  
- **Design Tools**: Figma (for wireframes & low-fi prototypes)  
- **[Optional]**: React / Bootstrap / WordPress (if expanded)

---

## 📣 How to Quickly Explain the Code

When showcasing or submitting the website, you can explain the code like this:

- **HTML Files**: Each page (`index.html`, `take-actions.html`, `donate.html`) contains the layout and content structure using semantic HTML5 tags.  
- **CSS (`style.css`)**: Styles the pages, adds layout responsiveness, and includes animations for icons and buttons.  
- **JavaScript (`scripts.js`)**: Enhances user interaction (e.g., menu toggles, form validations, or future dynamic features).  
- **Assets Folder**: Contains all supporting files like icons, images, and reusable design elements.  
- **Navigation**: Built with simple internal links (`<a href="...">`) across a shared navbar included in each page.

> 🔹 *Each page has its own focus, but they all follow a consistent structure. The styling is handled in one central CSS file, and any interactivity is managed in the JS file. The whole project can be run directly in a browser without setup.*

---

## 📈 Future Enhancements

- Connect to real-time climate data or news feeds.  
- Add backend for managing event listings and donation tracking.  
- Convert into a React app or WordPress plugin for scalability.  
- Improve accessibility (ARIA, contrast, screen reader support).  
- Add a blog or newsfeed section.

## 📈 Future Enhancements

- Connect to real-time climate data or news feeds.  
- Add backend for managing event listings and donation tracking.  
- Convert into a React app or WordPress plugin for scalability.  
- Improve accessibility (ARIA, contrast, screen reader support).  
- Add a blog or newsfeed section.

## HTML

- Uses semantic tags: `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`
- Includes comment blocks to organize structure:
  ```html
<!-- === VLAN Status Dashboard === -->
CSS
Structured with comment blocks for each section:

 ## CSS

/* === Layout === */

/* === Color Theme === */

/* === Device Cards === */

Uses custom properties:

 ## CSS

:root {
  --primary-color: #0055aa;

  --accent-color: #ffaa00;
}

Follows BEM naming convention for maintainable classes:
 
Example: .device-card__status--online


 
## 🔧 Maintenance & Extension Guide

To Add New Features:

New HTML Pages: Duplicate index.html, link the same style.css
 
New Styles: Add new section comments in style.css, follow naming convention
 
New Images/Assets: Place inside assets/images/ or assets/icons/
 
Future Enhancements (Optional):

JavaScript for dynamic status updates or modals
 
Interactive elements (e.g., VLAN selection)
 
Dark mode toggle with CSS variables
 
Backend integration to fetch live network data
 
## 🧪 Testing

✅ Validated HTML using W3C Validator
 
✅ CSS linted for formatting consistency
 
✅ Tested in:
 
Chrome
 
Firefox
 
Microsoft Edge
 
### 📄 Versioning

Semantic versioning used:
 
v1.0.0 — Initial stable release
 
All updates tracked in CHANGELOG.md
