# Cursor Website Clone (Desktop Only)

A desktop-only clone of the Cursor homepage built using pure HTML and CSS.

This project focuses on accurately recreating the structure, layout, typography, and visual design of the original website without using JavaScript, TailwindCSS, responsiveness, or animations.

---

## 🚀 Project Overview

This clone replicates the core sections of the Cursor homepage with close attention to:

- Layout structure
- Typography
- Color palette
- Spacing system
- Component styling
- Visual hierarchy

The project is built strictly for desktop view as per the given constraints.

---

## 🧱 Sections Recreated

The following sections from the original website were recreated:

1. **Sticky Header / Navigation Bar**
   - Logo
   - Navigation links (Product, Enterprise, Pricing, Resources)
   - Sign In button
   - Download button

2. **Hero Section**
   - Main headline
   - Download CTA button
   - Hero product image

3. **Trusted By Section**
   - Supporting text
   - Company logos grid

4. **Feature Sections**
   - Agent turns ideas into code
   - Magically accurate autocomplete
   - In every tool, at every step
   - Alternating image/text layout

5. **Testimonials Section**
   - Grid layout
   - Quote cards
   - Author images and roles

6. **Stay on the Frontier Section**
   - Three feature cards
   - Image-based content blocks

7. **Changelog Section**
   - Version badges
   - Release dates
   - Update titles

8. **Research Section**
   - Split layout
   - Image + text panel

9. **Recent Highlights Section**
   - Blog-style cards
   - Metadata
   - View more link

10. **Call-To-Action Section**
    - Large heading
    - Download button

11. **Footer**
    - Multi-column layout
    - Product / Resources / Company / Legal / Connect
    - Bottom bar with theme toggle and language selector

---

## 🎨 Fonts Used

### Primary Font:
**Cursor Gothic**

Loaded locally using `@font-face`:

- CursorGothic-Regular
- CursorGothic-Italic
- CursorGothic-Bold
- CursorGothic-BoldItalic

Font fallback stack:
```css
CursorGothic, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

---

## 🎨 Color Palette

The project uses CSS variables for consistent theming and better maintainability.

### Background Colors
- **Main Background:** `#13120A`
- **Section Cards:** `#18160d`
- **Alternate Section Background:** `#1B1912`
- **Highlight Cards:** `#201E18`

### Text Colors
- **Primary Text:** `#ffffff`
- **Muted Text:** `#a3a3a3`

### Accent Color
- **Brand Accent (Orange):** `#f54e00`

### Button Colors
- **Primary Button Background:** `#EDECEC`
- **Primary Button Text:** `#0d0d0d`
- **Button Hover State:** `#d7d5d5`

All colors are defined using CSS custom properties (`:root`) to ensure consistency, scalability, and easier future updates.

---

## 🛠 Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Variables
- Custom Font Loading via `@font-face`

---

## 📌 Constraints Followed

- Desktop-only layout
- No responsiveness
- No JavaScript
- No TailwindCSS
- No animations
- Layout closely matches original design
- Images and icons similar to original website

---

## 🎯 Learning Outcomes

Through this project:

- Practiced recreating a production-level UI using only HTML & CSS
- Improved understanding of CSS Grid and Flexbox layouts
- Worked with custom fonts and CSS variables
- Strengthened spacing, alignment, and visual hierarchy skills
- Gained experience building structured landing pages

---

## ⚠ Disclaimer

This project is created strictly for educational purposes.  
All design credits belong to the original Cursor website.
