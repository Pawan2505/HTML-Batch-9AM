### 🎧 Audio Tag Notes

**What is it?**
The `<audio>` tag is used to add audio/music/sound effects to your webpage.

You can either give the path directly in the `src` attribute, or you can use `<source>` tags inside the `<audio>` tag (recommended for better browser support).

---

### Syntax:

```html
<audio src="audio.mp3" controls></audio>
```

or

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
```

---

### Important Attributes:

* `src` → path to the audio file
* `controls` → shows the play/pause controls
* `autoplay` → audio will play automatically when page loads
* `loop` → will keep playing again and again
* `muted` → starts the audio in mute


---

### Example:

```html
<audio controls autoplay loop muted>
  <source src="music.mp3" type="audio/mpeg">
</audio>
```

In this example:

* `controls` lets users play/pause
* `autoplay` plays it immediately
* `loop` repeats it forever
* `muted` starts with no sound

---

### Notes:

* Always give a fallback message like: “Your browser does not support the audio element.”
* You can include multiple `<source>` tags for different audio formats (like `.mp3`, `.ogg`, etc.).
* Keep file path correct (relative or absolute).

---

