# Pathfinding Visualizer

A dynamic web application that visualizes pathfinding algorithms in action. Built with React 18, this interactive tool helps understand how different pathfinding algorithms work by providing real-time visualization of the algorithm's process.

## 🚀 Features

- **Interactive Grid**: Click and drag to create walls and obstacles
- **Real-time Visualization**: Watch algorithms find the shortest path step by step
- **Dijkstra's Algorithm**: Implements the famous weighted pathfinding algorithm
- **Responsive Design**: Clean and intuitive user interface
- **Modern Tech Stack**: Built with React 18 and optimized for performance

## 🛠️ Technologies Used

- **React 18** - Modern React with latest features
- **JavaScript (ES6+)** - Core programming language
- **CSS3** - Styling and animations
- **React Scripts 5.0** - Build and development tools

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

## 🔧 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/GitMasterJatin/Path-Finder-.git
cd Path-Finder-
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📦 Project Structure

```
src/
├── PathfindingVisualizer/    # Main visualizer component
│   ├── PathfindingVisualizer.jsx
│   ├── PathfindingVisualizer.css
│   └── Node/                  # Grid node component
├── algorithms/                # Pathfinding algorithms
│   └── dijkstra.js           # Dijkstra's algorithm implementation
├── App.js                     # Root component
└── index.js                   # Application entry point
```

## 🎯 How to Use

1. The grid represents a 2D space where pathfinding occurs
2. Click on cells to create walls/obstacles
3. Set start and end points for the path
4. Click "Visualize" to watch the algorithm find the shortest path
5. The algorithm explores nodes and highlights the final path

## 🚀 Available Scripts

### `npm start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000)

### `npm test`
Launches the test runner in interactive watch mode

### `npm run build`
Builds the app for production to the `build` folder

## 💡 Key Learnings

- Implementation of pathfinding algorithms
- React component architecture and state management
- Real-time UI updates and animations
- Grid-based data structure manipulation
- Performance optimization for visual rendering

## 🤝 Contributing

This is a personal project, but suggestions and feedback are welcome!

## 📝 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Jatin Sharma** - [GitMasterJatin](https://github.com/GitMasterJatin)

---

⭐ Star this repository if you find it helpful!
