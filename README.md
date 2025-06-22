# Pathfinder - Visualize Pathfinding Algorithms

Pathfinder is an interactive React web application that helps visualize popular pathfinding algorithms including BFS, DFS, Dijkstra, and A* Search. This tool allows users to create walls and obstacles, set start and finish nodes, generate mazes, and see how different algorithms explore the grid to find the shortest path.

## Demo

Check out the live deployed version here:  
[https://pathfinder-1.netlify.app/](https://pathfinder-1.netlify.app/)

## Features

•⁠  ⁠Visualize *BFS, **DFS, **Dijkstra, and **A\** search algorithms in action.
•⁠  ⁠Create and remove *walls/obstacles* dynamically on the grid.
•⁠  ⁠Set *start* and *finish* nodes anywhere on the grid.
•⁠  ⁠Generate random *mazes* to challenge the pathfinding.
•⁠  ⁠View the algorithm's progress step-by-step with animations.
•⁠  ⁠Display algorithm execution times for performance comparison.

## Getting Started

These instructions will help you set up and run the project locally for development and testing purposes.

### Prerequisites

Make sure you have the following installed:

•⁠  ⁠[Node.js and npm](https://nodejs.org/en/download/) (Node Package Manager)

### Installation

1.⁠ ⁠Clone the repository:
   ```bash
   git clone https://github.com/AnuBaswaraj/Pathfinder.git
   ```
2. Navigate into the project directory:
  ```⁠bash
   cd Pathfinder
```
3.⁠ ⁠Install dependencies:
```bash
  npm install
  ``` 
## Running Locally

Start the development server by running:
```⁠bash
npm start
```
⁠ Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.
The app will automatically reload if you make edits. You may also see any lint errors in the console.

## Building for Production
To create an optimized production build, run:
```⁠bash
npm run build
```
This bundles React in production mode and optimizes the build for the best performance. The build output will be in the build folder, ready to be deployed.

## Deployment

You can deploy the build folder contents to any static hosting service. The current live demo is hosted on Netlify:

 [https://pathfinder-1.netlify.app/]
 
Note: If you deploy yourself, ensure the homepage field is removed or set correctly in package.json to avoid broken asset links on Netlify.

## How to Use

1.⁠ ⁠*Select Algorithm: Choose BFS, DFS, Dijkstra, or A from the dropdown.

2.⁠ ⁠*Set Nodes*:
   - Click *Source*, then click a grid cell to set the start node.
   - Click *Destination*, then click a grid cell to set the finish node.

3.⁠ ⁠*Create Walls*: Select *Wall* and click cells to add or remove obstacles.

4.⁠ ⁠*Generate Maze*: Automatically create a random maze layout.

5.⁠ ⁠*Find Path*: Click *Find Path* to see the selected algorithm in action.

6.⁠ ⁠*Clear Path/Board*: Use these buttons to reset the visualization or the entire grid.

7.⁠ ⁠*View Execution Times*: Algorithm run times are displayed below the controls.

## Technologies Used

•⁠  ⁠React  
•⁠  ⁠JavaScript (ES6+)  
•⁠  ⁠CSS3  
•⁠  ⁠HTML5
## Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check the [issues page](../../issues) or submit a pull request.

---
## Learn More

•⁠  ⁠[React documentation](https://reactjs.org/)
•⁠  ⁠[Create React App documentation](https://create-react-app.dev/)
•⁠  ⁠[Pathfinding algorithm concepts (BFS, DFS, Dijkstra, A*)](https://en.wikipedia.org/wiki/Pathfinding)

