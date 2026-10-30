<div align="center">

# Web Accessibility Introduction

### Modern HTML & CSS From The Beginning 2.0

An introduction to web accessibility using HTML, CSS, and JavaScript — exploring screen reader-friendly markup, ARIA roles, ARIA attributes, and accessible interface states.

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Web Accessibility](https://img.shields.io/badge/Web-Accessibility-2E8B57?style=for-the-badge)

<br>

**[View Source Code](https://github.com/mhsakibb/Modern-HTML-CSS_Udemy/tree/main/Section%2013%20-%20Web%20Accessibilit%20Introduction)**

</div>

---

## Table of Contents

- [Course Overview](#course-overview)
- [Learning Objectives](#learning-objectives)
- [Repository Structure](#repository-structure)
- [Learning Modules](#learning-modules)
- [Key Concepts](#key-concepts)
- [Getting Started](#getting-started)

---

## Course Overview

Web accessibility is the practice of designing and developing websites that can be accessed and used by everyone, including people who rely on assistive technologies such as screen readers.

In this section, I explore the fundamentals of web accessibility through practical examples using HTML, CSS, and JavaScript.

The modules focus on semantic HTML, screen reader-friendly elements, ARIA roles, accessible labels, and managing interactive interface states with ARIA attributes.

---

## Learning Objectives

- Understand the fundamentals of web accessibility.
- Explore how screen readers interpret HTML elements.
- Use semantic HTML to structure accessible webpages.
- Understand and apply ARIA roles.
- Provide accessible names using ARIA attributes.
- Understand relationships between elements using ARIA.
- Manage expandable and collapsible content using `aria-expanded`.
- Control accessibility-related states dynamically with JavaScript.

---

## Repository Structure

```text
Section 13 - Web Accessibilit Introduction/
│
├── 01_screen-reader-testing/
│   ├── index.html
│   └── styles.css
│
├── 02_role-attribute/
│   └── index.html
│
├── 03_aria-attrbutes/
│   └── index.html
│
├── 04_aria-expanded/
│   ├── index.html
│   ├── script.js
│   └── styles.css
│
└── README.md
```

---

## Learning Modules

### 01. Screen Reader Testing

**Folder:** `01_screen-reader-testing`

Explore how HTML elements, accessible labels, and semantic page structures help screen readers understand webpage content.

**Topics Covered:**

- Semantic HTML landmarks: `header`, `nav`, and `main`.
- ARIA landmark role: `role="banner"`.
- Accessible names using `aria-label`.
- Connecting labels with form controls using `for` and `id`.
- Creating visually hidden labels with CSS.
- Understanding accessible navigation and search elements.

**Files:**

- `index.html` – Website structure with accessibility-focused HTML markup.
- `styles.css` – Website styling and the visually hidden CSS technique.

---

### 02. ARIA Role Attribute

**Folder:** `02_role-attribute`

Learn how ARIA roles communicate the purpose and meaning of HTML elements to assistive technologies.

**Topics Covered:**

- `role="banner"` – Identifying the website banner.
- `role="button"` – Defining button-like elements.
- `role="listbox"` – Identifying a listbox.
- `role="option"` – Defining individual listbox options.
- `role="region"` – Identifying a meaningful page region.
- `role="alert"` – Identifying important notification content.
- `aria-label` – Providing accessible names.
- `tabindex` – Making an element keyboard-focusable.

**Files:**

- `index.html` – Practical examples of different ARIA roles.

---

### 03. ARIA Attributes

**Folder:** `03_aria-attrbutes`

Explore commonly used ARIA attributes and understand how they provide additional accessibility information.

**Topics Covered:**

- `aria-label` – Providing an accessible name directly.
- `aria-labelledby` – Associating an element with another element's label.
- `aria-hidden="true"` – Hiding content from the accessibility tree.
- `aria-hidden="false"` – Keeping content available to assistive technologies.
- Combining ARIA attributes with HTML elements.

**Files:**

- `index.html` – Practical examples of ARIA labels, relationships, and visibility attributes.

---

### 04. ARIA Expanded

**Folder:** `04_aria-expanded`

Understand how to communicate the expanded and collapsed states of interactive content using ARIA attributes.

**Topics Covered:**

- Understanding the `aria-expanded` attribute.
- Using `aria-controls` to identify controlled content.
- Using `aria-hidden` to manage content visibility.
- Associating accordion content with its heading using `aria-labelledby`.
- Updating ARIA states dynamically with JavaScript.
- Using CSS attribute selectors to control content visibility.
- Implementing a basic accordion interaction.

**Files:**

- `index.html` – Accordion structure with ARIA attributes.
- `script.js` – JavaScript functionality for toggling accordion states.
- `styles.css` – Accordion styling and visibility control.

---

## Key Concepts

| Concept | Description |
|---|---|
| Web Accessibility | Making websites accessible to people with different abilities. |
| Screen Readers | Assistive technologies that interpret and communicate webpage content. |
| Semantic HTML | Using meaningful HTML elements to structure webpages. |
| ARIA Roles | Describing the purpose of elements to assistive technologies. |
| ARIA Labels | Providing accessible names for interface elements. |
| ARIA Relationships | Connecting elements using attributes such as `aria-labelledby` and `aria-controls`. |
| ARIA States | Communicating interface states through attributes such as `aria-expanded` and `aria-hidden`. |
| Keyboard Focus | Managing element focus using attributes such as `tabindex`. |

---

## Getting Started

Follow these steps to explore the examples locally.

### 1. Clone the Repository

```bash
git clone https://github.com/mhsakibb/Modern-HTML-CSS_Udemy.git
```

### 2. Navigate to the Project Directory

```bash
cd Modern-HTML-CSS_Udemy
```

### 3. Open Section 13

```bash
cd "Section 13 - Web Accessibilit Introduction"
```

### 4. Open in VS Code

```bash
code .
```

### 5. Run the Examples

Open any module's `index.html` file in your browser.

You can also use the **Live Server** extension in Visual Studio Code to run the examples locally.

No additional package installation is required.

---

<div align="center">

### Part of My Web Development Learning Journey