## 📝 HTML Basic Notes

---

### 🔹 1. Heading Tags (`<h1>` to `<h6>`)

* HTML provides 6 heading tags.
* `<h1>` is the **largest** and most important heading.
* `<h6>` is the **smallest** heading.

Example:

```html
<h1>This is Heading-1</h1>
<h6>This is Heading-6</h6>
```

---

### 🔹 2. Paragraph Tag (`<p>`)

* Used to write text in paragraph format.
* Adds space before and after the paragraph by default.

Example:

```html
<p>This is a sample paragraph.</p>
```

---

### 🔹 3. Line Break (`<br>`)

* Used to break the line inside a paragraph or sentence.
* It’s a self-closing tag.

Example:

```html
<p>Hello<br>This is line 2</p>
```

---

### 🔹 4. Horizontal Line (`<hr>`)

* Creates a horizontal line.
* Mainly used to divide content or sections.

Example:

```html
<hr>
```

---

### 🔹 5. Preformatted Text (`<pre>`)

* Displays text exactly as it is written in HTML.
* It respects spaces, line breaks, and tabs.
* Good for writing poems or code snippets.

Example:

```html
<pre>
  This is a line
  This is next line
</pre>
```

---

### 🔹 6. HTML Lists

#### 6.1 Ordered List (`<ol>`)

* Lists items in a **numbered** sequence.
* Types:

  * `type="1"` → 1, 2, 3...
  * `type="A"` → A, B, C...
  * `type="a"` → a, b, c...
  * `type="I"` → I, II, III...
  * `type="i"` → i, ii, iii...

Example:

```html
<ol type="A">
  <li>Apple</li>
  <li>Banana</li>
</ol>
```

💡 `start` attribute is used to change starting number:

```html
<ol start="5">
  <li>Item 1 (starts from 5)</li>
</ol>
```

---

#### 6.2 Unordered List (`<ul>`)

* Lists items with symbols (no specific order).
* Types:

  * `disc` (default) – ●
  * `circle` – ○
  * `square` – ▪
  * `none` – no bullets

Example:

```html
<ul type="square">
  <li>Pen</li>
  <li>Pencil</li>
</ul>
```

---

#### 6.3 Description List (`<dl>`)

* Used for **terms and definitions**.
* Structure:

  * `<dl>` → Description list wrapper
  * `<dt>` → Term (Title)
  * `<dd>` → Definition (Description)

Example:

```html
<dl>
  <dt>HTML</dt>
  <dd>It is a markup language.</dd>
</dl>
```

---

### Notes:

* Headings (`<h1>` to `<h6>`) are used for titles.
* Paragraphs (`<p>`) are for content.
* `<br>` = break line; `<hr>` = horizontal line.
* `<pre>` = keeps original formatting.
* Lists:

  * `<ol>` for ordered list
  * `<ul>` for unordered list
  * `<dl>` for definition-style list

