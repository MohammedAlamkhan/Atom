# Interactive Atom Visualization
 [DEMO](https://mohammedalamkhan.github.io/Atom/)
## Description

This project is an interactive, educational web application that visualizes atomic structure and properties. It allows users to explore different elements and their isotopes by adjusting the number of protons, neutrons, and electrons. The application provides a dynamic, scientifically accurate representation of atoms, including their nucleus, electron shells, and energy levels.

## Features

1. **Interactive Atom Builder**: Users can input the number of protons, neutrons, and electrons to visualize different atoms and isotopes.

2. **Dynamic Visualization**: The atom is rendered in real-time, with animated electrons orbiting the nucleus.

3. **Energy Level Display**: Electron shells are color-coded and labeled with their corresponding energy levels (K, L, M, N, etc.).

4. **Nucleus Visualization**: The nucleus shows individual protons and neutrons, with the size scaling based on the total number of nucleons.

5. **Element Information**: For the first 20 elements, the application displays atomic mass, electronegativity, and common uses.

6. **Electron Configuration**: The electron configuration is shown in spectroscopic notation.

7. **Ionic States**: Users can select common ionic states to see how the electron configuration changes.

8. **Stability Indicator**: The application visually indicates whether the current isotope configuration is stable or unstable.

9. **Responsive Design**: The visualization adapts to different screen sizes, making it accessible on both desktop and mobile devices.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Canvas API for drawing and animation

## Setup and Installation

1. Clone the repository or download the source code.
2. Open the `index.html` file in a modern web browser.

No additional installation or setup is required as this is a client-side application.

## How to Use

1. Open the application in a web browser.
2. Use the input fields to set the number of protons, neutrons, and electrons.
3. Select an ionic state from the dropdown menu if desired.
4. Observe the atom visualization update in real-time.
5. Read the additional information provided below the visualization.

## Code Structure

- `index.html`: The main HTML file containing the structure of the web page.
- `styles.css`: Contains all the CSS for styling the application.
- `script.js`: The JavaScript file containing all the logic for the atom visualization and interactivity.

Key JavaScript functions:
- `drawAtom()`: Main function for rendering the atom visualization.
- `drawNucleus()`: Renders the nucleus with protons and neutrons.
- `drawEnergyLevels()`: Draws the electron shells and labels.
- `getElectronConfiguration()`: Calculates the electron configuration.
- `updateAtomInfo()`: Updates the displayed atom information.
- `resizeCanvas()`: Handles responsive resizing of the canvas.

## Customization

The application can be extended to include more elements by updating the `elementInfo` object in the JavaScript file. Additional ionic states can be added by modifying the HTML select options and updating the `updateElectronCount()` function.

## Limitations

- The electron configuration calculation follows the Aufbau principle and may not accurately represent all elements, especially transition metals and heavy elements.
- The visualization is a simplified model and does not represent quantum mechanical effects or electron probability distributions.

## Future Enhancements

Potential areas for future development include:
- Expanding the element database beyond the first 20 elements.
- Adding more complex ionic states.
- Implementing a search function for elements.
- Adding 3D visualization options.
- Incorporating more detailed quantum mechanical models.

## Contributing

Contributions to improve the application are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is open-source and available under the MIT License.

## Contact

For any questions or suggestions regarding this project, please open an issue in the GitHub repository.
