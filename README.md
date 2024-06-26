### Path Finder Visualizer

#### Overview
I have created a **Path Finder Visualizer** using JavaScript. This interactive tool showcases various pathfinding algorithms, including BFS, Dijkstra's Algorithm, and Greedy Best-First Search. It allows users to experiment with custom mazes and witness the algorithms in action. The speed of the visualizer and the size of the grid cells are also controllable. Tutorials will be added soon to enhance the user experience.

#### Features
- **Interactive Grid**: Users can click and drag to move the starting and target points.
- **Obstacle Placement**: Users can create walls by clicking on grid cells, simulating obstacles in the path.
- **Algorithm Selection**: Users can choose from several pathfinding algorithms to visualize.
- **Real-time Visualization**: Watch the algorithm in action as it calculates the shortest path in real time.
- **Path Highlighting**: The final path is highlighted to show the route taken by the algorithm.
- **Speed Control**: Adjust the speed of the visualization with a slider.
- **Pixel Control**: Modify the size of the grid cells for different levels of detail.

#### Pathfinding Algorithms
The visualizer supports multiple algorithms, each demonstrating different approaches to pathfinding:

1. **Breadth-First Search (BFS)**:
   - Explores all nodes at the present depth level before moving on to nodes at the next depth level.
   - Guarantees the shortest path in unweighted grids.

2. **Dijkstra’s Algorithm**:
   - Explores nodes with the smallest known distance from the source first.
   - Guarantees the shortest path in weighted grids.

3. **Greedy Best-First Search**:
   - Selects the node that appears to be the best choice based on a heuristic (usually the estimated distance to the target).
   - Does not guarantee the shortest path but can be faster in some cases.

#### User Interface
- **Grid**: The main area where the pathfinding visualization takes place.
- **Control Panel**:
  - **Algorithm Selection**: Dropdown menu to choose the pathfinding algorithm.
  - **Speed Control**: Slider to adjust the speed of the visualization.
  - **Pixel Control**: Slider to adjust the size of the grid cells.
  - **Clear Board**: Button to reset the grid.
  - **Start Visualization**: Button to begin the pathfinding process.

#### Installation
To use the Path Finder Visualizer, follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/praveent04/path-visualizer
   ```

2. **Open the Project**:
   - Navigate to the project directory and open `index.html` in a web browser.

#### Usage
1. Open the visualizer in your web browser.
2. Use the interactive grid to set the starting point, target point, and obstacles.
3. Select a pathfinding algorithm from the dropdown menu.
4. Adjust the speed and pixel size using the sliders.
5. Click the "Start Visualization" button to see the algorithm in action.
6. Click the "Clear Board" button to reset the grid and try a different configuration.

#### Upcoming Features
- **Tutorials**: Detailed tutorials will be added to help users understand how to use the visualizer and the principles behind each algorithm.

will deploy it soon
