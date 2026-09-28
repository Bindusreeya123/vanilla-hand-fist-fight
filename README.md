# vanilla-hand-fist-fight 🗿📄✂️

Welcome to the **Vanilla Hand Fist Fight** repository! This is a lightweight, responsive web application implementing a **Rock Paper Scissors Series Engine** built using pure vanilla frontend technologies from scratch.

---

## ⚡ Features & Functionality

*   **Target Limit Framework:** Users can input a custom match threshold (e.g., 3, 5, or 10 rounds). Setting a target auto-resets active statistics to guarantee a clean series run.
*   **Automated Runtime Matrix:** Features a programmatic opponent AI matrix driven by automated range probabilities using `Math.random()`.
*   **Wobble-Free Score Board:** Keeps real-time updates for Player score, Computer score, and Tie frequencies printed instantly to the dynamic dashboard.
*   **Endgame Determination Overlays:** Detects the final matching round using localized micro-tasks (`setTimeout`) to deliver series winner alert panels.
*   **Geometric Styles:** Features circular action control points, balanced centering layout configurations, and a clean structural scoreboard panel.

---

## 🛠️ Tech Used

*   **HTML5:** Structural layout blocks, numerical configurations, and input elements.
*   **CSS3:** Flexbox matrix layouts, centering constraints, border geometries, and custom styling filters.
*   **Vanilla JavaScript (ES6+):** Programmatic win/loss matrix validations, matching event handlers, and data normalization.

---

## 📂 Project Structure

```text
├── index.html   # Holds structural view layers and core JS game loop mechanics
└── style.css    # Flexbox alignment controls and geometric styling blocks
```

---

## 🚀 How to Run Locally

1. **Clone or Download** this repository folder to your machine.
2. Open the directory and locate the `index.html` file.
3. Double-click `index.html` to **launch it directly in any web browser**—no server setup required!

---

## 🎮 How to Play

1. **Set a Target:** Enter the number of rounds you want the series to last in the input field and click **Set Target**.
2. **Make Your Move:** Click on 🗿 (Rock), 📄 (Paper), or ✂️ (Scissors) to play a round.
3. **Check the Log:** Open your browser's Developer Console (`F12`) to view background decision calculations and live metrics.
4. **View Final Results:** Once the round limit is reached, an alert box highlights the series champion before resetting the engine!
