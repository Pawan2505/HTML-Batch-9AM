### 📓 Marquee Tag:

**1. What is `<marquee>`?**
The `<marquee>` tag is an old HTML tag that we use to move text or images across the screen. Basically, it creates a moving effect like scrolling, sliding, or bouncing text.

**2. Why do we use it?**
We use it to grab attention on something — like announcements, headlines, offers, or any important message.

**3. Note:**
Even though it's cool and fun to use, `<marquee>` is **not officially supported in HTML5**. That means modern developers usually avoid it and prefer CSS/JS for animations. But for learning or fun projects, it’s still fine!

---

### Syntax of Marquee:

```html
<marquee>Content Goes Here</marquee>
```

---

### Marquee Attributes You Can Use:

| Attribute      | Meaning                                              |
| -------------- | ---------------------------------------------------- |
| `behavior`     | Defines how it moves: `scroll`, `slide`, `alternate` |
| `direction`    | Which way it moves: `left`, `right`, `up`, `down`    |
| `scrollamount` | Speed of the movement (higher = faster)              |
| `height/width` | Area it should move in                               |
| `loop`         | How many times it repeats (default is infinite)      |
| `bgcolor`      | Background color of marquee (optional)               |

---

### Example 1: Basic Marquee

```html
<marquee>This is a simple marquee text.</marquee>
```

It will scroll from **right to left** by default.

---

### Example 2: Direction Right

```html
<marquee direction="right">Moving to the right</marquee>
```

---

### Example 3: Slide Behavior

```html
<marquee behavior="slide" direction="left">Sliding text</marquee>
```

It will move once and stop at the end.

---

### Example 4: Bounce (alternate)

```html
<marquee behavior="alternate" direction="up" height="100px">
    Bouncing up and down
</marquee>
```

---

### Note:

* Marquee helps you move text/images on the screen.
* It's old, but easy to use.
* Don’t use it in serious/professional websites — just for learning and fun.
* For real projects, use CSS animations or JavaScript instead.

---

