# Final-Project-Software-Prototype.
Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The AR Tracked Image Placement project demonstrates how to leverage augmented reality (AR) technology to track real-world images and dynamically place 3D objects (prefabs) on them. This Unity project utilizes AR Foundation and AR Subsystems to create an interactive AR experience where virtual objects interact with real-world images.

## Features

- **Image Tracking:** The project detects and tracks real-world images using AR Foundation, providing a foundation for interactive AR experiences, In order to use the project you will need to replace the images to be tracked with images of your choice and the prefab to be displayed on the image will need to be replaced to your choice, there are no predownloaded prefabs present in the repository as the file is far too large.

- **Dynamic Object Placement:** 3D objects (prefabs) are placed on tracked images in real-time, creating an augmented reality environment where virtual objects appear to interact with the real world. These objects would then facilitate as clues for the scavenger hunt.

- **Customizable Prefabs:** The project allows you to define multiple prefabs that correspond to different tracked images. Each prefab can be customized to display unique content or interactions.

## Installation

1. Clone the repository: `git clone https://github.com/eseosapku/Final-Project-Software-Prototype`
2. Open the project in Unity (version 2021.3.15f1 or higher).
3. Set up your AR development environment and platform (ARCore or ARKit, depending on your target devices).
4. Import the AR Foundation package and any additional necessary assets.
5. Configure project settings and scenes to fit your project's requirements.

## Usage

1. Launch the project in Unity and build it for your target platform (e.g., Android, iOS).
2. Install the built application on a compatible AR-capable device.
3. Point the device's camera at a tracked image (such as a recognized image target) to see the corresponding 3D object placed on it, this will only work for images that have been saved to be tracked.

## Technologies Used

- Unity
- AR Foundation
- AR Subsystems
- C# Programming Language

## Contributing

Contributions to this project are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-new-feature`.
3. Implement your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to your fork: `git push origin feature-new-feature`.
5. Create a pull request describing your changes.

