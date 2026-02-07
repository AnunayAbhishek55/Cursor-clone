# Cursor Website Clone (Desktop Only)

A desktop-only clone of the Cursor homepage built using pure HTML and CSS.

This project focuses on recreating the structure, layout, typography, spacing, and color system of the original Cursor website without using JavaScript, TailwindCSS, responsiveness, or animations.

---

## 🚀 Project Overview

This clone replicates the major sections of the Cursor homepage while maintaining:

- Clean and structured layout
- Accurate visual hierarchy
- Consistent typography
- Reusable color system
- Component-based section design

The implementation strictly follows the desktop-only constraint.

---

## 🧱 Sections Recreated

The following sections from the original Cursor website were recreated:

1. **Sticky Navigation Bar**
   - Logo
   - Navigation links
   - Sign In button
   - Download button

2. **Hero Section**
   - Main headline
   - Supporting description
   - Call-to-action button
   - Product hero image

3. **Trusted By Section**
   - Supporting text
   - Company logos grid

4. **Feature Sections**
   - Agent turns ideas into code
   - Magically accurate autocomplete
   - In every tool, at every step
   - Alternating image-text layout structure

5. **Testimonials Section**
   - Quote cards
   - Author images
   - Role and company details
   - Grid-based layout

6. **Stay on the Frontier Section**
   - Feature highlight cards
   - Image-based content blocks

7. **Changelog Section**
   - Version labels
   - Release titles
   - Release dates

8. **Research Section**
   - Split layout (Image + Text)

9. **Recent Highlights Section**
   - Blog-style preview cards
   - Metadata and titles
   - View more link

10. **Call-To-Action Section**
    - Large heading
    - Download button

11. **Footer**
    - Multi-column layout
    - Product / Resources / Company / Legal / Connect sections
    - Bottom bar with language selector and theme toggle

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
```

---

## 🎨 Color Palette

The project uses CSS custom properties (`:root`) to maintain consistency across the design.

### Background Colors
- **Main Background:** `#13120A`
- **Section Card Background:** `#18160d`
- **Alternate Background:** `#1B1912`
- **Highlight Cards:** `#201E18`

### Text Colors
- **Primary Text:** `#ffffff`
- **Muted Text:** `#a3a3a3`

### Accent Color
- **Brand Accent (Orange):** `#f54e00`

### Button Colors
- **Primary Button Background:** `#EDECEC`
- **Primary Button Text:** `#0d0d0d`
- **Button Hover:** `#d7d5d5`

All colors are managed using CSS variables for scalability and maintainability.

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
- Images and icons similar to original website
- Focused on structural and visual accuracy

---

## 🎯 Learning Outcomes

Through this project:

- Strengthened CSS layout fundamentals (Grid & Flexbox)
- Practiced recreating a production-level SaaS landing page
- Improved understanding of spacing, alignment, and hierarchy
- Implemented a structured design system using CSS variables
- Learned professional UI section structuring

---

## ⚠ Disclaimer

This project is created strictly for educational purposes.  
All design credits belong to the original Cursor website.
