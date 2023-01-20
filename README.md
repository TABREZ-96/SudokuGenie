# Sudoku Solver

This project contains a Python implementation of a Sudoku solver. It uses a backtracking algorithm to solve the puzzle.

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need to have Python 3 installed on your system in order to run the solver. You can download the latest version from the official website: https://www.python.org/downloads/

### Installing

Clone the repository to your local machine.

git clone https://github.com/TABREZ-96/SudokuGenie.git


### Usage

The solver can be used by calling the `solve()` function and passing it a 9x9 grid represented as a 2D array. Empty cells in the grid should be represented as 0.

```python
from sudoku_solver import solve

grid = [[5,3,0,0,7,0,0,0,0],
        [6,0,0,1,9,5,0,0,0],
        [0,9,8,0,0,0,0,6,0],
        [8,0,0,0,6,0,0,0,3],
        [4,0,0,8,0,3,0,0,1],
        [7,0,0,0,2,0,0,0,6],
        [0,6,0,0,0,0,2,8,0],
        [0,0,0,4,1,9,0,0,5],
        [0,0,0,0,8,0,0,7,9]]

solve(grid)
for i in range(len(grid)):
print(grid[i])
```
This will print the solved sudoku grid.

## Built With

* [Python 3](https://www.python.org/) - The programming language used

## Authors

* **[TABREZ]** - *Initial work* - [Github
Profile](https://github.com/TABREZ-96)

## Acknowledgments

Hat tip to anyone whose code was used
Inspiration
etc
Note
This is a basic implementation, there may be edge cases that are not handled by this solver. Also, there may be multiple solutions for a given sudoku puzzle, this solver will return one of the solutions.

## Support 

If you found this project helpful or you learned something from it and want to show your appreciation, you can buy me a coffee. Your support will help me to continue maintaining and updating this project.

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/TABREZx96)
[![LinkedIn](https://image.flaticon.com/icons/svg/1409/1409945.svg)](https://www.linkedin.com/in/tabrez-sayed-b661641b8/)
[![Email](https://image.flaticon.com/icons/svg/565/565580.svg)](mailto:tabrez78546@gmail.com)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details

## Additional Resources
Sudoku Solver - Wikipedia
Backtracking - Wikipedia
Sudoku Guide
Sudoku Solver Python



