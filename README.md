# Comparing CNNs and SVMs for Image Classification on CIFAR-10

This project investigates the performance and computational trade-offs between Convolutional Neural Networks (CNNs) and Support Vector Machines (SVMs) with PCA-preprocessed features on the CIFAR-10 dataset. The goal is to understand how model structure, data size, and hyperparameters affect accuracy and runtime.

## Repository Structure

The repository contains the following files:

- **cnn_vs_kernel.ipynb**  
  Contains code snippets from initial tests.  

- **cnn_vs_kernel_experiment.ipynb**  
  The full notebook for this project accompanied with plots and printouts.
  Contains all code for data loading, preprocessing, model training, hyperparameter tuning, and evaluation.  

- **cnn_vs_kernel_experiment_commented.ipynb**     
  Cleaned up and added comments for clarity

- **README.md**  
  This file, describing the project, repository structure, and how to reproduce the experiments.

## Dataset
We use the CIFAR-10 dataset, which contains 60,000 color images (32×32 pixels) in 10 classes.

# To perform the study yourself:
1. Download the cifar-10-python.tar.gz file from https://www.cs.toronto.edu/~kriz/cifar.html 
and place it in a folder named data in the same directory as the notebook

2. Download and open the notebook cnn_vs_kernel_experiment_commented.ipynb

3. Install the required Python libraries
```bash
   pip install torch torchvision scikit-learn numpy pandas matplotlib seaborn
  ```
4. Remove the comment from the first cell (you only need to run it one time)

5. Run the notebook from start to finish!
The rest of the notebook is self-contained and handles data loading, preprocessing, model training and evaluation automatically.
Because some modules don't allow for perfect reproducibility tools you should expect slightly different, but still overall similar results.

