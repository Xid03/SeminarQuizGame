<div align="center">

# Seminar Quiz Game

### A fast, browser-based object identification quiz for interactive learning sessions.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tone.js](https://img.shields.io/badge/Tone.js-000000?style=for-the-badge&logo=javascript&logoColor=white)](https://tonejs.github.io/)

[Repository](https://github.com/Xid03/SeminarQuizGame) · [Demo Setup](#demo) · [Usage](#usage)

</div>

---

## Project Overview

**Seminar Quiz Game** is a lightweight web-based quiz game designed to make learning sessions, seminars, and classroom activities more interactive. Players are shown multiple object images and must quickly identify the correct item before the timer runs out.

The project is built as a simple single-page application using HTML, Tailwind CSS, vanilla JavaScript, and Tone.js for sound feedback. It runs directly in the browser with no build tools or backend setup required.

---

## Features

- **Timed quiz rounds** with a fast two-second challenge window.
- **Randomized object selection** to keep each round different.
- **Eight image choices per round** for a competitive visual challenge.
- **Instant answer feedback** for correct, incorrect, and timeout results.
- **Sound effects** for success, errors, timer ticks, and timeout events.
- **Responsive layout** that adapts across desktop and smaller screens.
- **Modern dark UI** with gradient highlights and interactive hover states.
- **No installation complexity** because the app runs from a single HTML file.

---

## Tech Stack

| Technology | Purpose |
| --- | --- |
| **HTML5** | Page structure and game markup |
| **Tailwind CSS CDN** | Utility-first styling and responsive UI classes |
| **Vanilla JavaScript** | Game logic, timer, randomization, and UI state |
| **Tone.js** | Browser-based sound effects |
| **Placehold.co** | Placeholder object images used by the quiz |

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Xid03/SeminarQuizGame.git
cd SeminarQuizGame
```

No package installation is required.

---

## Usage

You can run the project in either of these ways:

### Option 1: Open Directly

Open `index.html` in your browser.

### Option 2: Run With a Local Server

```bash
python -m http.server 5500
```

Then visit:

```text
http://localhost:5500
```

To play:

1. Click **Start Game**.
2. Read the prompt, for example: `Find the: "Laptop"`.
3. Select the matching image before the timer ends.
4. Review the result popup and click **Play Again** to restart.

---

## Screenshots

Screenshots can be added after capturing the app UI.

Recommended structure:

```text
assets/
|-- screenshots/
    |-- home-screen.png
    |-- quiz-round.png
    |-- result-popup.png
```

Example markdown once screenshots are added:

```markdown
![Home Screen](assets/screenshots/home-screen.png)
![Quiz Round](assets/screenshots/quiz-round.png)
![Result Popup](assets/screenshots/result-popup.png)
```

---

## Demo

The project is ready to run locally from `index.html`.

For a hosted version, enable **GitHub Pages** from the repository settings and publish from the `main` branch. After GitHub Pages is enabled, the demo will be available at:

```text
https://xid03.github.io/SeminarQuizGame/
```

---

## Folder Structure

```text
SeminarQuizGame/
|-- index.html      # Main application file
|-- index.txt       # Reserved project file
`-- README.md       # Project documentation
```

---

## Future Improvements

- Add score tracking and round history.
- Introduce difficulty levels with different timer durations.
- Replace placeholder images with custom or real object assets.
- Add category-based quizzes, such as food, sports, electronics, and furniture.
- Include leaderboard support for classroom or seminar competition.
- Add accessibility improvements for keyboard navigation and screen readers.
- Package the app as a Progressive Web App for offline use.

---

## Contact Information

**Project Owner:** [Xid03](https://github.com/Xid03)

**Repository:** [SeminarQuizGame](https://github.com/Xid03/SeminarQuizGame)

For suggestions, improvements, or collaboration, open an issue or submit a pull request through the GitHub repository.

---

<div align="center">

Built for quick, interactive, and engaging quiz sessions.

</div>
