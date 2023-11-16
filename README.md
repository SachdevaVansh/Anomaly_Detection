# Anomaly Detection in Real-Time Data Streams

## Overview

This project implements a real-time anomaly detection system for data streams. The system combines multiple anomaly detection algorithms, including Isolation Forest, Seasonal Hybrid ESD (Extreme Studentized Deviate), Autoencoders, and LSTM (Long Short-Term Memory) Autoencoders. The hybrid approach aims to provide a robust and adaptable solution for identifying anomalies in dynamic and evolving datasets.

## Table of Contents

1. [Algorithm Overview](#algorithm-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Code Structure](#code-structure)
5. [Dependencies](#dependencies)
6. [Customization](#customization)
7. [Results and Visualization](#results-and-visualization)
8. [Troubleshooting](#troubleshooting)
9. [Contributing](#contributing)
10. [License](#license)

## Algorithm Overview

The hybrid algorithm combines the following anomaly detection techniques:

- **Isolation Forest:** Effective for isolating anomalies in the dataset.
- **Seasonal Hybrid ESD:** Specially designed for time-series data with seasonality.
- **Autoencoders:** Captures complex patterns in the data using neural network-based unsupervised learning.
- **LSTM Autoencoders:** Extends the capabilities of autoencoders to handle sequential dependencies in time-series data.

## Installation

To run the code, follow these installation steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/SachdevaVansh/Anomaly_Detection.git
   cd repository

2. Install the required python packages
   ```bash
   pip install -r requirements.txt

## Usage
Run the following code by executing the main script

'''bash
python AnomalyDetection.py

## Code Structure
The code is organized as follows:

AnomalyDetection.py: The main Python script containing the real-time anomaly detection implementation.
requirements.txt: List of Python dependencies required for running the code.

## Dependencies
The code relies on the following Python packages:

numpy
matplotlib
scikit-learn
tensorflow
Ensure that these packages are installed before running the code.

## Customization
The code can be customized for specific use cases:

Adjust anomaly detection thresholds in the code based on the characteristics of your data.
Fine-tune hyperparameters of individual algorithms for optimal performance.
Modify the data stream simulation process to reflect the patterns present in your real-world data.

## Results and Visualization
The code provides real-time visualization of the data stream and detected anomalies. Anomalies are highlighted in the plot, and a message is printed when an anomaly is detected.

## Troubleshooting
If you encounter issues, consider the following:

Check that the required Python packages are installed (requirements.txt).
Review error messages and consult the documentation for specific troubleshooting steps.

## Contributing
We welcome contributions! If you find issues or have suggestions, please create a GitHub issue or submit a pull request.

## License
This project is licensed under the MIT License.


