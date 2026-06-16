# React via CDN (Basic Setup)

## 1. Overview
This is a simple way to use React without any build tools.  
Everything runs directly in the browser using script tags.

---

## 2. React Core Library
<script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>

- Provides React engine
- Handles components and state logic
- Does NOT interact with the DOM directly

---

## 3. ReactDOM Library
<script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>

- Connects React to the browser DOM
- Handles rendering UI into HTML
- Acts as a bridge between React and the web page

---

## 4. Mounting Point
<div class="js-container"></div>

- Empty HTML container
- React renders UI inside this element
- Becomes the controlled area of React

---

## 5. Create React Root
const container = document.querySelector('.js-container');
const root = ReactDOM.createRoot(container);

- Selects the DOM element
- Converts it into a React root
- Hands control to React rendering system

---

## 6. Render UI
root.render('Welcome to First Day of React!');

- Displays content inside the container
- React manages UI updates efficiently
- First visible output on the page

---

## 7. Key Idea
React does not directly manipulate the DOM.

Instead:
You describe what UI should look like → React handles rendering.

---

## 8. Real-World Note
This is for learning only.

In real applications:
- JSX is used instead of strings
- Components replace direct rendering
- Tools like Vite / Next.js handle setup
- UI becomes modular and scalable

---

## 9. Mental Model
React = Smart UI engine that controls a section of the page efficiently.