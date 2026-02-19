# 🎮 KIDARA: Kids Digital Augmented Reality Assistant

![Project Status](https://img.shields.io/badge/Status-Active-success)
![Technology](https://img.shields.io/badge/Tech-HTML%20%7C%20JS%20%7C%20MediaPipe-blueviolet)
![License](https://img.shields.io/badge/License-MIT-blue)

**KIDARA** is a web-based Augmented Reality (AR) educational platform designed for children. It leverages **Computer Vision** and **Hand Tracking** technology to create an interactive learning experience where kids can play and learn using hand gestures without touching the screen/keyboard.

> *Belajar sambil bermain dengan teknologi Augmented Reality!* 🚀

## ✨ Features

-   **🖐️ Touchless Interaction:** Controlled entirely by hand gestures (MediaPipe Hands).
-   **📚 Educational Content:** Covers Math, English, Logic, and Reading.
-   **🌐 Web-Based:** No app installation required, runs directly in the browser.
-   **🎨 Kid-Friendly UI:** Colorful, animated, and easy to understand.

## 🕹️ Game Modes

This repository contains 5 exciting AR mini-games:

### 1. 🧩 Puzzle Master AR (`puzzle.html`)
Arrange scattered puzzle pieces using hand gestures to complete the image.
-   **Skill:** Spatial awareness & logic.
-   **Levels:** 10 Levels with increasing difficulty.

### 2. 🧮 AR Matematika (`math.html`)
Solve basic math problems (Addition, Subtraction, Multiplication, Division) by catching the correct falling numbers.
-   **Skill:** Basic arithmetic & quick thinking.

### 3. 🌳 AR Pintar: Sorting (`sort.html`)
Sort falling objects into the correct categories (e.g., Living vs. Non-living, Healthy vs. Sweet food).
-   **Skill:** Categorization & cognitive speed.

### 4. 🎨 Shape Spell (`english.html`)
Learn English vocabulary by catching floating letters to spell words correctly.
-   **Skill:** English vocabulary & spelling.

### 5. 🗣️ Alpha-Talk (`huruf.html`)
A reading practice game where kids catch letters to form Indonesian words and sentences.
-   **Skill:** Literacy & reading comprehension (Bahasa Indonesia).

## 🛠️ Tech Stack

-   **Frontend:** HTML5, CSS3, JavaScript (Vanilla).
-   **Computer Vision:** [Google MediaPipe Hands](https://developers.google.com/mediapipe).
-   **Audio:** Web Audio API & Speech Synthesis API (Text-to-Speech).

## 🚀 How to Run

Since this project uses the camera and MediaPipe, it requires a secure context (HTTPS) or localhost.

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/nabilagx/kidara.git](https://github.com/nabilagx/kidara.git)
    cd kidara
    ```

2.  **Run with Live Server (Recommended)**
    -   Install the **Live Server** extension in VS Code.
    -   Open the project folder in VS Code.
    -   Right-click on `index.html` (or any game file like `puzzle.html`) and select **"Open with Live Server"**.

3.  **Allow Camera Access**
    -   When the browser opens, click **Allow** when asked for camera permission.
    -   Stand back and show your hands to the camera! ✋

## 📸 Screenshots

| Puzzle Master | AR Matematika |
|:---:|:---:|
| *(Place screenshot here)* | *(Place screenshot here)* |

| Shape Spell | Alpha Talk |
|:---:|:---:|
| *(Place screenshot here)* | *(Place screenshot here)* |

## 🤝 Contributing

Contributions are welcome! If you have ideas for new games or improvements:
1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/NewGame`).
3.  Commit your changes (`git commit -m 'Add some NewGame'`).
4.  Push to the branch (`git push origin feature/NewGame`).
5.  Open a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
Made with ❤️ by **[Nabila Choirunisa](https://github.com/nabilagx)**
