# Dynamic Auto Typing Effect

A sleek, customizable auto-typing animation that simulates realistic typing and deleting effects. This project demonstrates DOM manipulation, timing functions, and dynamic text rendering in vanilla JavaScript.

## 🌐 Live Demo

**[View Live Demo](https://tbarnett42.github.io/Dynamic-Auto-Typing-Effect/)**

## 📋 Table of Contents

- [Live Demo](#live-demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Customization](#customization)
- [Learning Outcomes](#learning-outcomes)
- [Acknowledgments](#acknowledgments)

## ✨ Features

- **Smooth Typing Animation**: Realistic character-by-character text rendering
- **Dynamic Word Rotation**: Cycles through multiple phrases automatically
- **Customizable Speed**: Adjustable typing and deleting speeds
- **Lightweight**: Pure vanilla JavaScript with no dependencies
- **Responsive Design**: Works seamlessly across all devices

## 🛠 Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling and animations
- **JavaScript (ES6)**: Core typing logic and DOM manipulation

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/tbarnett42/Dynamic-Auto-Typing-Effect.git
```

2. Navigate to the project directory:
```bash
cd Dynamic-Auto-Typing-Effect
```

3. Open `index.html` in your browser or use a local development server.

## 🚀 Usage

Simply open the `index.html` file in a web browser to see the typing effect in action. The animation will automatically start and cycle through the predefined text array.

## 🔍 How It Works

The typing effect is achieved through:

1. **Text Array**: A collection of phrases stored in an array
2. **Character Iteration**: Each character is displayed one at a time using `setTimeout()`
3. **State Management**: Tracks current word, character position, and typing/deleting state
4. **Deletion Logic**: Removes characters in reverse after a pause
5. **Word Cycling**: Moves to the next word in the array after deletion completes

**Key Functions:**
- `type()`: Handles the typing animation
- `delete()`: Manages the deleting animation
- `setTimeout()`: Controls timing between character displays

## ⚙️ Customization

You can easily customize the typing effect by modifying these parameters:

```javascript
// Change the words that get typed
const words = ['Developer', 'Designer', 'Creator'];

// Adjust typing speed (in milliseconds)
const typingSpeed = 100;

// Adjust deleting speed (in milliseconds)
const deletingSpeed = 50;

// Pause duration before deleting (in milliseconds)
const pauseDuration = 2000;
```

## 📚 Learning Outcomes

Building this project helped me strengthen:

- DOM manipulation techniques
- JavaScript timing functions (`setTimeout`, `setInterval`)
- State management in vanilla JavaScript
- CSS animation and transition effects
- Code organization and readability

## 🙏 Acknowledgments

This project is based on a tutorial by **Code With Sahand**. I recreated it as part of my learning journey to understand DOM manipulation and JavaScript animations.

Original tutorial credit: [Code With Sahand](https://www.youtube.com/@CodeWithSahand)

---

## 📫 Connect With Me

Feel free to reach out if you have questions or suggestions!

- GitHub: [@tbarnett42](https://github.com/tbarnett42)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

---

⭐ If you found this project helpful, consider giving it a star!
