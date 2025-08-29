🛤️ Shortest Path Finder
🚀 Project Overview

The Shortest Path Finder is an interactive pathfinding visualizer built using HTML, CSS, and JavaScript. It allows users to dynamically explore popular pathfinding algorithms like BFS, Dijkstra, and A* on a customizable grid.

This tool also introduces terrain weights (Normal, Grass, Water, Mountain) and supports import/export of grid states, making it a versatile project for learning and experimenting with graph algorithms.

🔗 Live Demo

👉 Shortest Path Finder on Netlify

📸 Demo Preview
<table> <tr> <td> <img src="Images/Home.png" alt="Home Page" width="400"> </td> <td> <img src="Images/Obstacles.png" alt="Obstacles Example" width="400"> </td> </tr> <tr> <td align="center">Grid Initialization</td> <td align="center">Adding Obstacles</td> </tr> <tr> <td> <img src="Images/Dijkstra.png" alt="Dijkstra Algorithm" width="400"> </td> <td> <img src="Images/AStar.png" alt="A* Algorithm" width="400"> </td> </tr> <tr> <td align="center">Shortest Path using Dijkstra</td> <td align="center">Shortest Path using A*</td> </tr> </table>

(You can replace the above placeholders with actual screenshots from your project’s Images/ folder.)

🌟 Features

🛤️ Pathfinding Visualization: Watch algorithms find the shortest path in real-time.

🧮 Supported Algorithms:

BFS – Finds the shortest path in unweighted grids.

Dijkstra’s Algorithm – Weighted shortest path search.

A Algorithm* – Optimized heuristic + weighted search.

🌍 Terrain Support:

Normal (weight = 1)

Grass (weight = 2)

Water (weight = 5)

Mountain (weight = 10)

💻 Interactive Interface:

Set Start & End points

Add Obstacles & Terrains

Visualize Visited & Path nodes

📂 Grid Management:

Export grid configuration as JSON

Import saved grid configuration

📚 Project Structure

index.html → UI structure and controls

style.css → Styling for grid, buttons, and terrains

script.js → Core logic for pathfinding algorithms and interactions

🛠️ How to Run Locally

Clone the repository:

git clone https://github.com/Ritesh972004/Shortest_Path_Finder.git


Navigate to the project directory:

cd Shortest_Path_Finder


Open index.html in your browser to start the visualizer.

📌 Future Improvements

Add more algorithms (Greedy Best-First, Bidirectional Search).

Mobile-friendly responsive grid.

Save/load multiple scenarios.