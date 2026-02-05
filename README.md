# 💖 Valentine Quiz Website

A fun and romantic interactive quiz website built with **HTML, CSS, and JavaScript**.  
Designed for asking your girlfriend to be your Valentine in a playful and engaging way.

---

## ✨ Features
- **Four quiz questions**: Each question unlocks the next only if the correct answer is chosen.
- **Correct answer effect**: The selected button turns green for 1 second before moving to the next question.
- **Wrong answer effect**: Highlights the correct option in green if the wrong choice is selected.
- **Playful "No" button logic**:
  - If "No" is clicked, the button text changes to cute prompts like *"Are you sure?"*, *"Really sure? 🥺"*, etc.
  - Simultaneously, the "Yes" button grows larger and more irresistible.
- **Final celebration**:
  - Clicking "Yes" triggers a burst of floating hearts across the screen.
  - A sweet final message is displayed.
- **Background music**:
  - Romantic music starts automatically when the page loads.
  - Loops continuously to set the mood.
- **Floating hearts animation**:
  - Hearts gently float in the background throughout the quiz.

---

## 🛠️ Technologies Used
- **HTML5** – Structure of the quiz and content.
- **CSS3** – Styling, animations, and transitions.
- **JavaScript (ES6)** – Quiz logic, button interactions, heart animations, and music control.

---

## 🚀 Setup & Usage
1. Clone or download this repository.
2. Place your chosen romantic music file (e.g., `romantic.mp3`) in the project folder.
3. Update the `<audio>` tag in `index.html` if your file has a different name:
   ```html
   <audio id="bgMusic" autoplay loop>
     <source src="romantic.mp3" type="audio/mpeg">
   </audio>

## 🌐 Live Demo

you can access the quiz here:

👉 `https://shamgurav96.io/Will-You-Be-My-Valentine/`
