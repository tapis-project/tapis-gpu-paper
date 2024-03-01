# TACC GPU-Aware Platforms Paper Repository

Small Abstract about GPU-Aware

The goal of this repository is to act as a center of operations for experiments. This repository will contain information and code used to create our experiments and graphics. Code will usually be presented in the form of Jupyter Notebooks (.ipynb) and consists of Python code blocks.

## Repository Composition

This repository holds the following folders and files:
 
 **experiments.ipynb**  
Old - if we have experiments, it would be nice to have.

**graph.ipynb**  
This Jupyter Notebook file contains all the Python code used in parsing our experiment data and visualizing it. The visualization is done with Python's `matplotlib` and `pandas` libraries.
 
**~/experiment_data**  
This folder contains `.csv` files which contain outputs from our experiments. Which experiment and which experiment case is stated in the filenames.

**~/images_and_graphs**  
This folder contains graphics which were created by our `graph.ipynb` notebook for use in our paper. The filenames describe the experiment and experiment case.

 
## Information
This experiment relies on the Pods service hosted by TACC at `https://tacc.tapis.io/v3/pods`. You will have to work around any issues that you might face as your situation will not match ours in the case of you running the experiments yourself.

