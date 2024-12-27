# LondonEye

This project is a 3D simulation of the **London Eye** (also known as the Millennium Wheel) built using **Babylon.js**. It creates an interactive 3D scene that mimics the rotating movement of the London Eye with realistic textures and animations. The simulation includes the London Eye’s central hub, a rotating ring, capsules attached to the ring, cables connecting the capsules to the center, and a ground texture representing the surrounding area.

## Features
- **Realistic 3D modeling**: The London Eye, its capsules, and columns are modeled in Babylon.js.
- **Interactive camera**: Use your mouse to control the view of the scene and explore the simulation.
- **Rotating animation**: The London Eye rotates smoothly, mimicking its movement in real life.
- **Texture mapping**: Custom textures are applied to the London Eye’s components, such as the capsules and ground, to give it a more realistic appearance.

## How to View

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/londoneye.git
    ```
2. **Open the `index.html` file** in your web browser to view the simulation.

## Technologies Used
- **Babylon.js**: A powerful JavaScript framework for building 3D games and simulations.
- **HTML5**: For structuring the simulation and including external resources.
- **JavaScript**: For animating the simulation and managing interactions.

## How It Works
The code sets up a Babylon.js scene and creates a 3D model of the London Eye. It starts by defining the camera and lights, then proceeds to create the main components of the wheel, including the central hub, rotating ring, capsules, and cables. Each component is animated to simulate the rotation of the London Eye over time.

### Key Components:
- **London Eye Structure**: The main object that houses the rotating components.
- **Capsules**: 22 capsules placed around the rotating ring, attached to the center via cables.
- **Columns**: The three support columns that hold up the London Eye.
- **Ground**: The ground texture, which is a water surface, forms the base of the scene.

### Animation:
The London Eye rotates around its center, and the rotation is animated using Babylon.js’s animation system. The animation loops continuously, creating the effect of the London Eye rotating in real-time.

## Screenshots

<p align="center">
  <img src="/Images/demo.gif" alt="London Eye Demo"/>
</p>




## Acknowledgements

- **Babylon.js**: [https://www.babylonjs.com/](https://www.babylonjs.com/) for providing the tools to create 3D graphics and animations.
- **Images**: Textures are sourced from local images, such as the water texture and sky texture.

