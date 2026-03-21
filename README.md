# Bloch Sphere Simulator

A web-based interactive visualizer for quantum qubit states on the Bloch sphere. This tool demonstrates how quantum states, angles (θ and φ), and gates affect the qubit's representation in 3D space.

## Features

Interactive 3D Visualization**: Drag to rotate the sphere, scroll to zoom, and view the state vector in real-time.
Angle Controls: Adjust polar (θ) and azimuthal (φ) angles with sliders.
Quantum Gates: Apply common gates (X, Y, Z, H, S, T) with animated transitions.
Basis States: Quick presets for standard states like |0⟩, |1⟩, |+⟩, |-⟩, |i⟩, |-i⟩.
Measurement Probabilities**: Real-time display of |0⟩ and |1⟩ probabilities.
Dirac Notation: Automatic generation of the quantum state in Dirac notation.
Responsive Design: Works on desktop and mobile with touch support.

## How to Use

1. Open `index html` in a web browser (or use VSCode's Live Server extension for local hosting).
2. Interact with the canvas:
   - Drag to rotate the view.
   - Scroll to zoom in/out.
3. Use the sliders or preset buttons to set angles and states.
4. Click gate buttons to apply quantum operations with smooth animations.
5. Observe updates in coordinates, probabilities, and Dirac notation.

## Technical Details

- Built with HTML5 Canvas for rendering.
- Pure JavaScript for logic and interactivity.
- CSS Grid for layout and custom styling with IBM Plex fonts.
- No external dependencies; runs entirely in the browser.

## License

This project is open source. feel free to modify and distribute(please).

## Contributing

Suggestions and improvements are welcome. Open an issue or submit a pull request.
