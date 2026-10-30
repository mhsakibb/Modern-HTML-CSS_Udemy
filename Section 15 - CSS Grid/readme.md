
<h1 align="center">CSS Grid</h1>

<p align="center">
  <strong>Master Modern Two-Dimensional Layouts with CSS Grid</strong>
</p>

<p align="center">
  Learn to build flexible and responsive layouts using CSS Grid — from defining rows and columns to positioning items and creating complete page layouts.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/CSS-Grid-663399?style=for-the-badge" alt="CSS Grid" />
</p>

---

## Section Overview

This section of **Modern HTML & CSS From The Beginning 2.0** focuses on mastering CSS Grid, a powerful two-dimensional layout system for organizing web content into rows and columns.

Through 12 practical exercises, this section covers grid columns, rows, flexible track sizing, alignment, item positioning, named grid lines, responsive layouts, and grid template areas.

It also includes two grid challenges and a practical **Lumina Creative Grid Refactor**, where CSS Grid is applied to redesign a creative agency's portfolio gallery.

## Repository Structure

```text
Section 15 - CSS Grid/
│
├── 01_grid-columns/
│   ├── index.html
│   └── styles.css
│
├── 02_repeat-minmax-functions/
│   ├── index.html
│   └── styles.css
│
├── 03_grid-rows/
│   ├── index.html
│   └── styles.css
│
├── 04_grid-challenge-1/
│   ├── index.html
│   └── styles.css
│
├── 05_align-justify-properties/
│   ├── index.html
│   └── styles.css
│
├── 06_autofit-autofill-repeat/
│   ├── index.html
│   └── styles.css
│
├── 07_positioning-spanning-items/
│   ├── index.html
│   └── styles.css
│
├── 08_named-grid-lines/
│   ├── index.html
│   └── styles.css
│
├── 09_grid-challenge-2/
│   ├── index.html
│   └── styles.css
│
├── 10_grid-media-querie/
│   ├── index.html
│   └── styles.css
│
├── 11_grid_template-areas/
│   ├── index.html
│   └── styles.css
│
├── 12_lumina-creative-grid-refector/
│   ├── about.html
│   ├── contact.html
│   ├── index.html
│   │
│   ├── css/
│   │   └── styles.css
│   │
│   └── images/
│       ├── favicon.ico
│       ├── image1.jpg
│       ├── image2.jpg
│       ├── image3.jpg
│       ├── image4.jpg
│       ├── image5.jpg
│       ├── image6.jpg
│       ├── image7.jpg
│       ├── image8.jpg
│       ├── image9.jpg
│       ├── image10.jpg
│       ├── image11.jpg
│       ├── image12.jpg
│       ├── logo.png
│       ├── portfolio1.jpg
│       ├── portfolio2.jpg
│       ├── portfolio3.jpg
│       ├── portfolio4.jpg
│       ├── portfolio5.jpg
│       ├── portfolio6.jpg
│       ├── portfolio7.jpg
│       ├── portfolio8.jpg
│       ├── portfolio9.jpg
│       ├── team1.jpg
│       ├── team2.jpg
│       └── team3.jpg
│
└── README.md
```

## Topics Covered

### 1. Grid Columns
**Folder:** `01_grid-columns`

- Understand the CSS Grid container using `display: grid`.
- Define column sizes using `grid-template-columns`.
- Combine fixed-width columns with flexible `fr` units.
- Control spacing between grid items using `gap`.

### 2. Repeat & Minmax Functions
**Folder:** `02_repeat-minmax-functions`

- Explore the `repeat()` function for defining repeated grid tracks.
- Use `minmax()` to establish minimum and maximum track sizes.
- Create flexible columns that maintain a defined minimum width.
- Understand how repeated grid definitions simplify CSS.

### 3. Grid Rows
**Folder:** `03_grid-rows`

- Define row sizes using `grid-template-rows`.
- Combine different fractional units such as `1fr`, `2fr`, and `3fr`.
- Understand the difference between explicit and implicit grid tracks.
- Control automatically generated rows using `grid-auto-rows`.

### 4. Grid Challenge 1
**Folder:** `04_grid-challenge-1`

- Apply grid columns and rows to arrange multiple items.
- Practice the `repeat()` function and fractional units.
- Control automatically generated rows.
- Use `gap` to maintain consistent spacing between grid items.

### 5. Align & Justify Properties
**Folder:** `05_align-justify-properties`

- Explore `justify-content` and `align-content`.
- Understand `justify-items` and `align-items`.
- Position grid items using `place-items`.
- Practice controlling alignment and distribution within a grid container.

### 6. Auto-Fit, Auto-Fill & Repeat
**Folder:** `06_autofit-autofill-repeat`

- Understand the difference between `auto-fit` and `auto-fill`.
- Combine `repeat()` with automatic track generation.
- Use `minmax()` to create flexible grid columns.
- Explore responsive grid behavior without manually defining every column.

### 7. Positioning & Spanning Grid Items
**Folder:** `07_positioning-spanning-items`

- Position items using `grid-column` and `grid-row`.
- Understand grid line-based placement.
- Make elements span multiple columns or rows.
- Practice the shorthand `span` keyword and the `grid-template` property.

### 8. Named Grid Lines
**Folder:** `08_named-grid-lines`

- Assign custom names to grid lines.
- Define named column and row boundaries.
- Position elements using named grid lines instead of numeric positions.
- Improve layout readability through meaningful grid line names.

### 9. Grid Challenge 2
**Folder:** `09_grid-challenge-2`

- Build a structured page layout with CSS Grid.
- Arrange Header, Navigation, Search, Main Content, Aside, and Footer sections.
- Create a two-column layout using fractional units.
- Allow header and footer elements to span across multiple columns.
- Practice combining different grid tracks for a complete page structure.

### 10. Grid Media Queries
**Folder:** `10_grid-media-querie`

- Combine CSS Grid with media queries.
- Create a two-column desktop layout.
- Change the grid into a single-column layout on smaller screens.
- Adjust grid columns and rows at a `770px` breakpoint.
- Practice responsive page composition.

### 11. Grid Template Areas
**Folder:** `11_grid_template-areas`

- Define named layout regions using `grid-template-areas`.
- Assign elements using the `grid-area` property.
- Create structured layouts for header, navigation, search, main content, aside, and footer.
- Rearrange layout regions using media queries.
- Build responsive layouts with more readable grid definitions.

### 12. Lumina Creative Grid Refactor
**Folder:** `12_lumina-creative-grid-refector`

A practical project that revisits the Lumina Creative website and refactors its portfolio gallery using CSS Grid.

**Key Features & Implementation:**

- **CSS Grid Portfolio Gallery:** Organizes nine portfolio images into a three-column gallery layout.
- **Grid Item Spanning:** Uses `nth-of-type()` selectors to make selected gallery items span multiple columns and rows.
- **Responsive Gallery:** Changes the gallery to a two-column layout on screens up to `768px`, with adjusted spanning behavior.
- **Multi-Page Structure:** Includes Home (`index.html`), About (`about.html`), and Contact (`contact.html`) pages.
- **About Page:** Presents Photography, Web Design, and Graphic Design services, along with a three-member team section.
- **Contact Page:** Provides a contact form with First Name, Last Name, Email, and Message fields.
- **Lightbox Gallery:** Integrates Lightbox2 to display enlarged portfolio images when selected.
- **CSS Layout Techniques:** Uses Flexbox for header, services, team, and footer arrangements alongside Grid for the portfolio gallery.

**Additional Libraries & Resources:**

- **Lightbox2:** Image preview and gallery interaction.
- **jQuery:** External JavaScript dependency used by Lightbox2.
- **Font Awesome:** Icons and social media icons.
- **Google Fonts:** Open Sans typography.

## Learning Outcomes

By completing this section, you will learn to:

- Build two-dimensional layouts with **CSS Grid**.
- Control **grid columns, rows, gaps, and track sizing**.
- Create flexible layouts using **`fr`**, **`repeat()`**, and **`minmax()`**.
- Position and span elements through **grid lines and named areas**.
- Apply **alignment and justification** to control grid layouts.
- Build responsive designs using **auto-fit, auto-fill, and media queries**.
- Develop complete page structures using **Grid and Flexbox together**.

## Getting Started

1. Open the `Section 15 - CSS Grid` folder in Visual Studio Code.
2. Select any exercise folder from the repository structure.
3. Open its `index.html` file in your browser.
4. Use the **Live Server** extension for a convenient local development experience.
5. Explore the associated `styles.css` file and experiment with different Grid properties.
6. For the Lumina Creative Grid Refactor, open its `index.html` file to explore the complete multi-page project.

---

<p align="center">
  <strong>Part of Modern HTML & CSS From The Beginning 2.0</strong>
  <br />
  Learn by building, experimenting, and mastering modern CSS layouts.
</p>
