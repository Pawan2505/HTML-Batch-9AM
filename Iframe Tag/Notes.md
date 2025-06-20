### HTML `<iframe>` Tag

**What is iframe?**
`<iframe>` means **inline frame**.
It lets you show another webpage inside your current webpage.
For example, you can show:

* Google Maps
* YouTube videos
* Your own web pages
* External websites (if allowed)

---

**Basic Syntax:**

```html
<iframe src="URL"></iframe>
```

---

**Common Attributes You Should Know:**

* `src` → This is the URL of the content you want to display.
* `width` and `height` → This sets the size of the frame. You can use `px`, `%`, `vw`, `vh`.
* `frameborder` → Set it to `"0"` to remove the border.
* `allowfullscreen` → Allows full screen mode (mainly for videos).
* `loading="lazy"` → Delays loading until the user scrolls to it (improves speed).
* `referrerpolicy` → Helps with privacy and security when loading content from other sites.

---

**Example – Google Map Embed**

```html
<iframe 
  src="https://www.google.com/maps/embed?pb=..." 
  width="100%" 
  height="400" 
  style="border: 0;" 
  allowfullscreen 
  loading="lazy">
</iframe>
```

---

**Example – YouTube Video Embed**

```html
<iframe 
  width="560" 
  height="315" 
  src="https://www.youtube.com/embed/video_id" 
  frameborder="0" 
  allow="autoplay; encrypted-media" 
  allowfullscreen>
</iframe>
```

---

**Note:**

* Always check if the website allows embedding (some websites block it).
* You can use a `div` with custom width and height to make your iframe responsive.
* `%` size depends on the parent element, `vw` and `vh` depend on the browser window.

---

