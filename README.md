# Random-Color-Changer
# 🎨 Random Color Changer

A simple and interactive **Random Background Color Generator** built using **HTML, CSS, and JavaScript**. This app changes the background color dynamically with each button click and automatically adjusts text color for better readability.

---

## 🚀 Features

* 🎲 Generates a random background color on each click
* 🎨 Uses RGB color model for dynamic color creation
* 🎯 Automatically adjusts heading color (light/dark) based on background brightness
* ⚡ Instant UI update using DOM manipulation
* 🧼 Minimal and clean design

---

## 🧠 How It Works

* When the **"Change Color"** button is clicked:

  1. Three random values (Red, Green, Blue) are generated (0–255).
  2. These values are combined into an `rgb()` color format.
  3. The background color of the page is updated dynamically.
  4. The brightness of the color is calculated using a formula:

     ```
     (R × 299 + G × 587 + B × 114) / 1000
     ```
  5. Based on brightness:

     * Light background → Heading becomes **black**
     * Dark background → Heading becomes **white**

---

## 🛠️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Basic styling and layout
* **JavaScript (Vanilla JS)** – Logic and DOM manipulation

---

## 📂 Project Structure

```id="color-files"
index.html   # Contains HTML, CSS, and JavaScript
```

---

## 🎯 Learning Outcomes

This project helps in understanding:

* Random number generation (`Math.random()`)
* DOM manipulation (`querySelector`)
* Event handling (`addEventListener`)
* Dynamic styling using JavaScript
* Basic color theory (brightness and contrast)

---

## 📌 Future Improvements

* 🎨 Add smooth color transition animation
* 📋 Display and copy color code
* 🌈 Add gradient background generator
* 🎯 Apply auto color adjustment to more elements
* 🎛️ Add manual RGB sliders

---

## 🧑‍💻 Author

A beginner-friendly project to practice JavaScript interactivity and dynamic UI behavior.

---
