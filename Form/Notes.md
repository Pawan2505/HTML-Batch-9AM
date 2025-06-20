## 📝 HTML Forms

### 🔹 What is a Form in HTML?

A **form** is a section on a webpage that allows users to input data and send it to the server.

We write forms using the `<form>` tag.

---

### 🔹 Basic Structure of a Form

```html
<form>
  <!-- form inputs here -->
</form>
```

Inside a form, we can use different input fields like:

* Text box
* Number input
* Radio button
* Checkboxes
* Dropdowns
* Textarea
* Submit/reset buttons

---

### 🔹 `<fieldset>` and `<legend>`

Used to group related fields in a form and give them a title.

```html
<fieldset>
  <legend>Student Application</legend>
  <!-- inputs here -->
</fieldset>
```

This gives a visible box with a label on top.

---

### 🔹 Common Form Input Types

#### 1. **Text Input**

```html
<input type="text" placeholder="Enter your name...">
```

Used for entering short text like name, city, etc.

---

#### 2. **Number Input**

```html
<input type="number" placeholder="Enter your age...">
```

Used for numerical values only.

---

#### 3. **Telephone Input**

```html
<input type="tel">
```

For phone numbers. It may show a number pad on mobile.

---

#### 4. **Radio Buttons**

Used to choose **only one** option from a group.

```html
<input type="radio" name="gender"> Male
<input type="radio" name="gender"> Female
```

Note: All options must have the **same `name`** to group them.

---

#### 5. **Checkboxes**

Used to choose **multiple** options.

```html
<input type="checkbox"> Music
<input type="checkbox"> Coding
```

Each checkbox is independent.

---

#### 6. **Dropdown List (Select Box)**

```html
<select>
  <option>Select Option</option>
  <option>Frontend Development</option>
</select>
```

You can add a `selected` attribute to show a default option.

---

#### 7. **Date Picker**

```html
<input type="date">
```

Used to select a date like DOB, booking date, etc.

---

#### 8. **Textarea**

```html
<textarea rows="2" cols="20"></textarea>
```

Used for larger text like address, comments, etc.

---

#### 9. **Email and Password Fields**

```html
<input type="email">
<input type="password">
```

* Email input checks for valid email format.
* Password hides the characters.

---

#### 10. **File Upload**

```html
<input type="file">
```

Used to attach documents, photos, etc.

---

#### 11. **Color Picker**

```html
<input type="color">
```

Used to select colors visually.

---

### 🔹 Form Buttons

#### Submit Button

```html
<input type="submit" value="Save">
```

Submits the form data.

#### Reset Button

```html
<input type="reset" value="Clear">
```

Clears all input fields.

#### Normal Buttons

```html
<button type="submit">Click</button>
<button type="reset">Reset</button>
```

You can style these buttons as needed.

---

### Note:

* Always use `name` attributes when submitting data to a server.
* Use `label` tags for better accessibility and clarity.
* Use `placeholder` to guide users inside input boxes.
* Always wrap form elements inside `<form>` for full functionality.

---

