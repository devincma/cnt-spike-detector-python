# Interictal Spike Detector

This is the Python implementation of the interictal spike detector created by Dr. Erin Conrad at Center for Neuroengineering and Theraputics at University of Pennsylvania. Interictal spikes are important in epileptogenesis. However, detection of these spikes is a non-trivial engineering challenge.

## Features

- **Fast**: This implementation takes advantage of concurrency and runs up to 10 times faster than existing implementation.
- **Validated**: Dr. Conrad's spike detector was validated by board-certified epileptologists and used for publications. This implementation was validated against Dr. Conrad's results and achieved over 95% accuracy. See [here](https://docs.google.com/spreadsheets/d/1q7JXyvOPsXhUxyvjG5FM3ddy4wZExehpnZe6P8AXZXw/edit?usp=sharing) for more validation results.
- **Easy to use**: Just pass in a 1-minute EEG segment, and it will return the location of the spikes and the corresponding channels.

## Getting Started

Get started by running the examples in the `example.ipynb` file.

The main spike detector is implemented in the `spike_detector.py` file. Other Python files contain helper functions that the spike detector depends on.

## Contact

Devin Ma <devinma@alumni.upenn.edu>
