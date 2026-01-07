# 📝 HTML Forms Demo

This project demonstrates how to use **HTML forms** to collect user input.  
Forms are essential for interaction on the web — from login pages to surveys.

---

## 📖 Explanation

### `<form>`
- Container for user input elements.
- Attributes:
  - `action` → URL where form data is sent.
  - `method` → Defines how data is sent (`get` or `post`).

### Common Form Elements
- `<label>` → Describes the input field (improves accessibility).
- `<input>` → Single-line input field.
  - `type="text"` → Text input.
  - `type="email"` → Email input (validates format).
- `<textarea>` → Multi-line text input.
- `<select>` → Dropdown menu with `<option>` choices.
- `<button>` → Clickable button (e.g., submit).

---

## 📝 Example Code

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="username" required>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="useremail">
  
  <button type="submit">Submit</button>
</form>
