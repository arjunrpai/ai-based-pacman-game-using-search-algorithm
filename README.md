# ai-based-pacman-game-using-search-algorithm

# 🎮 AI-Based Pacman Game using Greedy Best-First Search

## 📌 Overview
This project implements an **AI-powered Pacman game** where an intelligent agent navigates a maze, collects dots, and avoids ghosts using **Greedy Best-First Search (GBFS)**.

The agent makes decisions based on heuristic values, enabling **fast and efficient real-time gameplay**.

---

## 🚀 Features
- 🤖 AI-controlled Pacman agent  
- 🧠 Greedy Best-First Search algorithm  
- ⚡ Fast decision-making using heuristics  
- 👻 Dynamic ghost behavior (chase, scatter, power-up modes)  
- 🎮 Real-time movement and collision detection  
- 📊 Performance-based navigation  

---

## 🛠️ Technologies Used
- Python 🐍  
- Pygame 🎮  
- Data Structures (Priority Queue, Lists)  
- Artificial Intelligence (Search Algorithms)  

---

## 🧠 Core Algorithm: Greedy Best-First Search

### 🔍 Concept
Greedy Best-First Search selects the next move based only on the heuristic:

f(n) = h(n)

Where:
- h(n) = Estimated distance to the goal  

The algorithm always chooses the node that appears closest to the goal.

---

## ⚙️ How It Works
1. Pacman observes current position  
2. Evaluates possible moves  
3. Computes heuristic (distance to nearest target)  
4. Selects the best immediate move  
5. Repeats in real-time  

---

## 📊 Results & Analysis
- Uses **greedy directional heuristic** for movement  
- Decisions made locally at intersections  
- Ghosts assigned dynamic targets (chase/scatter modes)  
- Collision detection ensures valid paths  

👉 Outcome:
- Very fast execution  
- Low memory usage  
- Real-time responsiveness  

---

## 📈 Algorithm Comparison

| Algorithm | Type | Optimal | Speed | Memory |
|----------|------|--------|------|--------|
| BFS | Uninformed | ✅ | Slow | High |
| DFS | Uninformed | ❌ | Medium | Low |
| A* | Informed | ✅ | Fast | Medium |
| **Greedy** | Heuristic | ❌ | ⚡ Very Fast | Very Low |

---

## 🎯 Objectives
- Develop an AI-based Pacman agent  
- Implement heuristic-based decision making  
- Compare different search strategies  
- Optimize real-time navigation  


---

## 🔮 Future Scope
- Implement A* and Dijkstra algorithms  
- Add Reinforcement Learning (RL)  
- Improve ghost intelligence  
- Procedural maze generation  
- Multiplayer mode  

---

## 💡 Conclusion
This project demonstrates how **Greedy Best-First Search** can be effectively used for real-time decision-making in games.  
Although it does not guarantee optimal paths, it provides **excellent speed and responsiveness**, making it suitable for dynamic environments like Pacman.

---

## ⭐ How to Run
```bash
git clone https://github.com/your-username/pacman-ai.git
cd pacman-ai
python main.py
