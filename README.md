# 🚀 Graph Search Algorithms Visualization

This project implements and visualizes various graph search algorithms, including:

- **Bi-Directional BFS** 🔄
- **Standard BFS** 🔍
- **Depth First Search (DFS)** 🌲
- **Dijkstra's Shortest Path Algorithm** 📏

The program allows users to input a start and goal node, then runs the algorithms to find paths between them. Additionally, the graph and its shortest path (from Dijkstra's Algorithm) are visualized using `networkx` and `matplotlib`. 🎨

## 📌 Features
- **Bi-Directional BFS**: Finds the shortest path faster by searching from both the start and goal simultaneously.
- **BFS**: Explores all possible paths in breadth-first order.
- **DFS**: Explores paths in depth-first order.
- **Dijkstra’s Algorithm**: Finds the shortest weighted path.
- **Graph Visualization**: Displays the graph structure with edge weights and highlights the shortest path.

## 🛠️ Installation
Make sure you have Python installed. Then, install the required dependencies:

```sh
pip install networkx matplotlib
```

## 🚀 Usage
Run the script and input the start and goal nodes when prompted:

```sh
python graph_search.py
```

Example input:
```
Enter start node: A
Enter goal node: V
```

Example output:
```
Bi-Directional BFS Path: ['A', 'B', 'E', 'K']
Standard BFS Path: ['A', 'B', 'E', 'K']
Standard DFS Path: ['A', 'B', 'E', 'K']
Shortest Weighted Path using Dijkstra: ['A', 'B', 'E', 'K'] with cost 11
```

A visualization of the graph will be displayed, with the shortest path highlighted in red. 🔴

## 📁 Project Structure
```
📂 Graph-Algorithms-Visualization
├── 📜 graph_search.py  # Main Python script
├── 📜 README.md        # Project documentation
└── 📜 requirements.txt # Dependencies list (if needed)
```

## 👨‍💻 Contributing
Feel free to fork this repository, improve the code, and submit a pull request! 🚀

## 📜 License
This project is licensed under the MIT License.

---

Enjoy exploring graphs! 🎯
