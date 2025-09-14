 
# Project Architecture

This document outlines the structural design of **Password Creator with Forum**.

## 🧱 Overview

The project is a static frontend application built with HTML, CSS, and JavaScript. It is modular, with each HTML file serving a distinct purpose.

## 🧩 Components

### 1. `index.html`
- Landing page
- Navigation hub for all modules

### 2. `Generator.html`
- Password generation logic
- Six levels of complexity
- JavaScript-driven entropy and randomness

### 3. `Analyzer.html`
- Password strength evaluation
- Visual feedback (color bars, score)
- Suggestions for improvement

### 4. `Forum.html`
- Collects user input (e.g. name, birth year)
- Generates personalized passwords
- Uses form data to influence output

### 5. `Boxe.html`
- Compares two passwords
- Displays strength side-by-side
- Highlights differences in entropy and structure

### 6. `Wayland.css`
- Custom styling framework
- Dark mode, blur effects, responsive layout
- Shared across all HTML files

## 🧠 Logic Flow

- User interacts with UI → triggers JS functions
- JS processes input → generates or analyzes password
- Output is rendered dynamically in the DOM

## 📦 Hosting

- Static deployment via Vercel
- No backend or database required

---

This architecture is lightweight, modular, and easy to extend. Ideal for educational use, customization, or integration into larger systems.
