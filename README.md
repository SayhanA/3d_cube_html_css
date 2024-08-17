3D CSS Cube
A simple 3D rotating cube built using HTML and CSS. Each face of the cube can be viewed by selecting the corresponding option, demonstrating the use of CSS transforms and transitions.

Project Overview
This project showcases a 3D cube that can be rotated to display different faces. The rotation is controlled by radio buttons labeled "Front," "Left," "Right," "Top," "Bottom," and "Back." When a label is clicked, the cube rotates smoothly to display the corresponding face.

Features
3D Cube: A six-faced cube rendered using CSS.
Smooth Transitions: CSS transitions ensure the cube rotates smoothly between faces.
Interactive Buttons: Radio buttons are styled as labels to allow users to select and view different faces of the cube.
Tech Stack
HTML5
CSS3
How It Works
Cube Structure: The cube is created using six <div> elements, each representing a face of the cube.
CSS Transforms: The cube's faces are positioned using translateZ and rotated with rotateX and rotateY.
Perspective: The perspective property on the container gives the 3D effect.
Radio Buttons: Hidden radio buttons are used to trigger the rotation of the cube, with each button corresponding to a different face.
Demo
Live Demo - Add your demo link here

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/3d-css-cube.git
Navigate to the project directory:
bash
Copy code
cd 3d-css-cube
Open index.html in your browser to view the 3D cube.
Usage
Click on any of the buttons to rotate the cube to the desired face.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Inspired by various 3D CSS tutorials available online.
