# Space-Shooter-PY-game
# 🚀 SpaceShooter Game

A fast-paced 2D Space Shooter game built using **Python** and **Pygame**.
Control your spaceship, shoot lasers, destroy meteors, and survive as long as possible!

---

## 🎮 Game Features

* Smooth player movement (W, A, S, D keys)
* Laser shooting with cooldown system (SPACE key)
* Random meteor spawning
* Meteor rotation animation
* Explosion animation with sound effects
* Background stars for space effect
* Score based on survival time
* Background music and sound effects
* Mask-based collision detection for accurate hits

---

## 🛠️ Technologies Used

* Python 3
* Pygame Library

---

## 📂 Project Structure

```
SpaceShooter/
│
├── images/
│   ├── player.png
│   ├── meteor.png
│   ├── laser.png
│   ├── star.png
│   ├── explosion/
│   └── Oxanium-Bold.ttf
│
├── audio/
│   ├── laser.wav
│   ├── explosion.wav
│   ├── damage.ogg
│   └── game_music.wav
│
├── main.py
└── README.md
```

---

## 🎯 Controls

| Key   | Action      |
| ----- | ----------- |
| W     | Move Up     |
| A     | Move Left   |
| S     | Move Down   |
| D     | Move Right  |
| SPACE | Shoot Laser |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/spaceshooter.git
cd spaceshooter
```

### 2️⃣ Install Dependencies

Make sure Python is installed, then install pygame:

```bash
pip install pygame
```

### 3️⃣ Run the Game

```bash
python main.py
```

---

## 💥 How the Game Works

* Meteors spawn every 500 milliseconds.
* Player can shoot lasers with a short cooldown.
* If a laser hits a meteor:

  * Meteor is destroyed
  * Explosion animation plays
  * Sound effect plays
* If a meteor hits the player:

  * Game ends
* Score increases based on survival time.

---

## 🧠 Concepts Used

* Object-Oriented Programming (Classes & Objects)
* Sprite Groups
* Collision Detection (Mask-based)
* Delta Time Movement
* Custom Events
* Animation using frame indexing
* Sound and Music Handling

---

## 📸 Gameplay Preview

(Add screenshots or gameplay GIF here)

---

## 🚀 Future Improvements

* Add health system
* Add levels with increasing difficulty
* Add power-ups
* Add main menu and restart option
* Add high score saving system

---

## 👨‍💻 Author

Developed by **Dev Patel**
B.Tech Student | Python Developer

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!

---

### 🎉 Enjoy Playing SpaceShooter!


