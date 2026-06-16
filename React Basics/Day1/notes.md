# React & ReactDOM – Small Descriptive Note

## React

React is a JavaScript library used for building user interfaces. It provides the core building blocks for developing applications, such as components, state management, props, and hooks. These features are designed to be reusable and work across different platforms.

React focuses on **what the UI should look like**, not how it is rendered.

---

## ReactDOM

ReactDOM is a companion library used specifically for web applications. It connects React with the browser and is responsible for rendering React components into the HTML Document Object Model (DOM).

ReactDOM handles **how React components are displayed and updated in the browser**.

---

## Key Idea

* **React = Shared core features (logic, components, state)**
* **ReactDOM = Web-specific rendering engine**

React can be used beyond the web (e.g., mobile apps via React Native), but ReactDOM is only required for browser-based applications.

---

## Simple Structure View

React (Core Library)
        |
   ----------------
   |              |
ReactDOM    React Native
(Web)       (Mobile)
```
