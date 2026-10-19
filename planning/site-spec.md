# Maple & Mortar — Site Specification & Sitemap

## 1. Client

**Maple & Mortar** — a fictional neighborhood coffee shop and bakery that
specializes in small-batch espresso, single-origin pour-overs, and
house-made pastries. The shop has a warm, rustic interior and positions
itself as a "third place" between home and work.

## 2. Purpose

To give Maple & Mortar an online presence that:

- Introduces the cafe to new and returning customers.
- Presents the full menu with clear pricing.
- Tells the brand story and the people behind the coffee.
- Lets visitors find the location, hours, and reserve a table or request
  a private event.

## 3. Target Audience

- Commuters and locals looking for a daily coffee stop.
- Students and remote workers who need seating, WiFi, and good light.
- Weekend visitors seeking brunch-style pastries and a cozy atmosphere.
- Event hosts exploring the space for small private gatherings.

## 4. Page Breakdown

| Page        | File          | Purpose                                                              |
| ----------- | ------------- | ------------------------------------------------------------------- |
| Home        | index.html    | Hero welcome, intro, featured brews, weekly specials, testimonial.  |
| Menu        | menu.html     | Full menu presented as a styled, categorized data table.            |
| About       | about.html    | Origin story, values, the team, and what makes the coffee special.  |
| Visit       | visit.html    | Location, hours table, and a reservation / contact form.            |

## 5. Sitemap

```
                +-------------------+
                |   Home            |
                |   index.html      |
                +---------+---------+
                          |
        +-----------------+-----------------+
        |                 |                 |
+-------+-------+ +-------+-------+ +-------+-------+
|   Menu        | |   About       | |   Visit       |
|   menu.html   | |   about.html  | |   visit.html  |
+---------------+ +---------------+ +---------------+
```

All pages share a site-wide header navigation bar and footer. Every page
links to every other page, so the structure is fully interconnected.

## 6. Design System

- **Fonts:** Playfair Display (headings, serif) + Inter (body, sans-serif),
  each with full fallback font stacks.
- **Color palette:** espresso brown, warm cream, maple amber accent, sage
  green, and stone neutrals.
- **Layout:** centered `.container` wrapper, multi-column content grids
  using flexbox wrapper divs, responsive single-column stack on mobile.
- **Assets:** real photography (coffee shop interior, latte art, pastries,
  barista) with descriptive `alt` text.
- **Single external stylesheet:** `styles.css`, linked from every page.
  No inline styles are used anywhere in the site.

## 7. Validation & Testing Plan

- HTML validated with the W3C validator.
- CSS validated with the W3C Jigsaw validator.
- Tested in Chromium-based and Firefox browsers.
- All internal links and image sources checked for broken references.
