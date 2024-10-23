# Pathfinding Visualizer

An interactive web-based application for visualizing various pathfinding algorithms on a grid, integrated with map-based routing features. This tool allows users to set start, target, and bomb nodes, and visualize how different algorithms explore the grid to find the shortest path.

## Features
- **Start & Target Nodes:** Set your starting point and destination on the grid.
- **Pathfinding Algorithms:** Visualize popular pathfinding algorithms like A*, Dijkstra's, and more.
- **Bomb & Weight Nodes:** Add bomb nodes (blockers) or weight nodes (delays) to observe how they affect the pathfinding process.
- **Grid-Based Visualization:** The grid is visualized with clear node representations for walls, visited nodes, shortest-path nodes, and more.
- **Map Integration:** Option to visualize paths directly on a map (OpenStreetMap integration).
- **Search Location:** Find cities using the search bar and integrate that with your pathfinding grid.

## Getting Started

### Prerequisites
To run this project locally, you will need:
- A modern web browser (Chrome, Firefox, Edge, etc.)
- Internet connection for fetching external libraries (Leaflet.js, Bootstrap, etc.)

### Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Pathfinding-Visualizer.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd Pathfinding-Visualizer
   ```
3. **Open the `index.html` File in a Browser:**
   You can simply open the `index.html` file in your browser to run the application.

   Alternatively, you can serve the project locally using an HTTP server:
   ```bash
   # Example using Python's built-in HTTP server
   python -m http.server
   ```

4. **Start Visualizing:**
   - Select a start node and a target node.
   - Pick an algorithm from the "Algorithms" dropdown.
   - Hit "Visualize!" to see the algorithm in action.

### Usage
- **Start Node:** Click on the grid to set your starting position.
- **Target Node:** Select your destination node.
- **Bomb Node:** Place a bomb (or obstacle) to make pathfinding more challenging.
- **Weight Node:** Place weighted nodes to simulate additional traversal cost.
- **Clear Board:** Reset the grid for a fresh start.
- **Clear Path:** Retain nodes but reset the path visualization.
- **Use in Map:** Use the integration with OpenStreetMap to visualize your pathfinding in a real-world context.

## Technologies Used
- **HTML5 / CSS3 / JavaScript:** Core front-end technologies.
- **Leaflet.js:** For map visualization and integration.
- **Bootstrap:** For responsive design and styling.
- **OSRM (Open Source Routing Machine):** For route generation based on real-world map data.

## Screenshots

![Pathfinding Visualizer Interface](path/to/your/screenshot.png)

## Roadmap
Future features and improvements:
- Add more pathfinding algorithms (e.g., Greedy BFS, Bidirectional Search).
- Improve performance for larger grids.
- Enhanced map-based visualization features.

## Contributing
Contributions are welcome! If you find a bug or have a feature request, please open an issue or submit a pull request.

To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes.
4. Commit your changes: `git commit -m 'Add some feature'`.
5. Push to the branch: `git push origin feature-branch-name`.
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or feedback:
- **Name:** Aaditya Kumar Gupta
- **Email:** [your-email@example.com](mailto:your-email@example.com)

---

Feel free to modify the content to better suit your specific project and branding!
