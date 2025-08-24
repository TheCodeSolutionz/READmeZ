<img width="1024" height="559" alt="Image" src="https://github.com/user-attachments/assets/8d6a323e-89e3-428a-8bfa-835ea8ef0aed" />

<!--
Professional, human-first Markdown handout for "HTML Harmony — Part 1: HTML Foundations".
This document is intentionally focused ONLY on HTML (no CSS, no JS) and written in a storytelling, motivational style.
-->

# HTML Harmony — Part 1: Foundations

> *Unlock web magic fast — build meaningful pages that people understand and remember.*

---

## Welcome — Why this lesson matters

You’re not learning HTML just to write tags. You’re learning the vocabulary of the web — how ideas, structure, and intent become visible to people around the world.

This handout guides you through the absolute essentials of HTML with clarity, real examples, and short practice tasks that actually stick. Read it like a short conversation with an excellent teacher: warm, precise, and useful.

**What you’ll achieve by the end:**

* A clear mental model of what HTML does and why it exists
* Hands-on examples you can copy and run immediately
* A final HTML-only mini-project that proves you’ve got it

---

## Quick roadmap

1. What is HTML? — The essentials.
2. Tags & attributes — The building blocks.
3. Block vs inline — How the page lays out itself.
4. Lists, links & images — Real content structure.

Each section contains a short explanation, a copy-paste example, and a tiny task.

---

## Lesson 1.1 — What is HTML?

**One-line:** HTML defines the structure and meaning of web content.

Think of HTML as the skeleton of a page: it tells browsers and assistive tech what the content *is* (a heading, a paragraph, an image), not how it should look.

**Core idea:** Structure first → style later.

**Example (copy to a file named `index.html` and open in your browser):**

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>This is a paragraph of friendly text that explains who you are.</p>
  </body>
</html>
```

**Why this matters:** The `<!doctype html>` and `<html lang>` help browsers and screen readers behave correctly — they’re accessibility and compatibility basics.

**Mini Task (10 minutes):**
Create `index.html` with a main heading, two short paragraphs, and save it. Open it in your browser and say out loud what each tag means.

---

## Lesson 1.2 — Tags & Attributes

**One-line:** Tags define elements; attributes give them extra data.

Tags are the nouns of HTML (`<p>`, `<img>`, `<a>`). Attributes are adjectives — they describe tags (`src`, `alt`, `href`). Use attributes to make elements useful and accessible.

**Example:**

```html
<img src="cat.png" alt="A small orange cat curled on a blanket" width="300">
```

**Tip:** Always write a meaningful `alt` — it’s not optional. Describe the image’s purpose for someone who can’t see it.

**Mini Task (10 minutes):**
Add an image to your `index.html`. Use a relevant `alt` describing the image’s content or purpose.

---

## Lesson 1.3 — Block vs Inline Elements

**One-line:** Block elements stack vertically; inline elements flow inside lines of text.

Block elements (like `<div>`, `<p>`, `<h1>`) create structure and sections. Inline elements (like `<a>`, `<span>`, `<strong>`) live inside lines and emphasize or link.

**Examples:**

```html
<p>This is a <span class="highlight">highlighted</span> word inside a paragraph.</p>
<div>This is a block-level container — it starts on a new line.</div>
```

**Why this matters:** Choosing the right element improves readability and accessibility. Use `<p>` for paragraphs, `<h1>`–`<h6>` for headings, and `<span>` only for tiny in-line tweaks.

**Mini Task (5–10 minutes):**
Wrap one word in a paragraph with `<span>` and give it a `class` attribute (you won’t style it yet — we’re practicing structure).

---

## Lesson 1.4 — Lists, Links & Images

**One-line:** Use lists and links to create navigation and readable sequences.

Lists are for grouped items. Links let people move through your site. Images are content or decoration — treat them differently.

**Examples:**

```html
<nav>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="projects.html">Projects</a></li>
    <li><a href="contact.html">Contact</a></li>
  </ul>
</nav>

<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

**Accessibility note:** When links are read out of context, the label should still make sense. Prefer descriptive link text (e.g., `View my projects`) over `click here`.

**Mini Task (10 minutes):**
Add a `nav` with three links to `index.html`, `projects.html`, and `contact.html` to your `index.html` file.

---

## Quick accessibility checklist (always do these)

* Use `lang` on the `<html>` element.
* Provide meaningful `alt` attributes for images.
* Label form controls (we’ll cover forms briefly in the course, but keep labels in mind).
* Keep headings in logical order (`<h1>` → `<h2>` → `<h3>`).

---

## Small experiments (try these to learn fast)

1. Open your `index.html`, edit a heading, save, refresh — observe instant feedback.
2. Right-click → View Page Source — HTML you wrote is the same the browser sees.
3. In the browser inspector, find your `<img>` tag and toggle the `alt` text — think about what screen reader users would hear.

---

## Final HTML-Only Capstone Task (this proves you understand Part 1)

**Goal:** Build a simple, semantic `index.html` homepage that demonstrates everything above.

**Requirements (HTML only — no CSS or JS):**

* A valid `<!doctype html>` and `<html lang="en">` wrapper.
* `<head>` with `<meta charset="utf-8">` and a meaningful `<title>`.
* `<header>` that contains a `<nav>` with links to `index.html`, `projects.html`, and `contact.html`.
* A main `<h1>` heading that introduces you or the site.
* At least two paragraphs (`<p>`) that explain what the site or you do.
* An unordered list (`<ul>`) of three favorite foods (or three skills) — each as `<li>`.
* One image with a meaningful `alt` attribute.
* A final `<footer>` with contact info displayed as plain text or a mailto link.

**Bonus (still HTML only):**

* Add an `<article>` or `<section>` with a short project card using `<h3>`, an `<img>`, a `<p>`, and a link to details.

**Deliverable:** Save the file as `index.html`. Open it in your browser and test each link (they can point to separate files that don’t exist yet). When ready, submit your `index.html` file for review.

---
