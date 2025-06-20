## HTML Anchor Tag

---

### What is an Anchor Tag?

In HTML, we use the `<a>` tag to create links.
This tag allows us to jump from one place to another.
We can use it to open:

* A website (like Google, Flipkart, etc.)
* Another page from our own website
* Or even scroll to a specific part of the same page

---

### Types of Anchor Tags

We learned 3 types of anchor tags in class:

---

### 1. External Link

This type of link is used to open any **external website**,
like Google, Flipkart, or YouTube.

We use `target="_blank"` so that the link opens in a **new tab**.

**Example:**

```html
<a href="https://www.flipkart.com" target="_blank">Go to Flipkart</a>
```

* `href` means Hyperlink Reference (link)
* `target="_blank"` means open in a new tab

---

### 2. Internal Link

This type of link is used to open **another HTML file**
that is part of your own website or project.

It’s like going from `index.html` to `about.html`.

**Example:**

```html
<a href="about.html" target="_blank">Go to About Page</a>
```

Make sure the file (about.html) is saved in the same folder.

---

### 3. Bookmark Link

This type of link is used to **jump to a section**
inside the same page.

We use this when the page is long, and we want to scroll
to a specific heading or section quickly.

**How to do it:**

* First, give `id` to the element you want to jump to.
* Then, use `href="#idname"` in the anchor tag.

**Example:**

```html
<a href="#services">Jump to Services Section</a>

<!-- somewhere below in the same page -->
<h2 id="services">Our Services</h2>
```

This will scroll the page directly to the "Our Services" heading.

---

### Summary Table

| Type of Link  | What it Does                      | Example              |
| ------------- | --------------------------------- | -------------------- |
| External Link | Opens another website             | `href="https://..."` |
| Internal Link | Opens another HTML file           | `href="page.html"`   |
| Bookmark Link | Jumps to section in the same page | `href="#section-id"` |

---

### Important Attributes

* `href` → This tells the browser where the link goes.
* `target="_blank"` → This opens the link in a new tab.
* `id` → Used with bookmark links to mark the jump location.

---

