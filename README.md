# 🧱 Brick Breaker Game (Java Swing)

A simple **Brick Breaker Game** built using **Java Swing and AWT**.
Control the paddle, bounce the ball, and break all the bricks to win!

---

## 🎮 Features

* Interactive paddle movement using keyboard
* Ball collision detection (walls, paddle, bricks)
* Score tracking system
* Game Over and Win states
* Restart functionality
* Clean and simple UI using Java Graphics

---

## 🛠️ Technologies Used

* Java
* Swing (GUI)
* AWT (Graphics & Events)

---

## 📂 Project Structure

```
Brick-Breaker/
│
├── Main.java          # Entry point of the application
├── GamePlay.java      # Game logic and rendering
├── MapGenerator.java  # Brick layout generation
```

---

## ▶️ How to Run

### 1️⃣ Install Java JDK

Make sure Java is installed:

```
java -version
javac -version
```

---

### 2️⃣ Compile the Project

Open terminal in project folder and run:

```
javac *.java
```

---

### 3️⃣ Run the Game

```
java Main
```

---

## 🎯 Controls

| Key      | Action            |
| -------- | ----------------- |
| ⬅️ Left  | Move paddle left  |
| ➡️ Right | Move paddle right |
| Enter    | Restart game      |

---

## 🧠 Game Logic Overview

* Ball moves continuously using a timer
* Collision detection is handled using `Rectangle` class
* Bricks disappear when hit by the ball
* Score increases for each brick destroyed
* Game ends when:

  * Ball touches bottom → Game Over
  * All bricks destroyed → You Win

---

## 📸 Screenshots

<img width="852" height="736" alt="Screenshot" src="https://github.com/user-attachments/assets/906c158d-e87d-4ef2-8ca4-11ac8f0c79f8" />


---

## 🚀 Future Improvements

* Add sound effects 🔊
* Multiple levels 🎯
* Power-ups (extra life, bigger paddle)
* Pause/Resume feature
* High score saving

---

## 🤝 Contributing

Feel free to fork this repo and improve the game!

---

## 📄 License

This project is open-source and free to use.

---

## 👩‍💻 Author

Gundu Ashritha

---

⭐ If you like this project, give it a star on GitHub!
