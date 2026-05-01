# PyTorch Healthcare DNN Labs

This repository contains beginner-friendly PyTorch notebooks for learning tensor operations, neural network basics, and deep learning applications in healthcare prediction tasks.

The project is organized as a small learning portfolio. It includes basic PyTorch tensor practice, loss functions, simple neural network concepts, mortality prediction using diagnosis codes, and heart failure prediction using a deep neural network.

---

## Repository Contents

| File | Description |
|---|---|
| `01_pytorch_tensor_basics.ipynb` | Introduction to PyTorch tensors and basic tensor operations. |
| `02_pytorch_basics_tensors_loss.ipynb` | PyTorch basics including tensors, loss functions, and simple neural network building blocks. |
| `03_mortality_prediction_dnn.ipynb` | Deep neural network model for mortality prediction using diagnosis-code based healthcare data. |
| `04_heart_failure_prediction_dnn.ipynb` | Deep neural network model for heart failure prediction. |
| `requirements.txt` | Python packages required to run the notebooks. |
| `.gitignore` | Prevents unnecessary files, cache files, and private data files from being uploaded. |
| `LICENSE` | License information for this repository. |

---

## Project Goals

The goals of this project are to:

- Practice PyTorch tensor operations.
- Understand how loss functions are used in neural network training.
- Build beginner-level deep neural networks using PyTorch.
- Apply deep learning concepts to healthcare prediction problems.
- Organize machine learning notebooks into a clean GitHub portfolio project.

---

## Topics Covered

- PyTorch tensors
- Tensor indexing and reshaping
- Loss functions
- Neural network layers
- Model training loops
- Binary classification
- Healthcare prediction tasks
- Mortality prediction
- Heart failure prediction
- Deep neural networks

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
cd YOUR-REPOSITORY-NAME
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY-NAME` with your actual GitHub username and repository name.

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate the environment:

For Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebooks

```bash
jupyter notebook
```

Then open the notebooks one by one in this order:

1. `01_pytorch_tensor_basics.ipynb`
2. `02_pytorch_basics_tensors_loss.ipynb`
3. `03_mortality_prediction_dnn.ipynb`
4. `04_heart_failure_prediction_dnn.ipynb`

---

## Dataset Notice

The healthcare notebooks may require external datasets that are not included in this repository.

Because healthcare datasets can contain sensitive or restricted information, this repository does **not** include private medical data.

Before running the prediction notebooks, make sure you have permission to use the required dataset files and place them in the correct local folder expected by the notebook.

Do not upload private, restricted, or patient-level medical data to GitHub.

---

## How to Use This Repository

This repository is best used as a learning project. Start with the PyTorch basics notebooks, then move to the healthcare prediction notebooks.

Recommended order:

1. Learn tensor operations.
2. Understand loss functions.
3. Study how neural networks are built in PyTorch.
4. Train and evaluate healthcare prediction models.
5. Improve the notebooks by adding more explanation, visualizations, and model evaluation metrics.

---

## Possible Improvements

Future improvements can include:

- Add more markdown explanation before each code section.
- Add model evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
- Add training and validation loss plots.
- Add confusion matrix visualizations.
- Move reusable code into Python scripts.
- Add sample synthetic data so the notebooks can run without private datasets.
- Add a `notebooks/` folder to keep the repository more organized.
- Add screenshots of results to the README.

---

## Important Disclaimer

This project is for educational purposes only. The models in this repository are not intended for clinical decision-making or real-world medical diagnosis.

Healthcare machine learning models should be validated carefully and reviewed by qualified professionals before any real-world use.

---

## Author

Created by **Nobel789** as a PyTorch and healthcare deep learning learning project.
