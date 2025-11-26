# JavaScript Fundamentals Quiz

A simple interactive quiz that teaches the basics of the DOM, JavaScript logic, and event handling. This project is perfect for beginners learning how HTML, CSS, and JavaScript work together to create dynamic web applications.

---

## Features

* Multiple‑choice JavaScript questions
* Dynamic question loading
* Visual feedback for correct/incorrect answers
* Score screen at the end
* Ability to restart the quiz
* Fully customizable colors and questions

---

## Project Structure

```
index.html → main HTML, CSS, and JS combined
```

You can separate CSS and JS into their own files later if you want a cleaner structure.

---

## Setup Instructions

### **1. Download or Copy the Project Files**

* Copy the code from the project into a file called **index.html**
* Or download your existing file if you're working from a code editor.

### **2. Open the Project Locally**

You have two options:

#### **Option A: Open Directly in Your Browser**

1. Right‑click `index.html`
2. Choose **Open With → Chrome / Firefox / Edge**
3. The quiz will load immediately

#### **Option B: Use a Live Server (Recommended for Development)**

If you're using VS Code:

1. Install the **Live Server** extension
2. Right‑click `index.html`
3. Select **Open with Live Server**
4. Changes will auto‑refresh as you edit

### **3. Customize the Quiz**

Open the `<script>` section and edit this area:

```js
const quizData = [
  {
    question: "Your question here",
    options: ["Option 1", "Option 2", "Option 3", "Option 4"],
    answer: 0
  }
];
```

You can:

* Add more questions
* Change answer choices
* Add images
* Change colors in the `<style>` section

---

## Customization Tips

* You can adjust the pink, black, and grey theme in the CSS section
* Buttons can be made bigger, rounded, or animated
* You can insert a Start Screen before the quiz loads
* Question order can be randomized using `Math.random()`

---

## How to Add More Functionality

Here are some optional enhancements you can build later:

* Timer countdown
* Progress bar
* Final review screen showing all answers
* Sound effects for correct/incorrect choices
* Save high scores using localStorage

