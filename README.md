# Adversarial Machine Learning Final Project
## How to Run

Open the notebook and run all cells in order.

Main notebook:
- `final-project.ipynb`

This notebook:
- trains a baseline CNN on MNIST
- evaluates clean accuracy
- generates FGSM adversarial examples
- runs adversarial training
- compares baseline vs adversarially trained robustness across epsilon values

## Required Packages / Dependencies

- Python 3
- PyTorch
- torchvision
- matplotlib
- numpy

## Where the Main Code Is

- **Training code:** CNN training and adversarial training sections in `final-project.ipynb`
- **Inference / evaluation code:** clean accuracy evaluation and FGSM testing sections in `final-project.ipynb`
- **Demo / visualization code:** accuracy-vs-epsilon plots and adversarial example visualization cells in `final-project.ipynb`

## Output

The notebook saves final results to a text file and produces plots comparing:
- baseline clean accuracy vs adversarially trained clean accuracy
- FGSM robustness across different epsilon values
