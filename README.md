# Trading Card Grading System: Centering Assessment

This project implements a **Centering Assessment** model for evaluating the centering quality of trading cards using computer vision techniques. The goal is to analyze the centering of trading cards to assist in automated grading. The core of the model evaluates how well the inner image is centered within its bounding box, providing insights into the card's alignment and overall aesthetic.

## Overview

The centering assessment model calculates the centering ratio of the inner and outer bounding boxes of a trading card. The centering ratio is used as one of the metrics to assess the visual quality of the card. This is particularly important for trading card grading, where centering is a key factor in determining the card's quality and value.

The notebook provides the following key functionalities:
1. **Centering Ratio Calculation**: Measures how centered the inner part of the card is within the outer border.
2. **Visualization**: Displays the card images along with center alignment indicators for both the inner and outer bounding boxes.
3. **Automated Grading Assistance**: Helps assess whether the centering is within an acceptable range (e.g., PSA 10 grading) based on predefined thresholds.

## Features
- **Centering Ratio Calculation**: Calculates how well the inner image is centered inside the card’s outer bounding box.
- **Error Handling**: Gracefully handles edge cases like division by zero by substituting small values.
- **Visualization**: Visualizes the centers and bounding boxes for a better understanding of card alignment.
- **Grade Suggestions**: Suggests PSA grade based on centering analysis (e.g., PSA 10 if the centering is perfect within a set ratio range).

## Requirements

Before running the project, you need to have the following libraries installed:

- Python 3.x
- **Libraries**:
  - `numpy`
  - `matplotlib`
  - `opencv`
  - `PIL`
  - `tensorflow` 
  - `pandas`
  - `scipy`



