# Maze-Generation
A Swift program that uses Recursive-Backtracking to generate a maze

Based off of:
- [Programming Mazes](https://www.youtube.com/watch?v=Y37-gB83HKE)
- [OneLoneCoder Maze C++ Source Code](https://github.com/OneLoneCoder/videos/blob/master/OneLoneCoder_Mazes.cpp)

![Console Screenshot](https://github.com/patrickbiel01/Maze-Generation/blob/master/console-maze-screenshot.png)
![Game Screenshot](https://github.com/patrickbiel01/Maze-Generation/blob/master/game-maze-screenshot.png)

## Notes
* Odd-numbered width and height for best-results
* Data is represented in a 2-D Array (columns x rows)
* Each Entry represents one tile and is classified as a wall or floor
* A graph is also generated with each vertex representing a tile
* The edges in the graph represent passages and are uniform in weight

## Use
```swift
//Width - Number of Columns
//Height - Number of Rows
let maze = Maze(width: 10, height: 10)

//Retrieve graph
let graph = maze.graph

//Output maze to console
maze.outputMaze()
```

## Clone Repository
```bash
git clone https://github.com/patrickbiel01/Maze-Generation.git
```

## Issues
If you have any bugs or feature requests, please submit an [issue](https://github.com/patrickbiel01/Maze-Generation/issues).

## Contribution
If you wish to contribute, fork my project and create a [pull request](https://github.com/patrickbiel01/Maze-Generation/pulls)

## License
**Maze Generation** is released under the MIT license. See [LICENSE](https://github.com/patrickbiel01/Maze-Generation/blob/master/LICENSE) for details.
