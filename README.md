# Fashion MNIST Classification with PyTorch + Optuna

This project classifies Fashion MNIST images using a fully connected Neural Network built with **PyTorch**.  
Hyperparameter tuning was done using **Optuna**.

## Project Highlights

- Framework: PyTorch
- Dataset: Fashion MNIST
- Model: Artificial Neural Network (ANN)
- Hyperparameter Tuning: Optuna
- Best Accuracy: **85.11%**

## Best Hyperparameters (from Optuna)

| Parameter         | Value     |
|-------------------|-----------|
| Hidden Layers     | 3         |
| Neurons per Layer | 110       |
| Learning Rate     | 0.000666  |
| Epochs            | 37        |
| Dropout           | 0.42      |

## Tech Stack

- Python
- PyTorch
- Optuna
- Pandas, NumPy
- Scikit-learn

## How to Run

1. Open the notebook in Google Colab or Jupyter
2. Upload the Fashion MNIST CSV
3. Run all cells

## What I Learned

- Building ANN from scratch in PyTorch
- Using `Dataset` and `DataLoader`
- Hyperparameter optimization with Optuna
- Training and evaluating deep learning models
