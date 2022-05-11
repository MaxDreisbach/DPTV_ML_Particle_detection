# DPTV_ML_Particle_detection
Particle detection by means of neural networks and synthetic training data refinement in defocusing particle tracking velocimetry (DPTV)

by Maximilian Dreisbach (Institute of Fluid Mechanics (ISTM) - Karlsruhe Institute of Technology (KIT))

This code allows the training of neural networks for particle detection in DPTV as well as the generation of refined synthetic training data as presented at in the MST special issue.

The datasets used in this work, as well as the neural networks learned for particle detection on these datasets are available here:
https://bwsyncandshare.kit.edu/s/WxbXQDprSFmcHrQ

If you have any questions regarding this code, feel free to contact Maximilian (maximilian.dreisbach@kit.edu).

## Requirements
- Python (required packages below)
- Working TensorFlow Object Detection API (see: https://github.com/tensorflow/models)

## Tested for: 
- Python 3.7
- tensorflow-gpu==1.14.0 
- keras==2.3.1
- numpy==1.18.1
- opencv-python==4.4.0.42
- pillow==7.0.0
- pandas==1.0.1
- scipy==1.4.1
- xlsxwriter==1.2.7

## Getting Started
- Run detection from the jupyter notebook M1_particle_detection_evaluate_results.ipynb

