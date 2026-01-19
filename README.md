# People Counter App 🧮

A simple beginner-friendly web application built using **HTML, CSS, and JavaScript**.
This project helps understand how a webpage works internally using basic JavaScript logic and DOM manipulation.

---

## 📂 Project Structure

* `index.html` – Defines the structure of the webpage
* `style.css` – Styles and designs the webpage
* `first.js` – Contains JavaScript logic and functionality

---

## 🌐 What This Project Does

* Displays a number showing how many people entered
* **INCREMENT** button increases the count by 1
* **SAVE** button stores the count as history
* After saving, the counter resets to 0

Example output:

```
Previous entries: 5 - 3 - 7 -
```

---

## 🧱 HTML (index.html)

HTML creates the **content and structure** of the page.

Important elements:

* `<h2 id="count-el">` → shows the current count
* `<button>` → used to trigger JavaScript functions
* `<p id="save-el">` → displays saved counts

Buttons use `onclick` to call JavaScript functions:

```html
<button onclick="increment()">INCREMENT</button>
<button onclick="save()">SAVE</button>
```

---

## 🎨 CSS (style.css)

CSS controls **how the page looks**:

* Centers content
* Styles buttons with colors
* Adjusts font size and spacing

Example:

* Increment button → red
* Save button → green

---

## ⚙️ JavaScript (first.js)

JavaScript controls **behavior and logic**.

### Key Concepts Used:

* Variables to store count
* Functions for button actions
* DOM manipulation using `getElementById`

### How It Works:

* `increment()` increases the count and updates the screen
* `save()` stores the count in history and resets it

---

## 🧠 `.textContent` vs `.innerHTML` (Brief)

### `.textContent`

* Used to set or get **plain text**
* Safe and fast

```javascript
countEl.textContent = count
```

### `.innerHTML`

* Can insert **HTML tags**
* Risky if used with user input

### Why `.textContent` is used here

* We only display numbers
* No HTML is required
* It is safer and cleaner

**Rule:**
👉 Use `.textContent` for text
👉 Use `.innerHTML` only when HTML is needed

---

## 🔄 How Everything Connects

1. HTML shows content
2. CSS styles it
3. JavaScript updates it dynamically when buttons are clicked

This is called **DOM manipulation**.

---



## 📘 What This Project Teaches

* Basic HTML structure
* CSS styling
* JavaScript functions
* DOM manipulation
* 
---

## ✅ Beginner Project

This is a **perfect starter project** for anyone learning JavaScript and frontend basics.

credits - "Scrimba.com" for javaScript project 
