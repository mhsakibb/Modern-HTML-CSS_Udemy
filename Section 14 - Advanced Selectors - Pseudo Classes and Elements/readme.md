<div align="center">

# Advanced Selectors - Pseudo Classes and Elements

### Master Advanced CSS Selectors for More Precise and Flexible Styling

Explore attribute selectors, combinators, pseudo-classes, pseudo-elements, relational selectors, and advanced form styling through practical HTML and CSS exercises.

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white" alt="Google Fonts" />
</p>

</div>

---

## Section Overview

This section of **Modern HTML & CSS From The Beginning 2.0** focuses on advanced CSS selectors and techniques for targeting HTML elements without adding unnecessary classes or IDs.

Through practical exercises, this section explores attribute selectors, child and sibling combinators, pseudo-elements, structural pseudo-classes, relational selectors, and form styling.

It concludes with a **CSS Selectors Challenge**, where the concepts are applied to a multi-section website featuring smooth in-page navigation and targeted styling.

## Repository Structure

The following structure reflects the actual folders and files in this section of the repository.

```text
Section 14 - Advanced Selectors - Pseudo Classes and Elements/
│
├── 01_attribute-selector/
│   ├── index.html
│   └── styles.css
│
├── 02_child sibling combinators/
│   ├── index.html
│   └── styles.css
│
├── 03_pseudo-elements/
│   ├── index.html
│   └── styles.css
│
├── 04_pseudo-first-last-nth-child/
│   ├── index.html
│   └── styles.css
│
├── 05_pseudo-first-last-nth-type/
│   ├── index.html
│   └── styles.css
│
├── 06_before-after-pseudo/
│   ├── index.html
│   └── styles.css
│
├── 07_image-overlay/
│   ├── background.jpg
│   ├── index.html
│   └── styles.css
│
├── 08_is-where-has/
│   ├── index.html
│   └── styles.css
│
├── 09_styling-forms/
│   ├── index.html
│   └── styles.css
│
├── 10_selectors-challenge/
│   ├── index.html
│   ├── styles.css
│   ├── project1.jpg
│   ├── project2.jpg
│   ├── project3.jpg
│   ├── project4.jpg
│   ├── readme.md
│   └── screenshots/
│       └── selectors-challenge-preview.png
│
└── README.md
```

## Topics Covered

### 1. Attribute Selectors

**Folder:** `01_attribute-selector`

Learn how to select HTML elements based on their attributes and attribute values.

- Select elements by attribute name, such as `[required]`.
- Target specific input types using `[type="email"]` and `[type="password"]`.
- Combine multiple attribute selectors for more precise targeting.
- Use attribute value matching operators:
  - `[href^="#"]` — matches values that start with a specified string.
  - `[href$=".com"]` — matches values that end with a specified string.
  - `[href*="traversy"]` — matches values containing a specified substring.
- Apply different styles to form inputs, buttons, and navigation links.

### 2. Child & Sibling Combinators

**Folder:** `02_child sibling combinators`

Understand how CSS combinators select elements based on their relationships in the HTML document.

- **Child Combinator (`>`):** Selects direct children of an element.
- **Adjacent Sibling Combinator (`+`):** Selects the immediate next sibling.
- **General Sibling Combinator (`~`):** Selects all matching following siblings.
- Practice targeting direct paragraphs, unordered lists, links, and sibling elements.
- Understand how nested HTML structures affect selector matching.

### 3. Pseudo-Elements

**Folder:** `03_pseudo-elements`

Explore pseudo-elements to style specific parts of an element without adding extra HTML markup.

- `::first-letter` — styles the first letter of a text element.
- `::first-line` — styles the first line of a paragraph.
- `::selection` — styles text selected by the user.
- `::placeholder` — customizes placeholder text in form inputs.
- `::file-selector-button` — styles the file input button.
- `::marker` — customizes list markers.
- Explore the relationship between pseudo-classes and pseudo-elements.

### 4. First, Last & Nth Child Selectors

**Folder:** `04_pseudo-first-last-nth-child`

Learn how to target elements based on their position among their siblings.

- `:first-child` — selects the first child.
- `:last-child` — selects the last child.
- `:nth-child()` — selects elements by a specific position.
- `:nth-child(odd)` — targets odd-numbered children.
- `:nth-child(even)` — targets even-numbered children.
- `:nth-child(4n)` — targets every fourth child.
- `:only-child` — selects an element when it is the only child of its parent.

### 5. First, Last & Nth Of Type Selectors

**Folder:** `05_pseudo-first-last-nth-type`

Understand how `of-type` pseudo-classes select elements according to their HTML element type.

- `:first-of-type` — selects the first element of its type.
- `:last-of-type` — selects the last element of its type.
- `:nth-of-type()` — selects an element based on its position among elements of the same type.
- Explore `:nth-of-type(odd)` and `:nth-of-type(even)`.
- Compare `:nth-child()` with `:nth-of-type()`.
- Combine pseudo-classes with pseudo-elements for more targeted styling.

### 6. Before & After Pseudo-Elements

**Folder:** `06_before-after-pseudo`

Learn how to generate and position additional visual content using CSS pseudo-elements.

- `::before` — inserts generated content before an element's content.
- `::after` — inserts generated content after an element's content.
- Use the `content` property to insert text or create decorative elements.
- Add a required-field indicator using `label.is-required::after`.
- Explore positioning and styling generated elements.
- Apply universal box-sizing rules to pseudo-elements.

### 7. CSS Image Overlay

**Folder:** `07_image-overlay`

Practice creating a hero section with a background image and a dark overlay using CSS.

- Apply background images using `background`.
- Use `::before` to create a semi-transparent overlay.
- Position the overlay with absolute positioning.
- Use relative positioning on the hero section to establish its positioning context.
- Layer text and call-to-action content over the background.
- Apply a media query at `768px` to adjust heading, paragraph, and button typography for smaller screens.

### 8. Advanced Selectors — :is(), :where() & :has()

**Folder:** `08_is-where-has`

Explore modern relational and grouping selectors to write more flexible CSS rules.

- `:is()` — groups multiple selectors into one selector list.
- `:where()` — groups selectors without adding specificity.
- `:has()` — selects an element based on the presence of matching descendants or related elements.
- Explore selector combinations such as `:is(:hover, :focus)`.
- Practice relational selection with `.container:has(h1 span)`.
- Use `h1:has(+ h2)` to target an element based on its adjacent sibling.

**Note:** The current stylesheet contains commented examples of `:is()` and `:where()`, while the `:has()` selectors are actively demonstrated.

### 9. Styling Forms with CSS

**Folder:** `09_styling-forms`

Learn how to create visually organized forms and style their interactive states using CSS selectors.

- Style text inputs, email inputs, and textareas.
- Use `:focus` to customize focused input states.
- Apply `:focus-within` to style a form when an element inside it receives focus.
- Use `:placeholder-shown` to target inputs displaying placeholder text.
- Apply `:invalid` and `:valid` to style form validation states.
- Customize placeholder text using `::placeholder`.
- Create consistent form spacing, borders, typography, and button styling.

### 10. CSS Selectors Challenge — Smooth Scroll Mini-Project

**Folder:** `10_selectors-challenge`

Apply advanced CSS selectors in a complete multi-section website. This challenge is an updated version of the Smooth Scroll exercise originally introduced in Section 10.

**Key Features & Implementation**

- **Smooth In-Page Navigation:** Includes Home and Project 1–4 navigation links connected to their respective page sections.
- **CSS Smooth Scrolling:** Uses `scroll-behavior: smooth` on the HTML document to create smooth navigation between sections.
- **Structural Pseudo-Classes:** Uses `:first-of-type` and `:nth-child()` to style paragraphs and alternate list-item backgrounds.
- **Relational Selectors:** Uses `:has(img)` to target sections containing images.
- **Sibling Combinators:** Uses `ul + p` to select paragraphs immediately following unordered lists.
- **Attribute Selectors:** Targets external links using `[href^='http://']` and `[href^='https://']`.
- **Combined Selectors:** Combines `:nth-of-type()`, `:first-of-type`, and link selectors to apply targeted font styling.
- **Visual Layout:** Uses a gradient navigation header, styled section headings, project images, and a centered content container.

<p align="center">
  <img src="./10_selectors-challenge/screenshots/selectors-challenge-preview.png" alt="Smooth Scroll and CSS Selectors Challenge preview" width="90%" />
</p>

<p align="center">
  <a href="https://smooth-scroll-mini-project.vercel.app/">
    <strong> View Live Website</strong>
  </a>
  ·
  <a href="https://github.com/mhsakibb/Modern-HTML-CSS_Udemy/tree/main/Section%2014%20-%20Advanced%20Selectors%20-%20Pseudo%20Classes%20and%20Elements/10_selectors-challenge">
    <strong>View Source Folder</strong>
  </a>
</p>

## Learning Outcomes

By completing this section, you will develop the ability to:

- Select HTML elements precisely using **Attribute Selectors** and **Combinators**.
- Apply structural styling through **Pseudo-Classes** such as `:first-child`, `:nth-child()`, and `:nth-of-type()`.
- Generate decorative content using **`::before`** and **`::after`**.
- Use modern relational selectors such as **`:is()`**, **`:where()`**, and **`:has()`**.
- Style interactive form states with **`:focus`**, **`:valid`**, and **`:invalid`**.
- Combine multiple selector techniques to build more maintainable and targeted CSS rules.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/mhsakibb/Modern-HTML-CSS_Udemy.git
   ```

2. Open the repository in **Visual Studio Code**.

3. Navigate to:

   ```text
   Section 14 - Advanced Selectors - Pseudo Classes and Elements/
   ```

4. Choose any exercise folder and open its `index.html` file.

5. Run the HTML file using the **Live Server** extension or open it directly in your browser.

6. Modify the corresponding `styles.css` file to experiment with different selectors and styling rules.

---

<div align="center">

**Part of Modern HTML & CSS From The Beginning 2.0**

Learn by experimenting, practicing, and building real-world layouts.

</div>