# 🧠 Intellect Quiz

[![GitHub license](https://img.shields.io/github/license/abhishekxshrma/Intellectual-quiz?style=flat-square&color=blue)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive Design](https://img.shields.io/badge/Responsive-Yes-success?style=flat-square)](https://en.wikipedia.org/wiki/Responsive_web_design)

**Intellect Quiz** is a beautifully designed, highly interactive, and responsive web application designed for lifelong learners to challenge their knowledge across multiple domains. Built with raw, semantic HTML5, modern vanilla CSS3, and interactive ES6+ JavaScript, this application delivers a premium, gamified quiz experience directly in the browser—with zero server setup required.

---

## 📌 Project Status

> **Note**: This is a **1-year academic/development project**. It is designed to be continuously updated, refactored, and expanded in the future as new ideas, features, and modern web standards are introduced.

---

## 🌟 Key Features

- **⏱️ Timed Gameplay**: Each question runs on a strict 15-second timer. The timer badge features a dynamic countdown warning (pulsing red visual cues) when time is running low (4 seconds left) to elevate the action.
- **📊 Local Stats Dashboard**: Automatically tracks and persists your high scores and attempt history locally using browser `localStorage`. View your cumulative progress in a dashboard on the home page.
- **🎨 Glassmorphic & Premium UI**: Features a modern, polished aesthetic with smooth gradients, translucent overlays, hover micro-animations, and styled visual feedback.
- **🧠 4 Diverse Quiz Categories**:
  - **CSS Styling** (Hard): Selectors, Flexbox alignments, grid properties, and styling rules.
  - **Geography** (Medium): World capitals, oceans, landscapes, and landmarks.
  - **History** (Medium): Historical figures, global events, and key moments.
  - **Sports** (Easy): Championship records, athletes, and general trivia.
- **📝 Post-Quiz Performance Review**: Once a quiz is completed, the game shows a full breakdown of the questions, highlighting which ones you got right, which ones you missed, what you selected, and the correct answers.
- **🔒 Privacy-First & Serverless**: No registration or database needed. Your high scores and inputs remain securely on your device.
- **📱 Fully Responsive Design**: Seamless layout adjustments for smartphones, tablets, and desktop displays.

---

## 📂 Project Structure

```text
├── .git/                  # Git repository details
├── README.md              # Project documentation
├── index.html             # Homepage & high-scores dashboard
├── select.html            # Category selection screen
├── about.html             # About story, mission, and highlights
├── services.html          # Features and services summary
├── contact.html           # Feedback form with local persistence
├── global.css             # Main stylesheet (design variables & utilities)
├── quiz-css.html          # CSS quiz page & game script
├── quiz-geography.html    # Geography quiz page & game script
├── quiz-history.html      # History quiz page & game script
└── quiz-sports.html       # Sports quiz page & game script
```

---

## 🚀 Getting Started

Since Intellect Quiz is a serverless front-end application, running it locally is incredibly easy:

### Method 1: Direct Execution
1. Clone this repository or download the source files.
2. Double-click the `index.html` file in your project directory to open it in your preferred browser.

### Method 2: Local Web Server (Recommended)
For the best experience with paths and potential future browser capabilities, run a local web server:

- **Using VS Code Live Server**: Install the "Live Server" extension, open the directory in VS Code, and click the **Go Live** button at the bottom-right.
- **Using Python**:
  ```bash
  python -m http.server 8000
  ```
  Then navigate to `http://localhost:8000` in your web browser.
- **Using Node.js (`http-server`)**:
  ```bash
  npx http-server
  ```

---

## 🛠️ Technology Stack

- **Core Structure**: [HTML5](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
- **Styling**: [Vanilla CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) (using custom CSS Variables, Flexbox, CSS Grid, and custom keyframe animations)
- **Interactive Logic**: [Vanilla ES6+ JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- **Fonts**: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (via Google Fonts)
- **Icons**: [Font Awesome v6](https://fontawesome.com/)

---

## 📈 Future Enhancements Roadmap

- [ ] **Dark Mode Toggle**: Introducing an alternative dark theme using dynamic CSS variable swaps.
- [ ] **Sound Effects & Haptics**: Adding optional audio cues for correct/incorrect answers and timer warnings.
- [ ] **Custom Quiz Creator**: Allowing users to write their own questions and export them as JSON.
- [ ] **Leaderboards**: Integration with simple backend API to share high scores globally.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

*Made with ❤️ for Visual and Technical Excellence.*
