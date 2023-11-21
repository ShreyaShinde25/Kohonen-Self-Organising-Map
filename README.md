# Kohonen-Self-Organising-Map

## Overview
This repository presents a Kohonen Self-Organizing Map (SOM) implementation for color clustering on a 100 by 100 grid of neurons. The SOM is trained on a dataset of 24 colors, including shades of red, green, blue, yellow, teal, and pink. The training process incorporates a time-varying learning rate and a topological neighborhood function.

## Functionality
* **Color Dataset:** The dataset consists of 24 colors represented in RGB format, normalized between 0 and 1.
* **Training Parameters:** The SOM is trained over 1000 epochs with a time-varying learning rate and varying topological neighborhood sizes (sigma).
* **Visualization:** Figures of the SOM are generated for epochs 20, 40, 100, and 1000, illustrating how the output changes with different sigma values (1, 10, 30, 50, 70) and the number of epochs.

## Implementation Details
* **Distance Calculation:** Euclidean distance is used to find the distance between the weight vectors and input colors.
* **Neighborhood Function:** The topological neighborhood function is employed to define the influence of neighboring nodes during weight updates.
* **Learning Rate:** A time-varying learning rate is implemented to control the rate of weight adjustments during training.
