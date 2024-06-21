# Dijkstra Algorithm Visualizer

This project is a visual representation of Dijkstra's Algorithm for finding the shortest path between two nodes in a grid. Users can set start and end nodes, add walls, and visualize the algorithm in action.

## Features

- **Set Start Node**: Allows the user to set the starting point for the algorithm.
- **Set End Node**: Allows the user to set the endpoint for the algorithm.
- **Add Walls**: Users can add walls to the grid, making the algorithm find an alternative path.
- **Visualize Dijkstra's Algorithm**: Starts the visualization of Dijkstra's Algorithm from the start node to the end node.

## Structure

- `index.html`: Contains the HTML structure of the page.
- `styles2.css`: Contains the CSS for styling the page.
- `script2.js`: Contains the JavaScript logic for the grid and Dijkstra's Algorithm visualization.

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```sh
    cd dijkstra-visualizer
    ```

3. Open `index.html` in your preferred web browser.

## Usage

1. Open the project in your web browser.
2. Click "Set Start Node" and then click on a node in the grid to set the start node.
3. Click "Set End Node" and then click on a node in the grid to set the end node.
4. Click "Add Walls" and then click on nodes in the grid to add walls.
5. Click "Visualize Dijkstra's Algorithm" to see the algorithm in action.

## Code Overview

### HTML

The `index.html` file sets up the structure of the page with a header, a control panel for the buttons, a main section for the grid, and a footer.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dijkstra Algorithm Visualizer</title>
    <link rel="stylesheet" href="styles2.css">
</head>
<body>
    <header>
        <h1>Dijkstra's Algorithm Visualizer</h1>
    </header>
    <div class="controls">
        <button id="startButton">Set Start Node</button>
        <button id="endButton">Set End Node</button>
        <button id="wallButton">Add Walls</button>
        <button id="visualizeButton">Visualize Dijkstra's Algorithm</button>
    </div>
    <main>
        <div id="grid"></div>
    </main>
    <footer>
        <p>© 2024 Dijkstra Algorithm Visualizer. All rights reserved.</p>
    </footer>
    <script src="script2.js"></script>
</body>
</html>
