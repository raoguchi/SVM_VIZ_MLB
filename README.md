# ⚾️ SVM Pitch Classifier Visualization

### By Alex Oguchi and Bhakin Phaneksiri

An interactive web-based tutorial and visualizer demonstrating how **Support Vector Machines (SVMs)** work using real MLB pitch data.

This project allows users to explore how a machine learning model makes decisions using only two features: **Release Speed** and **Release Spin Rate**, to classify pitch types such as Fastballs, Sliders, Changeups, and more.

## 🚀 Live Demo

Check it out here: [https://raoguchi.github.io/svm_viz_mlb](https://raoguchi.github.io/svm_viz_mlb)

---

## 📚 Project Overview

SVMs are powerful classification algorithms that calculate the optimal decision boundary between two classes. This project explains:
- What an SVM is and why it’s useful
- How it can be used to classify different pitch types in baseball
- Visual intuition behind decision boundaries and support vectors
- Limitations of SVMs in closely clustered data

### 🧠 Key Features:
- Interactive visualization of SVM decision boundaries
- Dynamic pitch pair selection
- Embedded math with MathJax for educational clarity
- Clean, responsive design using Svelte + Vite

---

## ⚙️ Tech Stack

- **Svelte** – Reactive front-end framework
- **Vite** – Fast bundler and dev server
- **MathJax** – Beautiful math rendering
- **GitHub Pages** – Deployed site hosting

---

## 🧪 Running Locally

```bash
git clone https://github.com/raoguchi/svm_viz_mlb.git
cd svm_viz_mlb
npm install
npm run dev

