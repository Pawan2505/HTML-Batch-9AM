### 📒 Image Tag

In HTML, we can show images on a webpage using the `<img>` tag. This tag is self-closing and does **not need a closing tag**.

---

### Important Attributes of `<img>`:

1. **`src`** – This means **source** of the image. It tells the browser where to find the image.

   * This can be an **online URL** or an **offline (local) file path**.

2. **`width` and `height`** – Used to set the **size** of the image.

3. **`alt`** – This is **alternative text**. If the image doesn’t load, this text will be shown instead.
   It's also helpful for **screen readers** (accessibility).

4. **`title`** – When we hover the mouse on the image, this **tooltip text** will appear.

---

### Types of Images:

#### 1. **Online Image**

* We copy the link (URL) of an image from the internet and use it in `src`.

```html
<img src="https://example.com/image.jpg" width="300px" height="400px" alt="Girl" title="She is very beautiful girl">
```

#### 2. **Offline Image**

* For this, the image must be saved in your **project folder** (like in an `images` folder).

```html
<img src="./images/boy.jpg" width="300px" height="400px" alt="Boy" title="He is very handsome boy">
```

---

### Note:

* The `<img>` tag does **not** have a closing tag.
* Always give `alt` text — it's good for SEO and accessibility.
* Use relative paths like `./images/photo.jpg` for local images.
* Online images need an active internet connection to be visible.

---

