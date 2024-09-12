# SciBlend - Compositor v.1.0.0

Compositor is an advanced Blender addon designed for 4.2+ versions, providing powerful cinematography composition tools for scientific visualization and 3D artists. While primarily focused on scientific applications, it's versatile enough for various artistic projects. This addon is optimized to work seamlessly with other SciBlend addons, creating a comprehensive suite for scientific 3D visualization and animation.

## Table of Contents

1. [Requirements](#requirements)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Advanced Features](#advanced-features)
6. [Troubleshooting](#troubleshooting)
7. [Contributing](#contributing)
8. [License](#license)

## Requirements

Before installing Blender and the add-on, ensure that you meet the following requirements:

1. **Operating System**: 
    - Any OS with Blender 4.2 or higher installed
  
2. **Blender**:
    - Blender 4.2 or higher

3. **Python**:
    - Python 3.11 (bundled with Blender 4.2)

## Features

- **Camera Staging**: Set up and manage complex multi-camera scenes with ease, perfect for scientific demonstrations and presentations.
- **Camera Management**: Add, remove, and manage multiple cameras within your scene.
- **Cinema Format Presets**: Quickly set up standard cinema resolutions (2K, 4K, 8K, etc.).
- **Print Resolution Settings**: Configure resolutions for print formats (A4, A3, etc.) for publication-ready outputs.
- **Frame Rate Control**: Easily adjust and sync frame rates with cinema formats.
- **Resolution Linking**: Maintain aspect ratios when adjusting resolutions.
- **Orientation Control**: Switch between horizontal and vertical orientations.
- **DPI Settings**: Adjust DPI for print-quality renders, crucial for scientific publications.
- **Custom Resolution Input**: Set precise custom resolutions for specialized scientific visualization projects.
- **Integration with SciBlend Suite**: Designed to work seamlessly with other SciBlend addons for comprehensive scientific visualization workflows.

## Installation



### 3. Install the Add-on

1. **Package the Script**:
    - Place the provided script files into a folder named `Compositor`.

2. **Install the Add-on in Blender**:
    - Open Blender and go to `Edit > Preferences > Add-ons`.
    - Click on `Install...` and select the `Compositor` folder.
    - Enable the add-on by checking the box next to `Compositor`.

3. **Using the Add-on**:
    - Access the add-on from the `View3D` panel under the `Compositor` tab.
    - Configure your shapes and add them to your composition.

## Usage

After installation, you can access SciBlend-Compositor features through the "Compositor" panel in the 3D Viewport's sidebar (press N to toggle).

### Camera Staging
- Use the Camera Staging tools to set up complex multi-camera scenes.
- Define camera movements, transitions, and timing for scientific demonstrations or presentations.
- Automate camera switches based on timeline events or specific frames.

Example of basic Camera Staging usage:
1. Add multiple cameras to your scene using the "Add Camera" button in the Compositor panel.
2. Select a camera from the list and set its active range using the "Start Frame" and "End Frame" fields.
3. Repeat step 2 for each camera, ensuring that their frame ranges don't overlap.
4. Use the "Update Timeline" button to automatically create markers on the timeline for each camera switch.
5. Play the animation to see automatic camera switches based on the defined ranges.
6. Fine-tune camera positions and properties for each stage of your presentation.

This basic setup allows you to create a multi-camera presentation where each camera is active for a specific part of your timeline, ideal for showcasing different aspects of your scientific visualization or guiding viewers through a complex 3D scene.
### Camera Management
- Use the camera list to add, remove, and select cameras.
- Set frame ranges for each camera to control their active periods.

### Resolution Settings
1. Choose a cinema format from the dropdown or set a custom resolution.
2. Adjust the orientation if needed.
3. For print formats, select the desired size and set the DPI.

### Frame Rate Control
- Set the frame rate directly or let it sync with the chosen cinema format.

### Resolution Linking
- Toggle the "Link Resolution" option to maintain aspect ratio when adjusting either width or height.

## Advanced Features

- **Custom Aspect Ratios**: Create and save custom aspect ratios for unique scientific visualization requirements.
- **Camera Switching Automation**: Set up automatic camera switches based on frame ranges or specific events in your scientific animation.
- **Integration with Other SciBlend Addons**: Seamlessly work with other SciBlend tools for a complete scientific visualization pipeline.
- **Real-time Camera Adjustment**: When using the "Lock Camera to View" mode, you can move the camera in real-time even while the animation is playing. This feature allows for precise composition adjustments between camera switches, enhancing the fluidity and accuracy of your multi-camera setups.

## Troubleshooting

- If settings are not applying, ensure the addon is enabled and you're in the correct workspace.
- For performance issues, try lowering the resolution or disabling real-time updates in heavy scenes.

## Contributing

Contributions to the Compositor add-on are welcome! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear, descriptive messages.
4. Push your branch and submit a pull request.

Please ensure your code adheres to the existing style and includes appropriate tests and documentation.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.