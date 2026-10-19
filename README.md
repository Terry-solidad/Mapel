# Mapel

# ☕ Maple & Mortar — Coffee Shop & Bakery Website

**A warm neighborhood cafe experience, built for the web.**

Maple & Mortar is a fictional neighborhood coffee shop and bakery specializing in small-batch espresso, single-origin pour-over coffee, and freshly baked, house-made pastries. This website introduces the cafe, showcases its menu, shares its story, and helps customers plan their visit.

The design reflects the cafe's rustic atmosphere and welcoming identity, positioning it as a comfortable third place between home and work.

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Website Pages](#-website-pages)
- [Design System](#-design-system)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Getting Started](#-getting-started)
- [Validation and Testing](#-validation-and-testing)
- [Accessibility](#-accessibility)
- [Future Improvements](#-future-improvements)
- [License](#-license)

## 🌿 Project Overview

The goal of Maple & Mortar is to establish a welcoming online presence for a neighborhood cafe. The website provides customers with essential information about the business while maintaining a consistent, elegant, and responsive design.

**Target audience:**
- Commuters and local residents looking for quality coffee.
- Students and remote workers seeking comfortable seating and Wi-Fi.
- Weekend visitors interested in pastries and specialty coffee.
- Individuals and groups looking to reserve space for private gatherings.

## ✨ Features

- **Welcoming homepage:** A hero section, cafe introduction, featured brews, weekly specials, and customer testimonials.
- **Categorized menu:** A structured menu table displaying product names, descriptions, categories, and prices.
- **Cafe story:** Information about the cafe's origins, values, coffee philosophy, and team.
- **Visit and contact page:** Location details, opening hours, and a reservation or event inquiry form.
- **Consistent navigation:** A shared header and footer across all pages.
- **Responsive layout:** Flexbox-based content layouts that adapt to smaller screens.
- **Photography:** Descriptive images of coffee, pastries, the cafe interior, and baristas.
- **External stylesheet:** All visual styling is maintained in a single `styles.css` file.
- **Interconnected pages:** Every page links to the other pages for easy navigation.

## 📄 Website Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Cafe introduction, featured drinks, specials, and testimonials. |
| Menu | `menu.html` | Categorized food and beverage menu with pricing. |
| About | `about.html` | Brand story, values, team, and coffee philosophy. |
| Visit | `visit.html` | Location, opening hours, reservations, and event inquiries. |

## 🎨 Design System

### Color Palette

The visual identity uses warm, natural colors inspired by coffee, maple wood, and a rustic cafe interior.

| Color | Purpose |
|---|---|
| Espresso Brown | Primary headings, navigation, and dark backgrounds. |
| Warm Cream | Main page backgrounds and light content sections. |
| Maple Amber | Buttons, highlights, and interactive accents. |
| Sage Green | Secondary accents and natural visual details. |
| Stone Neutrals | Borders, muted text, and supporting elements. |

### Typography

- **Playfair Display:** Used for headings to create an elegant, editorial feel.
- **Inter:** Used for body text, navigation, forms, and general interface elements.

Both fonts include appropriate fallback font stacks to support readability when the preferred fonts are unavailable.

### Layout

- Centered `.container` wrapper for consistent page alignment.
- Flexbox-based layouts for multi-column content.
- Responsive single-column layouts on smaller screens.
- Consistent spacing, typography, and visual hierarchy across pages.
- Descriptive image alternative text for meaningful photographs.

## 📁 Project Structure

```text
maple-and-mortar/
│
├── index.html          # Homepage
├── menu.html           # Food and beverage menu
├── about.html          # Cafe story and team
├── visit.html          # Location, hours, and contact form
├── styles.css          # Shared external stylesheet
├── images/             # Website photography and image assets
│   ├── cafe-interior.jpg
│   ├── latte-art.jpg
│   ├── pastries.jpg
│   └── barista.jpg
└── README.md           # Project documentation
```

*Note: The image filenames above are examples. Update them to match the actual files in your project.*

## 🛠️ Technologies Used

- **HTML5** — Semantic structure and website content.
- **CSS3** — Styling, typography, colors, responsive layouts, and Flexbox.
- **Google Fonts** — Playfair Display and Inter, with fallback font stacks.
- **Photography assets** — Visual storytelling and cafe branding.
- **Git and GitHub** — Optional version control and project hosting.

The website uses a shared external stylesheet and does not require JavaScript or a backend for its basic static pages.

## 🚀 Getting Started

### 1. Download or Clone the Project

If the project is hosted on GitHub, clone the repository:

```bash
git clone terry1703.github.io/Mapel/

```


Alternatively, download the project files and extract them into a folder named `maple-and-mortar`.

### 2. Open the Project

Open the project folder in Visual Studio Code.

Ensure the folder contains the four HTML pages, `styles.css`, and the image assets used by the website.

### 3. Launch the Website

Open `index.html` in your browser.

For a convenient local development experience, you can use the **Live Server** extension in Visual Studio Code:

1. Open `index.html`.
2. Right-click inside the editor.
3. Select **Open with Live Server**.
4. Navigate through the website using the header links.

### 4. Check the Stylesheet

Each HTML page should reference the same external stylesheet inside its `<head>` element:

```html
<link rel="stylesheet" href="styles.css">
```

This keeps the appearance consistent across all four pages.

## 🧪 Validation and Testing

The website should be checked against the following criteria before publication:

- **HTML validation:** Use the [W3C HTML Validator](https://validator.w3.org/) to identify markup errors.
- **CSS validation:** Use the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to check stylesheet syntax.
- **Browser compatibility:** Test the website in Chromium-based browsers and Mozilla Firefox.
- **Navigation testing:** Confirm that all internal links connect to the correct pages.
- **Image testing:** Check that image paths work and alternative text is meaningful.
- **Responsive testing:** Inspect the website at desktop, tablet, and mobile screen sizes.
- **Form testing:** Check required fields and input behavior. A working submission process requires a backend or a connected form service.
- **Accessibility checks:** Confirm readable contrast, keyboard accessibility, and clear form labels.

## ♿ Accessibility

Maple & Mortar aims to provide an inclusive browsing experience through:

- Semantic HTML elements and a logical heading hierarchy.
- Descriptive alternative text for meaningful images.
- Explicit labels for form controls.
- Readable typography and sufficient color contrast.
- Clear, descriptive navigation links.
- Keyboard-accessible interactive elements.
- Responsive layouts that work across different screen sizes.

## 🔮 Future Improvements

Potential enhancements include:

- Online ordering and takeaway functionality.
- A real-time table reservation system.
- Private event booking and inquiry management.
- A customer review and testimonial management system.
- An interactive map with directions to the cafe.
- A gallery featuring seasonal drinks and bakery products.
- Backend integration for processing contact and reservation submissions.
- Search engine optimization and website analytics.

## 📜 License

This project is created for educational and demonstration purposes. Maple & Mortar is a fictional business, and any sample menu items, prices, contact details, opening hours, or testimonials should be treated as illustrative unless verified.

If the project is published or reused, ensure that all photographs, fonts, and other third-party assets comply with their respective licenses.

---

**Maple & Mortar — Good coffee. Fresh pastries. A place to belong.** ☕

