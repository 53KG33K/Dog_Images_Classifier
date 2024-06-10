# Pet Image Classifier

This repository contains a program that classifies images of pets using a pre-trained neural network model. The program runs various functions to process the images, classify them, and print the results along with the time taken for execution.

## Overview

The program performs the following tasks:
1. Retrieves command line arguments.
2. Processes the pet images to create labels.
3. Classifies the images using a specified model architecture.
4. Adjusts the classification results to identify if the images are of dogs.
5. Calculates and prints the statistics of the classification results.
6. Measures and prints the total runtime of the program.

## Prerequisites

- Python 3.x
- Required Python modules (imported in the script)

## Running the Program

To run the program, execute the following command in your terminal:

```bash
python main.py --dir [path_to_image_directory] --arch [model_architecture] --dogfile [path_to_dogfile]

