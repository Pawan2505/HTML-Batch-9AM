### 📘 HTML `<video>` Tag

**What is it for?**
The `<video>` tag is used when we want to add video files directly on a webpage.
Just like we use `<img>` for images, we use `<video>` for videos.

---

### Basic Syntax:

```html
<video src="file.mp4" controls></video>
```

This line adds a video player to your page.

---

### Common Attributes:

* **`src`** → Path of the video file (can be offline or online).
* **`controls`** → Shows default play, pause, volume, etc.
* **`autoplay`** → Automatically plays the video when page loads.
* **`loop`** → Restarts video once it ends.
* **`muted`** → Starts the video with no sound.
* **`width` / `height`** → Sets size of video on page.


---

### Example 1 – Simple video with controls:

```html
<video src="video.mp4" width="500px" height="300px" controls></video>
```

---

### Example 2 – Autoplay, loop, and muted:

```html
<video src="video.mp4" width="100%" height="500px" autoplay loop muted></video>
```

---

### Example 3 – Using `<source>` tag (recommended):

```html
<video width="100%" height="400px" controls>
  <source src="video.mp4" type="video/mp4">
  <source src="video.ogg" type="video/ogg">

</video>
```

This method allows multiple formats for better browser compatibility.

---

### Note:

* Always use the `controls` attribute if you want user interaction.
* Most browsers block `autoplay` unless the video is muted.
* Not all users have fast internet, so it's better to compress video files.

---


