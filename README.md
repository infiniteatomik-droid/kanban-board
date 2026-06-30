# 📋 Interactive Kanban Board

A dynamic, state-managed Kanban Board application built with Vanilla JavaScript. It allows users to manage everyday tasks across different workflow stages.

## 🚀 Live Demo
https://infiniteatomik-droid.github.io/kanban-board/

## ✨ Features
* **Dynamic State Management:** Tasks are stored in a JavaScript array of objects and rendered dynamically based on their status.
* **Interactive Workflow Flow:** Users can move tasks from "Todo" to "In Progress", then to "Done", and finally delete them simply by clicking on the task cards.
* **Modern UI/UX:** Clean CSS layout featuring flexbox columns, clean task card designs, and smooth hover elevation effects.
* **Safe Input Validation:** Built-in form validation prevents users from submitting empty or space-only tasks.

## 🛠️ Tech Stack
* **HTML5** & **CSS3** (Flexbox, custom transitions, box-shadows)
* **Vanilla JavaScript** (ES6+, DOM manipulation, Event Listeners, Array.prototype.filter())

## 📖 What I Practiced in This Project
1. **Data-Driven UI:** Learned how to separate application data (state) from visual presentation, ensuring the DOM always mirrors the JavaScript array.
2. **Dynamic Event Binding:** Mastered creating HTML elements via JavaScript (`document.createElement`) and attaching dynamic event handlers to them on the fly.
3. **Array Manipulation:** Utilized methods like `forEach` for rendering and `filter` for safely deleting objects from the array by their unique IDs.

## 🔧 How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/infiniteatomik-droid/kanban-board.git
   ```
2. Open `index.html` in your favorite browser.
