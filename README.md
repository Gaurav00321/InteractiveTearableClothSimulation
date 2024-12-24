# 3D Cloth Simulation

A dynamic 3D cloth simulation built using HTML5 Canvas and JavaScript, featuring tearable interactions and realistic cloth physics.

## Features

- **Realistic Cloth Physics:** Simulates a grid of interconnected points that behave like a cloth.
- **Gravity-Less Interaction Mode:** Gravity can be minimized for smoother interactions.
- **Tearable Cloth:** The cloth can tear based on mouse movements.
- **Cursor Interaction:** The cloth reacts dynamically to mouse hover and movement.
- **Customizable Parameters:** Adjust grid size, spacing, damping, and more.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- No external libraries are required.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/3d-cloth-simulation.git

2. Navigate to the project directory:
   ```bash
   cd 3d-cloth-simulation

3. Open index.html in your browser to run the simulation.

## Usage

### Controls
- Mouse Hover: The cloth reacts to the cursor by repelling points.
- Mouse Click (Drag): Tearing occurs along the cloth at the cursor position.
- Arrow Keys: Adjust depth simulation:

  - Arrow Up: Increase depth.
  - Arrow Down: Decrease depth.

### Customization
Modify these parameters in the script for different effects:

- rows and cols: Adjust the grid size of the cloth.
- spacing: Change the distance between points.
- damping: Control the velocity reduction for smoother movement.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with improvements.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Inspired by classic cloth physics simulations. Built with a focus on interactive and visual physics in the browser.
