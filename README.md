# visualize-sorting-mechanism (sorting visualizer)

A web application that visualizes various sorting algorithms, allowing users to see how different algorithms sort arrays of data in real-time.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Visualizes the following sorting algorithms:
1) Bubble sort
2) Selection sort
3) Insertion sort
4) Merge sort
5) Quick sort
6) Heap sort

Features:
1) Colored representation of step being executed.
  1.1) Blue:default
  1.2) Yellow: Being compared
  1.3) Red: Identified as in incorrect position and to be moved
  1.4) Green: In correct position
2) 3 Controls for visualizations
  2.1) Speed of visualization (5 speed levels)
  2.2) Data size ()
  2.3) Generation of new data (Randomly generate new data).
4) Time and Space complexity of algorithm being visualized.

## Technologies Used

- HTML5
- CSS3 (SCSS)
- JavaScript

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/sorting-visualizer.git
    ```

2. Navigate to the project directory:
    ```bash
    cd sorting-visualizer
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Compile SCSS to CSS:
    ```bash
    npm run sass
    ```

## Usage

1. Open the `index.html` file in your web browser:
    ```bash
    open index.html
    ```

2. Adjust the size and speed of the array using the sliders.

3. Click "Generate New Array" to create a new array with the specified size.

4. Select a sorting algorithm by clicking one of the algorithm buttons.

5. Watch the visualization of the sorting algorithm in action!

