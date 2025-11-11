# 🧭 Pathfinding and Maze Generation Visualizer

An interactive web-based visualizer for pathfinding algorithms and maze generation, built using **React**. This project helps users understand how popular algorithms like **Dijkstra's**, **A\***, **DFS**, and **BFS** work in real-time on a grid interface.

## 🚀 Live Demo

👉 [Check App - Deployed Link](https://graph-algorithms-visualizer.vercel.app/)  


## 📌 Features

- **Visualizes popular pathfinding algorithms**
- **Generates mazes using various generation techniques**
- **Interactive grid with drag-and-drop support for start/end nodes and walls**
- **Clear, reset, and step-through visual options**

## 🧠 Pathfinding Algorithms

| Algorithm                     | Weighted | Guarantees Shortest Path | Notes                                      |
|------------------------------|----------|---------------------------|--------------------------------------------|
| Dijkstra's Algorithm         | ✅       | ✅                        | Guarantees shortest path                   |
| A* Search                    | ✅       | ✅                        | Uses heuristics to improve performance     |
| Greedy Best-First Search     | ✅       | ❌                        | Fast, but may not find optimal path        |
| Bidirectional Greedy Search  | ✅       | ❌                        | Faster alternative to greedy search        |
| Breadth-First Search (BFS)   | ❌       | ✅                        | Explores all neighbors uniformly           |
| Depth-First Search (DFS)     | ❌       | ❌                        | Can get stuck; not optimal                 |
| Random Walk                  | ❌       | ❌                        | May get trapped; mostly for fun!           |

## 🏗️ Maze Generation Algorithms

- 🔀 **Random Maze**
- 🧱 **Recursive Division Maze**
- ↕️ **Vertical Division Maze**
- ↔️ **Horizontal Division Maze**

## 💻 Technologies Used

- **React JS** (with Create React App)
- **JavaScript / HTML / CSS**
- **DOM Manipulation for visualization**

## 📂 Getting Started

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/pathfinding-visualizer.git
cd pathfinding-visualizer

# Install dependencies
npm install

# Start the development server
npm start


 
HTML
1.0%
Footer
© 2
