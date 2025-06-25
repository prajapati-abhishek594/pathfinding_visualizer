# 🧭 Pathfinding Visualizer

An interactive **Pathfinding Visualizer** built with **React.js**, showcasing how various pathfinding algorithms explore the grid and find the shortest path.

This project helps understand the logic of famous algorithms using an animated grid, with user-controlled speed, start/end node selection, and pattern generation using Prim’s Maze.

---

## 🖼️ Project Demo UI

### Starting Main Page
![Visualizer Screenshot](./public/screenshots/starting_main_page.png)

### Dijstra Algorithm
![Visualizer Screenshot](./public/screenshots/dijstra_algorithm)

### Breadth First Search Algorithm
![Visulaizer Screenshot](./public/screenshots/breadth_first_search_algorithm)

### A* Algorithm
![Visulaizer Screenshot](./public/screenshots/A_star_algorithm)

---

## ✨ Features

- 🎯 Interactive **grid visualization**
- 🧱 Optional **maze generation** using **Prim's Algorithm**
- 🟩 Set **Start Node** and 🟥 **End Node** manually
- ⚙️ Select speed: Fast, Medium, Slow
- 🧠 Algorithms Supported:
  - ✅ Dijkstra's Algorithm
  - ✅ A* Search Algorithm
  - ✅ Breadth-First Search (BFS)
  - ✅ Depth-First Search (DFS)
- 📛 Clear options: Board, Walls, or just Path
- ✅ Fully functional **React app** with hooks and component ref usage

---

## 📂 Project Structure

```
pathfinding_visualizer-main/
├── public/
│   └── index.html, icons, manifest,screenshots,....
├── src/
│   ├── App.js                  # UI and user controls
│   ├── index.js                # Entry point
│   ├── index.css               # Styling
│   ├── pathfinding_visualizer/
│   │   └── grid.js             # Grid generation, interactivity
│   ├── algorithms/
│   │   ├── dijkstra.js
│   │   ├── A_star.js
│   │   ├── bfs.js
│   │   ├── dfs.js
│   └── maze generation/
│       └── prims_maze.js       # Prim’s Maze Generator
├── package.json
└── README.md
```

---

## 🚀 How to Run Locally

### 1. 📥 Clone the Repository
```bash
git clone https://github.com/prajapati-abhishek594/pathfinding-visualizer.git
cd pathfinding-visualizer
```

### 2. 💿 Install Dependencies
```bash
npm install
```

### 3. ▶️ Start the App
```bash
npm start
```

Then go to 👉 **http://localhost:3000** in your browser.

---

## 🎮 How to Use

1. **Pattern (Optional):** Select _"Prim's Algorithm Maze"_ to auto-generate a maze.
2. **Speed:** Choose how fast the animation should run.
3. **Algorithm:** Choose one of the supported algorithms to visualize.
4. **Make Pattern:** Generate the selected maze.
5. **Select Start/End Node:** Click on the green/red buttons and place them on the grid.
6. **Visualize Algorithm:** Click this to see the algorithm explore the grid.
7. **Clear Options:**
   - 🧹 Clear Board – resets everything
   - 🚧 Clear Walls – removes walls but keeps path
   - 🔄 Clear Path – removes previous animation only

---

## 🎨 Grid Colors

| Color     | Description         |
|-----------|---------------------|
| 🟩 Green   | Start Node          |
| 🟥 Red     | End Node            |
| ⚪ White   | Unvisited Node      |
| 🔵 Blue    | Visited Node        |
| 🟨 Yellow  | Shortest Path       |
| ⚫ Black   | Wall/Obstacle       |

---

## 🧠 Algorithms Summary

| Algorithm             | Weighted | Guarantees Shortest Path | Description |
|----------------------|----------|---------------------------|-------------|
| Dijkstra's           | ✅ Yes   | ✅ Yes                    | Expands uniformly |
| A* Search             | ✅ Yes   | ✅ Yes                    | Heuristic + Dijkstra |
| Breadth-First Search | ❌ No    | ✅ Yes                    | Uniform exploration |
| Depth-First Search   | ❌ No    | ❌ No                     | Explores deep first |

---


## 🛠️ Technologies Used

- React.js
- HTML5 + CSS3
- JavaScript (ES6)
- Functional Components + React Hooks
- Grid-based animation

---

## 📌 Future Improvements

- ✅ Drag & drop start/end nodes
- ✅ Add more maze generation algorithms (e.g., Recursive Division)
- ❌ Weighted Nodes (variable cost)
- ❌ Diagonal movement toggle


---
