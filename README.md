# 🎯 Aim Trainer Game (Python + Pygame)

<p align="center">
  <b>An interactive aim-tracking game built using Python and Pygame to improve mouse precision, speed, and accuracy.</b>
</p>

---

## 🚀 About the Project

The **Aim Trainer Game** is a desktop-based application developed using **Python and Pygame** that helps users practice and improve their mouse aiming skills.  
Targets appear at random positions on the screen and grow/shrink dynamically, challenging the player’s reaction time and precision.

The game tracks key performance metrics such as **hits, misses, speed, accuracy, and survival time**, providing instant feedback to the player.

---

## ✨ Features

✅ Randomly spawning targets  
✅ Smooth target growth and shrink animation  
✅ Mouse click collision detection  
✅ Real-time performance tracking  
✅ Lives system to increase difficulty  
✅ End screen with detailed statistics  
✅ Clean and minimal game UI  

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|--------|
| 🐍 Python | Core programming language |
| 🎮 Pygame | Game development & rendering |
| 🧮 Math | Distance & collision calculation |
| ⏱️ Time | Game timing & performance tracking |
| 🎲 Random | Random target generation |

---

## 🎮 Gameplay Mechanics

- Targets spawn every few milliseconds at random positions.
- Targets grow and shrink over time.
- Clicking inside a target counts as a **hit**.
- Missing or letting a target disappear costs a **life**.
- Game ends when all lives are lost.

---

## 📊 Performance Metrics

The game calculates and displays:
- ⏱️ Time survived  
- 🎯 Total hits  
- ⚡ Hit speed (targets per second)  
- 🎯 Accuracy percentage  
- ❤️ Remaining lives  

---

## ▶️ How to Run the Game

### 1️⃣ Install Pygame
```bash
pip install pygame
