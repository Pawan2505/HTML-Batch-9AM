## Block-Level Elements

---

### What is a Block-Level Element?

Block-level elements are the tags in HTML that **start from a new line** and usually take up the **full width** of the page, even if the content inside them is small.

They act like **big blocks** on your webpage — meaning they naturally push whatever comes after them **down to the next line**.

---

### Main Points to Remember:

* Always starts on a **new line**
* Takes **100% width** by default
* Can **hold other tags** (like inline tags or even other block-level elements in some cases)
* Used mainly for **structure** and **layout**

---

### Some Common Block-Level Tags:

* `<div>` → A simple block container. Most common for layout.
* `<p>` → Paragraph.
* `<h1>` to `<h6>` → Headings (from largest to smallest).
* `<ul>` and `<ol>` → Lists (unordered and ordered).
* `<li>` → List items (go inside `<ul>` or `<ol>`).
* `<table>` → Tables.
* `<form>` → Forms.
* `<section>`, `<article>`, `<nav>`, `<header>`, `<footer>` → Semantic layout tags.
* `<hr>` → A horizontal line, used to break content.

---

### Example:

```html
<div>
  <h2>This is a heading</h2>
  <p>This is a paragraph under the heading.</p>
</div>
```

In this example:

* `<div>` is the main block.
* Inside it, both `<h2>` and `<p>` are also block-level tags.
* Each of these tags will start on a new line and take full width.

---

### Block vs Inline:

| Feature             | Block Element               | Inline Element              |
| ------------------- | --------------------------- | --------------------------- |
| Starts on new line? | Yes                         | No                          |
| Takes full width?   | Yes (100% width by default) | No (only as much as needed) |
| Example tags        | `<div>`, `<p>`, `<ul>`      | `<span>`, `<a>`, `<b>`      |

---

