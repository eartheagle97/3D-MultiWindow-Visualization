# 3D MultiWindow Visualization using Three.js

This project showcases a 3D visualization using the three.js library, featuring dynamic adjustments of cubes based on the layout of multiple windows. The scene provides an interactive and visually engaging experience.

## Overview
The main goal of this project is to demonstrate the capability of three.js to create a dynamic 3D scene that adapts to the layout of multiple windows or tabs. The cubes within the scene represent individual windows, and their positions are updated in real-time as the layout changes.

## Features

- **Dynamic Cube Layout**: Cubes are dynamically positioned based on the layout of windows, providing a responsive and visually interesting 3D scene.

- **Multiple Windows Support**: Open the application in multiple windows or tabs to observe how each cube adjusts its position according to the window's layout.

- **LocalStorage Interaction**: The project utilizes the browser's local storage to persist window data, ensuring a consistent experience across different instances.


## Getting Started
Clone the repository and open `index.html` in your browser to start exploring the 3D scene.

```
git clone https://github.com/eartheagle97/3D-MultiWindow-Visualization
```

## Usage
- **Explore the 3D Scene**: Move and resize windows to observe the dynamic adjustments of cubes within the 3D scene.

- **Open Multiple Windows**: Open the application in multiple windows or tabs to see how each window contributes to the overall 3D visualization.

- **Customize the Experience**: Experiment with modifying the code in main.js and WindowManager.js to customize the behavior and appearance of the 3D scene.

- **Share Your Experience**: Share your experience or any interesting modifications with the community by creating a pull request or starting a discussion.

## Dependencies
- `three.js`: A JavaScript library for creating 3D graphics.

## Structure and Components
- `index.html`: The main HTML file that includes the three.js library and the main.js script.
- `WindowManager.js`: A module handling the management of multiple windows, including local storage interactions.
- `main.js`: The JavaScript file containing the main logic for setting up the 3D scene, managing windows, and rendering cubes.
- `three.r124.min.js`: Minified version of the Three.js library used for 3D graphics rendering.

## Detailed Functionality
- `WindowManager.js` handles the lifecycle of multiple browser windows, including creation, synchronization, and removal. It uses localStorage to maintain state across windows.
- `main.js` initializes the 3D scene using Three.js, manages the window's resize events, and updates the scene based on window interactions.

## Contributing
1. Fork the project.

2. Create your feature branch:
```
git checkout -b feature/new-feature
```

3. Commit your changes:
```
git commit -am 'Add a new feature'
```

4. Push to the branch:
```
git push origin feature/new-feature
```

5. Submit a pull request.

## License
This project is open-sourced under the MIT License.

## Acknowledgments
- `three.js` - The 3D graphics library used in this project.
- `WindowManager.js` - Special thanks for managing multiple windows and their shapes.

## Contact
For inquiries or issues, please contact [patelkairav97@gmail.com].
