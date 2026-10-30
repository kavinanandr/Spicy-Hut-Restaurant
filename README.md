# 🌶️ Spicy Hut Restaurant Website

A modern, fully responsive single-page front-end website built for **Spicy Hut**, a fictional restaurant. The application showcases brand offerings through an organized dining menu, multi-location listings, and an interactive social media footer.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [File Structure](#-file-structure)
- [Getting Started](#-getting-started)
- [Key Implementation Details](#-key-implementation-details)
- [Author](#-author)

---

## 📖 Overview

Spicy Hut is a sleek, component-driven UI layout designed to deliver a smooth digital experience for restaurant patrons. It features a full-screen landing view, categorized item grids for starters, main courses, and chaats, multi-branch addresses across Chennai, and animated social media tooltips.

---

## ✨ Features

- **Full-Screen Hero / Landing Section**: Clean navigation container complete with brand identity, tagline styling, and call-to-action buttons.
- **Categorized Dining Menu**:
  - Divided into **Starters**, **Main Course**, and **Chats** sections.
  - Itemized pricing in Indian Rupees (`₹`).
  - Fluid responsiveness using a CSS Grid layout (`repeat(auto-fit, minmax(256px, 1fr))`).
- **Branch Directory**:
  - Highlights physical storefront locations across **Anna Nagar**, **Velachery**, and **Tambaram**.
  - Structured semantic markup utilizing `<address>` tags.
- **Interactive Social Media Footer**:
  - Circular icon buttons styled with smooth hover transitions and custom cubic-bezier timing.
  - Interactive floating tooltips for Facebook, Twitter, and Instagram.

---

## 🛠️ Technologies Used

- **HTML5**: Semantic elements (`<section>`, `<nav>`, `<address>`, `<table>`, `<footer>`)
- **CSS3**: 
  - CSS Custom Properties (`:root` variables)
  - Flexbox and CSS Grid layouts
  - Custom transition cubic-beziers and box-shadows
- **Google Fonts**: Poppins typography integration
- **Font Awesome 6**: Vector icon support for social branding

---

## 📁 File Structure

```text
Spicy-Hut-Restaurant/
├── img/
│   ├── bg.jpg               # Hero background imagery
│   └── favicon.ico          # Browser tab icon / branding icon
├── index.html               # Main webpage structure
├── style.css                # Styling, themes, layouts, and animations
└── README.md                # Project documentation

---

🚀 Getting StartedPrerequisites

Ensure you have a modern web browser (e.g., Google Chrome, Firefox, Edge, Brave) installed.Installation & SetupClone the repository:git clone https://github.com/kavinanandr/Spicy-Hut-Restaurant.git
Navigate into the project directory:cd Spicy-Hut-Restaurant
Open the project:Double-click index.html to open it directly in your web browser.Alternatively, serve it locally using the VS Code Live Server extension (http://127.0.0.1:5500).🔍 Key Implementation DetailsHTML <head> Setup & Asset LinkingInclude both your favicon and the Font Awesome CDN inside your <head> tag to render page branding and social media icons correctly:<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Kavin Anand">
    <meta name="description" content="A Fully Responsive Restaurant Website">
    <title>Spicy Hut - Restaurant in Chennai</title>

    <!-- Favicon -->
    <link rel="icon" type="image/x-icon" href="img/favicon.ico">

    <!-- Font Awesome CDN -->
    <link 
      rel="stylesheet" 
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" 
      integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" 
      crossorigin="anonymous" 
      referrerpolicy="no-referrer" 
    />

    <!-- Stylesheet -->
    <link rel="stylesheet" href="style.css">
</head>
Color Palette ReferenceVariable TokenColor ValuePreview--WHITEwhitesmoke #f5f5f5--REDcrimson #dc143c--GREEN#53bf9d #53bf9d--YELLOW#ffc54d #ffc54d👤 AuthorKavin AnandGitHub: @kavinanandr 

##fgegg