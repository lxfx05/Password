 
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
