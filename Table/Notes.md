### 📚 HTML Table

If we want to **display data in a row & column format**, we use the `<table>` tag. It's kind of like how we use tables in Excel — we divide info neatly so it's easy to read.

---

### 1. **Basic Structure of a Table**

The main tag is:

```html
<table> ... </table>
```

And inside it, we use different tags to define rows, headers, and cells:

* `<thead>` → for header row(s)
* `<tbody>` → for body content
* `<tfoot>` → for footer row(s)
* `<tr>` → for table rows
* `<th>` → for table header cells (bold + centered)
* `<td>` → for table data cells (normal content)

---

### 2. **Simple Table Example**

```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Pawan</td>
    <td>25</td>
  </tr>
</table>
```

This will show 2 rows: one for heading (Name, Age) and one with values (Pawan, 25).

---

### 3. **Attributes You Should Know**

* `border="1"` → adds border around the table
* `cellpadding` → space inside cells
* `cellspacing` → space between cells
* `width`, `height` → to set table size
* `align` → to center or left-align the table
* `bgcolor` or `style="background-color:"` → for coloring rows/cells
* `colspan` → one cell takes space of multiple columns
* `rowspan` → one cell takes space of multiple rows

---

### 4. **Table Sections**

* `<thead>` – For header part (first row usually)
* `<tbody>` – For main data rows
* `<tfoot>` – For bottom row like total or remarks

They help organize the table clearly and help with styling too.

---

### 5. **Image inside Table**

You can also add images inside table cells:

```html
<td><img src="..." width="100px"></td>
```

This is useful when showing profile pics, product photos, etc.

---

### 6. **Sample Layout with Caption**

```html
<table border="1" align="center">
  <caption>Student Details</caption>
  <thead>
    <tr>
      <th>ID</th>
      <th>Name</th>
      <th>Course</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Pawan</td>
      <td>Full Stack</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="3">Total Students: 1</td>
    </tr>
  </tfoot>
</table>
```

---

### 7. **Using Colspan & Rowspan**

* `colspan="2"` → merges two columns into one
* `rowspan="2"` → merges two rows into one

Example:

```html
<td colspan="2">Merged Cell</td>
```

---

### 8. **Styling Table**

We can add background color, text color, and other styles using:

* `bgcolor="red"` → old method
* or `style="background-color:red; color:white;"` → preferred way

---

