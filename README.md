# Restricted-TextArea

A simple HTML, CSS, and JavaScript project that demonstrates how to restrict user input in a `<textarea>` field to a specific number of characters. It also provides live character counting and displays an error message when the limit is exceeded.

---

## 🚀 Features
- Live character count while typing.
- Restricts input to a **maximum of 250 characters**.
- Displays an error message once the user reaches the character limit.
- Clean, minimal UI with responsive design.

---

## 🛠️ Technologies Used
- **HTML5** – for structure.
- **CSS3** – for styling and layout.
- **JavaScript (Vanilla JS)** – for input validation and live character updates.

---

## 📂 Project Structure
.
├── index.html # Main HTML file


---

## 📖 How It Works
1. User starts typing in the textarea.
2. A live counter (`currentLength/maxLength`) updates with each keystroke.
3. Once the maximum character limit is reached:
   - An error message is displayed.
   - Further typing is blocked (handled by `maxlength` attribute).

---

## ▶️ Usage
1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Start typing into the textarea to see character restrictions in action.

---

## ✨ Example
- Input: `"Hello World!"`  
- Counter: `12/250 characters`  
- If the user tries to type beyond 250 characters, they will see a red warning message.

---

## 📌 Notes
- You can adjust the maximum character limit by changing the `maxlength` attribute in the `<textarea>` element:
  ```html
  <textarea id="myTextarea" maxlength="250"></textarea>

https://roadmap.sh/projects/restricted-textarea
