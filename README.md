# 3D CSS Cube

A simple 3D rotating cube built using HTML and CSS. Each face of the cube can be viewed by selecting the corresponding option, demonstrating the use of CSS transforms and transitions.

## Project Overview

This project showcases a 3D cube that can be rotated to display different faces. The rotation is controlled by radio buttons labeled "Front," "Left," "Right," "Top," "Bottom," and "Back." When a label is clicked, the cube rotates smoothly to display the corresponding face.

## Features

- **3D Cube:** A six-faced cube rendered using CSS.
- **Smooth Transitions:** CSS transitions ensure the cube rotates smoothly between faces.
- **Interactive Buttons:** Radio buttons are styled as labels to allow users to select and view different faces of the cube.

## Tech Stack

- **HTML5**
- **CSS3**

## How It Works

1. **Cube Structure:** The cube is created using six `<div>` elements, each representing a face of the cube.
2. **CSS Transforms:** The cube's faces are positioned using `translateZ` and rotated with `rotateX` and `rotateY`.
3. **Perspective:** The `perspective` property on the container gives the 3D effect.
4. **Radio Buttons:** Hidden radio buttons are used to trigger the rotation of the cube, with each button corresponding to a different face.

## Demo

[Live Demo](#) - *Add your demo link here*

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/3d-css-cube.git
