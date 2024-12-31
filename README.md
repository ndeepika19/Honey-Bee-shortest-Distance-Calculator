# Honey-Bee-shortest-Distance-Calculator


This project demonstrates a graphical tool using Python's `Tkinter` module for visualizing a spiral matrix and calculating the shortest distance between two nodes within the spiral. Inspired by the movement of honey bees in hexagonal grids, it provides an intuitive way to understand distance calculation in spirals.

## Features

1. **Spiral Matrix Generation**: Creates a visually appealing spiral matrix of any given size.
2. **Shortest Distance Calculation**: Calculates the shortest distance between two nodes in the spiral.
3. **Interactive UI**: User-friendly interface built with `Tkinter`.

---

## Installation

### Prerequisites
Ensure Python 3.x is installed on your system. You can download it from [python.org](https://www.python.org/).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/username/honeybee-shortest-distance.git
   cd honeybee-shortest-distance
   ```
2. Install the required modules (if not already installed):
   ```bash
   pip install tkinter
   ```

---

## Usage

1. Run the script:
   ```bash
   python honey_bee_distance.py
   ```

2. Enter the desired size for the spiral matrix.
3. Input two node values for which you want to calculate the shortest distance.
4. Use the buttons to either display the spiral matrix or calculate the shortest distance.

---

## Code Highlights

### Spiral Matrix Generation
The `print_spiral` function generates an `n x n` matrix in a spiral pattern. It uses a center-outward filling mechanism.

### Shortest Distance Calculation
The `shortest_distance` function calculates the Manhattan distance between two nodes in the spiral, simulating hexagonal grid movements inspired by honey bee navigation.

### GUI
The user interface is built using `Tkinter`, providing fields for input, buttons for actions, and dynamic displays for results and matrices.

---

## File Structure
```
.
├── honey_bee_distance.py  # Main script for the project
└── README.md              # Project documentation
```

---

## Example

### Input
- Spiral Matrix Size: `5`
- First Number: `3`
- Last Number: `14`

### Output
- Spiral Matrix: A colorful visualization of the matrix.
- Shortest Distance: `5`

---

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with any enhancements or bug fixes.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Author
Deepika

Feel free to explore, modify, and share this project!
