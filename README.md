# neural-net-regression

This is the code used to optimize the weights of an under-parameterized neural network.
Training is done via gradient flow using MLPGradientFlow.jl (https://arxiv.org/abs/2301.10638). 
In this repo, we release the code to train and visualize the result of training for the erf 
activation function and standard Gaussian input data (https://arxiv.org/abs/2311.01644). 

## Files

* This file README.md
* Simulation file ```???```
* Script to see the loss curves and gradient norms ```plot-training.py```
* Script to see the summary of training ```plot-training-summary.py``` for all widths
* Script to visualize the weights at convergence ```plot-results.py```
* Helper functions ```helper.py```

## Dependencies

To visualize the results using Python as done in this repo. 

* juliacall
* numpy
* matplotlib 

## Results 

![loss_curves_25stud_50teach](https://github.com/berfinsimsek/neural-net-regression/assets/37277437/96eed74e-207b-457a-b908-c698849c84fe)


Jan 15, 2024
