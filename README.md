# Map-Based Pathfinding Visualizer

An interactive web-based application for visualizing various pathfinding algorithms on a grid, now enhanced with map-based routing features. This tool allows users to set start, target, and bomb nodes, and visualize how different algorithms explore the grid and map to find the shortest path in real-world environments.

## Features

- **Start & Target Nodes**: Set your starting point and ending point on the grid and directly on map.
- **Pathfinding Algorithms**: Visualize popular pathfinding algorithms like A*, Dijkstra's, and more.
- **Bomb & Weight Nodes**: Add bomb nodes (blockers) or weight nodes (delays) to observe how they affect the pathfinding process.
- **Grid-Based Visualization**: The grid is visualized with clear node representations for walls, visited nodes, shortest-path nodes, and more.
- **Map Integration**: Option to visualize paths directly on a map using OpenStreetMap.

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

1. Set your starting point and destination on the grid.
2. Pick an algorithm from the "Algorithms" dropdown like A*, Dijkstra's, and more.
3. Hit "Visualize!" to see the algorithm in action.
4. In the top right corner, you’ll see the map-based visualizer. Click it to open the map.
5. Once the map is displayed, click "Allow" to grant access to your location if prompted.
6. On the map, you can:
   - **Set the Start point** by clicking on your desired starting location.
   - **Set the End point** by clicking on your target destination.
7. Then click on the "Find Sortest Path" to find the shortest distance between the startpoint and endpoint. You can also see the distance and time taken by the path.

## Usage

- **Start Node**: Click on the grid to set your starting position.
- **Target Node**: Select your destination node on the grid.
- **Bomb Node**: Place a bomb (or obstacle) to make pathfinding more challenging in the grid.
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

1.) Set your starting point and destination on the grid.

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1W3q8UNxKxwnjMgQVZLdI2C6d_v7JgneW)

2.) Pick an algorithm from the "Algorithms" dropdown like A*, Dijkstra's, and more.

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1HfFNujWobR3AYWloeM5DDhrI802JNe0U)

3.) Hit "Visualize!" to see the algorithm in action.

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1tUcKvL6PGC1tKzwnDO0e5NnxeA9SsLRX)

4.) Add bomb nodes (blockers).

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1tpaiFIOUFjk0-LH3cHflx7A7OM1nIIfm)

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1AKe5_1oZUzhK-CU2hM5M246czvGKr_S2)

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1NJZNSf0Ohnlv_AJDCuX78KT4NgvUjLZ1)

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1gkBfGUaZ72kEUBFThbvZz6j1U9enhxJz)

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1wXy2rctbnwLqTThLpUGD3g8UDmLImIg4)

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1QZNJE1RxDUtQvt-hJLDt7KUGSHOrAKRa)

5.) Add weight nodes (delays).

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1y7FIO_shoKyBss_or5jeM4u00k2MuKZ-)

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?ecport=view&id=1nXgMCDpYLyMFFrdv12n-WnWPjmgl1R1Q)

6.) In the top right corner, you’ll see the map-based visualizer. Click it to open the map.

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1xIpIOwUKFAezT8lRg-hBNLe8OaunAauS)

7.) Once the map is displayed, click "Allow" to grant access to your location if prompted.

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1SUsDCI1OV_sdSL9CY3D27J9a7vax34QJ)

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1OBZs1acLVNiCXZP3M_hdj2kYP0Jkdxhh)

8.) On the map, you can:
   - **Set the Start point** by clicking on your desired starting location.

     ![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1_RLWCuCDuhvYJ99QDWbF4CfdOYmwUnOU)

     
   - **Set the End point** by clicking on your target destination.

     ![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1lemMTOixKq7FkiucLm5OuBF17aJvX3tn)

9.) Then click on the "Find Sortest Path" to find the shortest distance between the startpoint and endpoint. You can also see the distance and time taken by the path.

![Pathfinding Visualizer Screenshot](https://drive.google.com/uc?export=view&id=1mCWS0mi12TlZyOFGsmWgYHsq2EBbwm1b)



## Roadmap

Future features and improvements:
- Add more pathfinding algorithms (e.g., Greedy BFS and more).
- Improve performance for larger grids.
- Enhanced map-based visualization features.


## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/AadityaKGupta/Map-Based-Pathfinding-Visualizer/blob/master/LICENSE) file for details.


## Contact

For any inquiries or feedback, please reach out to:

- **Name**: Aaditya Kumar Gupta
- **Email**: k.aaditya.g@gmail.com
- **GitHub**: [AadityaKGupta](https://github.com/AadityaKGupta)
