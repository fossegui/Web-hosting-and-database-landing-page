# 🚀 Bank Box - Hosting and Database Landing Page

Site: https://web-hosting-and-database-landing-pa-nine.vercel.app/

> **Bank Box** is a modern, responsive, and high-performance landing page developed to showcase database storage services, web hosting,
> and domain search solutions.

---

## 📌 Table of Contents
- [Demo](#-demo)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [HTML Code Overview](#-html-code-overview)
- [CSS Concepts & Styling](#-css-concepts--styling)
- [How to Run the Project](#-how-to-run-the-project)
- [Author](#-author)

---

## 💻 Demo

*(Tip: Add an image or GIF of your running project here)*
`![Bank Box Preview](./img/preview.png)`

---

## ✨ Features

- **Navbar Navigation Menu:** Fixed header featuring logo and quick links (*Home*, *Pricing*, *Contact*, and a *Sign In* button).
- **Hero Section (Main Banner):** Eye-catching welcome banner with custom background styling and impactful text.
- **Services Section:** Displays key value propositions (Security, Performance, and 24/7 Support) utilizing clean icon design and *Flexbox*.
- **Pricing & Plans Table:** Clear presentation of 4 pricing plans (Basic, Dedicated, Dedicated Plus, and Cloud) with visual highlights for the recommended option.
- **Domain Search:** Interactive section for checking domain availability.
- **Contact Form:** Direct communication form to get in touch with an expert.
- **Fully Responsive Layout:** Built using *Media Queries* to ensure optimal viewing across Desktop, Tablet, and Mobile screens.

---

## 🛠️ Technologies Used

Built from scratch using the following core technologies:

- **[HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML):** Semantic structure and layout accessibility.
- **[CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS):** Custom styling, flexible layouts (Flexbox), hover states, and responsive breakpoints.
- **[Font Awesome 5/6](https://fontawesome.com/):** Vector icons library used in the features section.

---

## 📂 Project Structure

```
├── css/
│   └── style.css       # Main stylesheet
├── img/
│   ├── hdchostlogo.png # Brand logo
│   └── mainbanner.png  # Hero background image
├── index.html          # Main HTML document
└── README.md           # Project documentation
```
---

## 🔍 HTML Code Overview

The index.html file follows clean semantic guidelines for better accessibility and SEO:
1.	<nav> / .navbar-container: Contains the logo and primary navigation links.
2.	<main>: Wraps the main landing content:
o	.main-banner: High-impact hero section.
o	.services-container: Key business highlights.
o	.pricing-container: Plan options presented in card layouts.
o	.searchdomain-container: Quick domain lookup bar.
o	.contact-container: Direct contact form.
3.	<footer>: Copyright notice and author credits.

---

## 🎨 CSS Concepts & Styling

Technical highlights from style.css:

•	Flexbox (display: flex): Used extensively to arrange feature cards and pricing columns evenly.
•	Relative/Absolute Positioning: Utilized for circular badge overlaps on pricing tags (.price).
•	Media Queries (@media): Ensures smooth responsiveness:
o	Up to 1100px: Adjusts container widths and side margins for pricing cards.
o	Up to 900px: Optimizes padding and text scaling for tablet screens.
o	Up to 576px: Switches multi-column flex layouts to single-column (flex-direction: column) for mobile usability.

---

## 🚀 How to Run the Project

1.	Clone this repository:
Bash
git clone [https://github.com/your-username/bank-box.git](https://github.com/your-username/bank-box.git)

2.	Navigate to the project folder:
Bash
cd bank-box

3.	Open in browser:
o	Double-click index.html or use the Live Server extension in VS Code.

---

## 👨‍💻 Author

Developed by Guilherme Pereira de Jesus.

•	🏢 GitHub: @fossegui
© 2026 Guilherme Pereira de Jesus - All rights reserved.


