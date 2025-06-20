## 📘 HTML5 Notes

### 🔸 What is HTML5?

HTML5 is the **latest version of HTML** (HyperText Markup Language). It’s used to **structure content** on the web like text, images, videos, buttons, etc.

> It’s not a programming language – it just **tells the browser what to show**.

---

### 🔸 What's New in HTML5?

HTML5 introduced many new features that made web development **easier and smarter**:

#### **New Semantic Tags**

Helps in organizing web page content more meaningfully:

* `<header>` – for top section or logo/title
* `<nav>` – for navigation/menu links
* `<section>` – for a section of content
* `<article>` – for self-contained content (like a blog or news)
* `<aside>` – for sidebars or extra notes
* `<footer>` – for bottom section of the page

📝 These tags make your code **clean, readable, and SEO-friendly**.

---

#### **New Input Types in Forms**

HTML5 added new types of `<input>` to collect specific types of data:

* `type="email"` – email input
* `type="url"` – website link input
* `type="tel"` – phone number input
* `type="number"` – numbers only
* `type="range"` – slider
* `type="date"` – select date
* `type="color"` – color picker

> These inputs help in **validating data automatically**.

---

#### **New Form Attributes**

* `placeholder` – shows light gray hint inside the input
* `required` – makes input mandatory
* `autofocus` – automatically focuses on the field when page loads
* `autocomplete` – browser fills data automatically

---

#### **Multimedia Tags**

HTML5 lets us add **video and audio without Flash**:

* `<video src="video.mp4" controls></video>`
* `<audio src="audio.mp3" controls></audio>`

---

#### **Canvas and SVG**

Used to draw graphics, charts, games, etc.

* `<canvas>` – for drawing 2D graphics using JavaScript
* `<svg>` – for scalable vector graphics (shapes and lines)

---

#### **Storage in Browser**

HTML5 lets websites store data in browser (without cookies):

* `localStorage` – stores data permanently (until cleared)
* `sessionStorage` – stores data until browser/tab is closed

---

### 🔸 Features of HTML5 at a Glance

* Clean & meaningful structure (semantic)
* Audio/video support
* Better forms and input fields
* Works on mobile and desktop
* Offline storage
* JavaScript APIs supported

---

### 🔸 Example of Semantic HTML5 Page

```html
<!DOCTYPE html>
<html>
<head>
  <title>HTML5 Example</title>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
  </nav>

  <section>
    <article>
      <h2>My First Blog</h2>
      <p>This is a cool post about HTML5!</p>
    </article>
  </section>

  <footer>
    <p>Copyright © 2025</p>
  </footer>
</body>
</html>
```

---

### Note:

* Always use `<!DOCTYPE html>` on top (to declare HTML5)
* Avoid using old tags like `<font>`, `<center>`, etc.
* Use semantic tags to improve **readability and SEO**
* Learn about **accessibility** and **responsive design** as next steps

---

