<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=venom&color=0:00ffcc,100:1e90ff&height=220&section=header&text=Alien%20Invasion&fontSize=50&fontColor=ffffff&animation=fadeIn"
  />
</p>

<p align="center">
  <b>👾 Arcade-style Space Shooter • Built with Python & Pygame</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pygame-2.x-00A300?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Complete-007A33?style=for-the-badge" />
</p>

---

### 🎥 Gameplay Preview

<p align="center">
  <img src="https://via.placeholder.com/700x400.gif?text=Insert+Gameplay+GIF+Here" alt="Preview of Alien Invasion gameplay" width="700" />
</p>

---

## ✨ Core Features

This game implements classic arcade mechanics with increasing difficulty and persistent scoring, serving as a robust demonstration of object-oriented game design.

- **Responsive Controls:** Smooth player movement and accurate bullet firing using keyboard input.
- **Dynamic Difficulty:** The alien fleet accelerates and appears in faster waves as the player progresses, creating a challenging loop.
- **Scoring & High Scores:** Real-time score tracking and persistent storage of the highest achieved score across sessions.
- **Game State Management:** Implements clear states for Title Screen, Game Active, and Game Over, controlled by an event-driven loop.
- **Sound Effects:** Basic sound integration for laser firing and alien destruction (Crucial for game feel!).

## 🚀 Getting Started (How to Run)

To run this game locally, ensure you have Python installed and follow these steps.

### ⚙️ Prerequisites

You need Python 3.10 or higher and the Pygame library.

```bash
# Verify Python installation
python --version
```

## 🚀 Getting Started (How to Run)

To run this game locally, ensure you have Python installed and follow these steps.

### 📦 Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/your-username/alien-invasion.git](https://github.com/your-username/alien-invasion.git)
    cd alien-invasion
    ```

2.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    # If no requirements.txt is provided, you can install Pygame directly:
    # pip install pygame
    ```

### ▶️ Execution

Run the main game file directly from your terminal:

```bash
python alien_invasion.py
```

## 🕹️ Controls

| Action                 | Key(s)                   |
| :--------------------- | :----------------------- |
| **Move Ship Left**     | `←` (Left Arrow) or `A`  |
| **Move Ship Right**    | `→` (Right Arrow) or `D` |
| **Fire Bullet**        | `Spacebar`               |
| **Start/Restart Game** | `P` (Play)               |
| **Quit Game**          | `Q` or `Esc`             |

---

## 📚 Review & Reflection (BCA Student Perspective)

As a BCA student focusing on full-stack development and complex systems, completing _Alien Invasion_ was a valuable exercise in core software principles, specifically **Object-Oriented Programming (OOP)** and **Event-Driven Architecture**.

### On "Python Crash Course":

The book provides an incredibly structured and clear pathway from raw Python basics to applying those skills in a tangible project. The _Alien Invasion_ project served as an excellent introduction to:

- **Object-Oriented Design:** Effectively utilizing classes for the `Ship`, `Bullet`, and `Alien` to manage game state and behavior. This demonstrated how OOP makes code reusable and scalable.
- **Code Organization:** Learning how to manage modules for settings, sprites, and main game logic (separating concerns), a skill vital for larger development environments.
- **Iterative Development:** Building the game piece by piece—movement first, then bullets, then collisions—mirrored real-world agile methodology.

### 💡 Personal Takeaway:

This project was instrumental in solidifying my understanding of the **game loop**—the continuous cycle of handling input, updating game state, and rendering graphics.

While my career focus is on scalable web backends (Spring Boot/NestJS), this project reinforced the importance of **tight code structure** and **efficient state management**, skills that are directly transferable to any complex application.

> "A huge thanks to Eric Matthes for this foundational project. It’s a perfect bridge from theoretical learning to practical, rewarding development."

---

<p align="center">
  <sub>Built for learning. Polished for showcasing. 🚀</sub>
</p>

<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&color=0:1e90ff,100:00ffcc&height=120&section=footer"
  />
</p>
