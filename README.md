# Lane Detection Project

## Description
The Lane Detection Project aims to develop a robust lane detection system using computer vision techniques. This system is crucial for autonomous vehicles to accurately identify and track lane markings on the road, ensuring safe and reliable navigation.

## Overview
Lane detection is a fundamental task in autonomous driving systems, allowing vehicles to stay within their lanes and navigate effectively. This project explores various computer vision algorithms and techniques to achieve accurate lane detection under different environmental conditions.

## Steps Followed
1. **Exploration of Color Spaces:**
   - Explored five color spaces: RGB, LAB, YUV, HSV, and HSL.
   - Analyzed the effectiveness of each color space in highlighting lane markings.

2. **Color Space Selection:**
   - Selected HSL (Hue, Saturation, Lightness) color space for its superior performance in detecting lane markings.

3. **Canny Edge Detection:**
   - Applied Canny edge detection to identify edges in the image.
   - Utilized Gaussian smoothing to reduce noise and improve edge detection accuracy.

4. **Hough Transform:**
   - Implemented Hough Transform to detect lines representing lane boundaries.
   - Used parameters tuning to optimize lane detection performance.

5. **Lane Line Averaging:**
   - Averaged and extrapolated the detected lane lines to enhance accuracy and stability.
   - Implemented techniques to handle challenging scenarios such as curves and varying lighting conditions.

## Technologies Used
- **Programming Language:** Python
- **Libraries/Frameworks:**
  - OpenCV: Used for image processing tasks such as color space transformations, edge detection, and Hough Transform.
  - NumPy: Used for numerical computations and array operations.
  - Matplotlib: Used for data visualization and displaying images and plots.
- **Development Environment:**
  - Jupyter Notebook: Used for experimentation, code execution, and documentation.
- **Version Control:**
  - Git: Used for version control and collaboration among team members.

## Getting Started
To get started with the Lane Detection project, follow these steps:
1. Clone the repository: `git clone https://github.com/Jasmitha02/Lane-Detection.git`
2. Install the necessary dependencies.
3. Explore the code and documentation provided in the repository.
4. Experiment with different parameters and algorithms to improve lane detection performance.
5. Share your feedback and contribute to the project to enhance its capabilities.


