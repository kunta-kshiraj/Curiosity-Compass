# Curiosity Compass: A Multiplayer Riddle Game

Curiosity Compass is a simple, real-time multiplayer game that blends classic riddle-solving with modern AI and web technologies.  
This proof-of-concept demonstrates how AI can inspire creativity, collaboration, and fun in a lightweight, browser-based format.

---

## 🎮 How to Play

The game is turn-based and runs for **5 rounds**.

### 1. Start or Join a Room
- One player creates a new room from the home screen.  
- A unique **Room ID** and **shareable link** are generated.  
- Other players can join using the Room ID or the link.  
- The game begins once at least **two players** are in the lobby.  

### 2. Submission Phase (⏱ 45 seconds)
- The player whose turn it is has **45 seconds** to either:
  - Type a word, or
  - Upload a picture of an object.  
- The AI processes this input and automatically generates a **riddle**.

### 3. Guessing Phase (⏱ 70 seconds)
- The timer resets to **70 seconds**.  
- All other players can submit guesses.  

**Hints**  
- 2 Hints will be Revealed at some time.  

**Scoring**  
- The first player to guess correctly earns the most points.  
- Subsequent correct guesses earn slightly fewer points.  
- If time runs out, no points are awarded.  

### 4. End of Game
- The game continues for **5 rounds**, rotating turns among players.  
- After the final round, a **scoreboard** is displayed with total scores.


### To run the web app
- Go to the respected folder and enter live-server --port=3000
---

## 🛠 Technology Stack
The goal of this project was to demonstrate a practical, lightweight approach to building an AI-powered multiplayer game.

### Frontend
- **React** — Used to build the dynamic, component-based user interface.
- **Tailwind CSS** — A utility-first CSS framework for rapid and responsive styling.

### Backend & Data
- **Firebase** — Provides a powerful, serverless backend.
- **Firestore** — Real-time NoSQL database for game state (rooms, players, scores, etc.).
- **Firebase Auth** — Anonymous authentication, so players can join instantly.

### Artificial Intelligence
- **Gemini API (gemini-1.5-flash)** —  
  A multimodal model that accepts both text and images.  
  It generates riddles and hints, powering the entire AI pipeline.

---

## 🚀 Future Vision

This MVP is a solid foundation for a full-featured product. Next steps include:

- **Scalable Backend**  
  - Migrating the core game logic to Firebase Cloud Functions would prevent cheating and secure the API keys.

- **Enhanced Features**  
  - Adding persistent user accounts, a global leaderboard, achievements, and more diverse game modes (e.g., mini-missions, story mode). 

- **Improved User Experience**  
  - Developing a multi-file front-end project to enhance performance and create a more polished UI with smooth animations and transitions.

---

## 📸 Demo- link
**
https://drive.google.com/file/d/1rjVDZ1XhYIolkSvPdc7Vq-2Z255OeJUy/view?usp=sharing

---
 
