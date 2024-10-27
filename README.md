# Map-Based Pathfinding Visualizer

An interactive web-based application for visualizing various pathfinding algorithms on a grid, now enhanced with map-based routing features. This tool allows users to set start, target, and bomb nodes, and visualize how different algorithms explore the grid and map to find the shortest path in real-world environments.

## Features

- **Start & Target Nodes**: Set your starting point and destination on the grid or directly on the map.
- **Pathfinding Algorithms**: Visualize popular pathfinding algorithms like A*, Dijkstra's, and more.
- **Bomb & Weight Nodes**: Add bomb nodes (blockers) or weight nodes (delays) to observe how they affect the pathfinding process.
- **Grid-Based Visualization**: The grid is visualized with clear node representations for walls, visited nodes, shortest-path nodes, and more.
- **Map Integration**: Option to visualize paths directly on a map using OpenStreetMap.
- **Search Location**: Find cities using the search bar and integrate that with your pathfinding grid.

## Getting Started

### Prerequisites

To run this project locally, you will need:
- A modern web browser (Chrome, Firefox, Edge, etc.)
- Internet connection for fetching external libraries (Leaflet.js, Bootstrap, etc.)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AadityaKGupta/PathFinding-Visualizer.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd Map-Based-Pathfinding-Visualizer
   ```
3. **Open the `index.html` File in a Browser**: You can simply open the `index.html` file in your browser to run the application.

### Start Visualizing

1. Select a start node and a target node on the grid **or directly on the map**.
2. Pick an algorithm from the "Algorithms" dropdown.
3. Hit "Visualize!" to see the algorithm in action.
4. In the top right corner, you’ll see the map-based visualizer. Click it to open the map.
5. Once the map is displayed, click "Allow" to grant access to your location if prompted.
6. On the map, you can:
   - **Set the Start Node** by clicking on your desired starting location.
   - **Set the End Node** by clicking on your target destination.
7. And you can find the shortest path between the startNode and endNode.

## Usage

- **Start Node**: Click on the grid or map to set your starting position.
- **Target Node**: Select your destination node on the grid or map.
- **Bomb Node**: Place a bomb (or obstacle) to make pathfinding more challenging.
- **Weight Node**: Place weighted nodes to simulate additional traversal cost.
- **Clear Board**: Reset the grid for a fresh start.
- **Clear Path**: Retain nodes but reset the path visualization.
- **Use in Map**: Use the integration with OpenStreetMap to visualize your pathfinding in a real-world context.

## Technologies Used

- **HTML5 / CSS3 / JavaScript**: Core front-end technologies.
- **Leaflet.js**: For map visualization and integration.
- **Bootstrap**: For responsive design and styling.
- **OSRM (Open Source Routing Machine)**: For route generation based on real-world map data.

## Screenshots

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1SUsDCI1OV_sdSL9CY3D27J9a7vax34QJ)

## Roadmap

Future features and improvements:
- Add more pathfinding algorithms (e.g., Greedy BFS, Bidirectional Search).
- Improve performance for larger grids.
- Enhanced map-based visualization features.

## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue or submit a pull request.

To contribute:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-branch-name
   ```
3. **Make your changes**.
4. **Commit your changes**:
   ```bash
   git commit -m 'Add some feature'
   ```
5. **Push to the branch**:
   ```bash
   git push origin feature-branch-name
   ```
6. **Open a pull request**.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries or feedback:

**Name**: Aaditya Kumar Gupta  
**Email**: k.aaditya.g@gmail.com

