# Interictal Spike Detector

This is the Python implementation of the interictal spike detector created by [Dr. Erin Conrad](https://www.med.upenn.edu/apps/faculty/index.php/g324/p8590351) at [Center for Neuroengineering and Theraputics](https://cnt.upenn.edu/) at University of Pennsylvania. Interictal spikes are important in epileptogenesis. However, detection of these spikes is a non-trivial engineering challenge.

## Features

- **Fast**: This implementation takes advantage of concurrency and runs up to 10 times faster than existing implementation.
- **Validated**: Dr. Conrad's spike detector was validated by board-certified epileptologists and used for publications. This implementation was validated against Dr. Conrad's results and achieved over 95% accuracy. See [here](https://docs.google.com/spreadsheets/d/1q7JXyvOPsXhUxyvjG5FM3ddy4wZExehpnZe6P8AXZXw/edit?usp=sharing) for more validation results.
- **Easy to use**: Just pass in a 1-minute EEG segment, and it will return the location of the spikes and the corresponding channels.

## Getting Started

Get started by running the examples in the `example.ipynb` file.

The main spike detector is implemented in the `spike_detector.py` file. Other Python files contain helper functions that the spike detector depends on.

## Contact

Devin Ma <devinma@alumni.upenn.edu>

## Acknowledgement

I thank Carlos Aguilla, Nina Ghosn, Alfredo Lucas, Will Ojemann, Dr. Erin Conrad, and Dr. Brian Litt for their help.

## Related Publications

- Conrad EC, Revell AY, Greenblatt AS, Gallagher RS, Pattnaik AR, Hartmann N, Gugger JJ, Shinohara RT, Litt B, Marsh ED, Davis KA. Spike patterns surrounding sleep and seizures localize the seizure-onset zone in focal epilepsy. Epilepsia. 2023 Mar;64(3):754-768. doi: 10.1111/epi.17482. Epub 2023 Jan 14. PMID: 36484572; PMCID: PMC10045742. [LINK TO PAPER](https://onlinelibrary.wiley.com/doi/10.1111/epi.17482)

- Conrad EC, Tomlinson SB, Wong JN, Oechsel KF, Shinohara RT, Litt B, Davis KA, Marsh ED. Spatial distribution of interictal spikes fluctuates over time and localizes seizure onset. Brain. 2020 Feb 1;143(2):554-569. doi: 10.1093/brain/awz386. PMID: 31860064; PMCID: PMC7537381. [LINK TO PAPER](https://academic.oup.com/brain/article/143/2/554/5682483)
