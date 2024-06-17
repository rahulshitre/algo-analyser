# Algorithms-Visualizer
This is a project made for the Data Structures and Algorithms course in International University with main the purpose of visualizing some algorithms. The project is finished with our initial intentions completed.

## Pre-requisites
This project is made with:
+ Pure HTML and CSS
+ TypeScript

## How to run
Install TypeScript:

Make sure you have Node.js installed.
Open your command line interface (CLI) and run the following command to install TypeScript globally:
bash
Copy code
npm install -g typescript
Compile TypeScript:

In your project's root directory, open your CLI and run the TypeScript compiler in watch mode:
bash
Copy code
tsc --watch
This command will start the TypeScript compiler in watch mode, which means it will automatically compile your TypeScript files into JavaScript whenever it detects any changes. The output you provided (File change detected. Starting incremental compilation... Found 0 errors. Watching for file changes.) indicates that the compiler is running and watching for changes successfully.
Run the Project:

Once TypeScript is compiling your code without errors, you need to serve your HTML files to view them in a browser. You can use a simple HTTP server for this. If you don't already have one, you can install a lightweight server like http-server using npm:
bash
Copy code
npm install -g http-server
After installation, navigate to your project's root directory in the CLI and start the server:
bash
Copy code
http-server
By default, http-server will start serving your files at http://localhost:8080. You can open this URL in your web browser to see your project in action.
Example Steps in VS Code
Open Integrated Terminal:

Open your project folder in Visual Studio Code (VS Code).
Open the integrated terminal by selecting Terminal > New Terminal from the top menu.
Run TypeScript Compiler:

In the integrated terminal, run:
bash
Copy code
tsc --watch
Leave this terminal open as it watches and compiles your TypeScript files.
Start HTTP Server:

Open a new terminal in VS Code.
Navigate to your project directory if not already there and start the HTTP server:
bash
Copy code
http-server
Open your web browser and go to http://localhost:8080.

If you can't run the project, you can visit here: <https://tpspace.github.io/Algorithms-Visualizer/> to see the demo.

## Features
### Sorting Algorithms
+ Visualize the sorting process of algorithms via *Books* in a Library. The goal is to sort all the books alphabetically.
+ User can choose the Algorithm desired to visualize, the speed of the visualization, the number of books and the worst case.
+ **Algorithms supported**: Bubble Sort, Selection Sort, Insertion Sort, Quick Sort
### Path Finding Algorithms
+ Visualize the path finding process of algorithms via drawable *Maze*.
+ User is presented with a blank canvas in which the user can draw the maze, set the start and end point and visualize the path finding process.
+ User can choose the Algorithm desired to visualize, the speed of the visualization.
+ **Algorithms supported**: Depth First Search, Breadth First Search
