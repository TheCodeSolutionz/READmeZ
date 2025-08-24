<img width="1024" height="559" alt="Image" src="https://github.com/user-attachments/assets/8d6a323e-89e3-428a-8bfa-835ea8ef0aed" />

# HTML Harmony — Unlock Web Magic in Hours

> **Quick, practical lessons you can open, edit, and download as PDF / DOCX / Markdown.**

---

## How to use this file

* Click any item in the **Table of Contents** to jump to the lesson.
* Each lesson contains a short explanation, a code example, a **Mini Task**, and suggested image search queries you can use to find an illustration to place in your `.md` or `.docx`.
* When ready, use the editor's **File → Download** menu to export as **PDF**, **.docx**, or copy the Markdown for your GitHub repo.

---

## Table of Contents

1.  **[Part 1 — HTML Foundations](https://www.google.com/search?q=%23part-1---html-foundations)**
      * [Lesson 1.1 — What is HTML?](https://www.google.com/search?q=%23lesson-11---what-is-html)
      * [Lesson 1.2 — Tags & Attributes](https://www.google.com/search?q=%23lesson-12---tags--attributes)
      * [Lesson 1.3 — Block vs Inline Elements](https://www.google.com/search?q=%23lesson-13---block-vs-inline-elements)
      * [Lesson 1.4 — Lists, Links & Images](https://www.google.com/search?q=%23lesson-14---lists-links--images)
2.  **[Part 2 — Styling Secrets (CSS Basics)](https://www.google.com/search?q=%23part-2---styling-secrets-css-basics)**
3.  **[Part 3 — Interactive Elements](https://www.google.com/search?q=%23part-3---interactive-elements)**
      * [Forms](https://www.google.com/search?q=%23forms)
      * [Media & Responsive Images](https://www.google.com/search?q=%23media--responsive-images)
4.  **[Part 4 — Advanced Touches](https://www.google.com/search?q=%23part-4---advanced-touches)**
5.  **[Capstone — Personal Portfolio Project](https://www.google.com/search?q=%23capstone---personal-portfolio-project)**
6.  **[Cheatsheets & Export Guide](https://www.google.com/search?q=%23cheatsheets--export-guide)**

---

# Part 1 — HTML Foundations

## Lesson 1.1 — What is HTML?

**Short:** HTML defines the structure of a webpage.

**Example**

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

**Mini Task:** Create `index.html` containing a heading, two paragraphs, and an unordered list of three favorite foods.

**Suggested image (search):** `lego bricks web analogy`, `html structure diagram`

---

## Lesson 1.2 — Tags & Attributes

**Short:** Tags wrap content; attributes add information.

**Example**

```html
<img src="cat.png" alt="Cute cat" width="300">
```

**Mini Task:** Add an image to your page with a meaningful `alt` attribute.

**Suggested image (search):** `mail envelope analogy attributes`, `html attributes illustration`

---

## Lesson 1.3 — Block vs Inline Elements

**Short:** Block elements start on a new line; inline elements flow inside text.

**Examples**

```html
<p>This is a <span class="highlight">highlighted</span> word.</p>
<div>This is a block element.</div>
```

**Mini Task:** Wrap a single word in a paragraph with `<span>` and add a class for styling.

**Suggested image (search):** `block vs inline html diagram`, `box model simple`

---

## Lesson 1.4 — Lists, Links & Images

**Short:** Build navigation and lists for content structure.

**Examples**

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>

<a href="about.html">About</a>
```

**Mini Task:** Create a `nav` using a `<ul>` with 3 links to `index.html`, `projects.html`, `contact.html`.

**Suggested image (search):** `simple navigation bar wireframe`, `html lists diagram`

---

# Part 2 — Styling Secrets (CSS Basics)

**Short:** Add visual design using CSS. Use an external stylesheet for projects.

**Link CSS**

```html
<link rel="stylesheet" href="styles.css">
```

**Basic rules**

```css
/* styles.css */
body { font-family: Arial, sans-serif; margin: 0; }
.nav { display: flex; gap: 1rem; }
#hero { padding: 3rem; background: linear-gradient(#fff,#f4f4f4); }
```

**Mini Task:** Create a hero section with a large heading, subtitle, and CTA button. Link `styles.css` and center the hero content.

**Suggested image (search):** `hero section design example`, `landing page hero mockup`

---

# Part 3 — Interactive Elements

## Forms (short)

```html
<form action="/submit">
  <label for="name">Name</label>
  <input id="name" name="name" type="text" required>
  <label for="message">Message</label>
  <textarea id="message" name="message"></textarea>
  <button type="submit">Send</button>
</form>
```

**Mini Task:** Build a contact form with Name, Email, Message, and a Submit button. Ensure each input has a corresponding `<label>`.

**Suggested image (search):** `contact form UI example`, `forms accessibility label`

---

## Media & Responsive Images

**Short:** Use native elements for audio/video and `srcset` for responsive images.

```html
<video controls>
  <source src="intro.mp4" type="video/mp4">
</video>

<img src="hero.jpg" srcset="hero-small.jpg 480w, hero-large.jpg 1200w" sizes="(max-width:600px) 480px, 1200px" alt="Hero image">
```

**Mini Task:** Add a sample video and a responsive image to a page.

**Suggested image (search):** `responsive images srcset example`, `video element demo`

---

# Part 4 — Advanced Touches

**Short:** Make your site semantic, accessible, and fast.

**Semantic layout**

```html
<header>...nav...</header>
<main>...content...</main>
<footer>...contacts...</footer>
```

**Accessibility checklist (quick)**

* meaningful `alt` on images
* `label` for form inputs
* logical heading order
* sufficient color contrast

**Performance tips**

* compress images (use WebP where suitable)
* minify CSS and JS
* defer non-critical scripts

**Mini Task:** Convert your homepage to use `<header>`, `<main>`, and `<footer>` and add `alt` text for all images.

**Suggested image (search):** `web accessibility icons`, `semantic html layout diagram`

---

# Capstone — Personal Portfolio Project

**Goal:** Build a responsive multi-page portfolio. Use the steps below as checkpoints.

### Project files (recommended)

```
/portfolio
  /assets
  index.html
  about.html
  projects.html
  contact.html
  styles.css
```

### Milestones

1. Scaffold project folder and files.
2. Implement responsive header & nav.
3. Create hero + about section.
4. Add projects grid with cards.
5. Create a contact form.
6. Polish: hover effects, transitions, mobile layout.

### Example card

```html
<article class="project-card">
  <img src="assets/project1.png" alt="Project 1 screenshot">
  <h3>Project One</h3>
  <p>Short description.</p>
  <a href="projects/project1.html">Details</a>
</article>
```

**Suggested image (search):** `portfolio website wireframe`, `project card layout example`

---

# Cheatsheets & Export Guide

## Quick Cheatsheet

* HTML: `<!doctype html>`, `<head>`, `<title>`, `<h1>`–`<h6>`, `<p>`, `<a>`, `<img>`, `<ul>`, `<div>`
* CSS: `display`, `margin`, `padding`, `box-sizing`, `flex`, `grid`
* Accessibility: `alt`, `label`, keyboard focus, color contrast

## Exporting this document

* To export as **PDF** or **.docx**: use the editor's **File → Download** menu and select the desired format.
* To get Markdown: copy the document text or download as `.md` if your editor supports it.

## Image search hints (use these queries)

* `lego bricks web analogy`
* `html tags infographic`
* `box model diagram simple`
* `hero section mockup responsive`
* `portfolio website wireframe`

---

# Next steps I can do for you

* Generate a ready-to-download `.docx` file with this content (I will create it for you).
* Generate a GitHub-ready repo ZIP including `index.html`, `styles.css`, and asset placeholders.
* Create SVG badge files for Gamification.

---

*End of document — open the editor and use the File menu to download.*
