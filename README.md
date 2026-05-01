# PyTorch Healthcare Deep Learning Labs

A beginner-friendly PyTorch repository containing tensor basics, neural-network fundamentals, and healthcare-focused DNN notebooks.

## Project overview

This repo is organized as a small learning portfolio:

1. **PyTorch Tensor Basics** — tensor creation, indexing, slicing, reshaping, and math operations.
2. **PyTorch Basics: Tensors, Losses, and Training** — activation functions, gradients, loss functions, and a simple training loop.
3. **Mortality Prediction with a DNN** — diagnosis-code based mortality prediction using a neural network.
4. **Heart Failure Prediction with a DNN** — binary classification for heart-failure prediction using SVMlight data.

> Important: the healthcare notebooks require datasets that are **not included**. Do not upload private, restricted, or licensed medical data to GitHub unless you have permission.

## Repository structure

```text
pytorch-healthcare-dnn-labs/
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
├── notebooks/
│   ├── 01_pytorch_tensor_basics.ipynb
│   ├── 02_pytorch_basics_tensors_loss.ipynb
│   ├── 03_mortality_prediction_dnn.ipynb
│   └── 04_heart_failure_prediction_dnn.ipynb
├── src/
│   └── utils.py
├── data/
│   ├── README.md
│   ├── hw2/
│   │   └── .gitkeep
│   └── lab2/
│       └── .gitkeep
└── outputs/
    └── .gitkeep
```

## Setup

### Option 1: local Python environment

```bash
git clone https://github.com/YOUR-USERNAME/pytorch-healthcare-dnn-labs.git
cd pytorch-healthcare-dnn-labs

python -m venv .venv
source .venv/bin/activate      # macOS/Linux
# .venv\Scripts\activate     # Windows

pip install -r requirements.txt
jupyter notebook
```

### Option 2: Google Colab

1. Open a notebook from the `notebooks/` folder.
2. Upload the required data files manually.
3. Adjust `DATA_PATH` inside the notebook if needed.

## Data setup

### Heart failure notebook

Expected folder:

```text
data/hw2/
```

Expected files:

```text
features_svmlight.train
features_svmlight.val
features_svmlight.test
```

### Mortality prediction notebook

Expected folder:

```text
data/lab2/
```

Expected files depend on the original assignment dataset, commonly including CSV files such as:

```text
PATIENTS.csv
ADMISSIONS.csv
DIAGNOSES_ICD.csv
```

Because healthcare datasets can be sensitive or licensed, the repository includes only placeholder folders.

## What was cleaned for GitHub

- Notebook outputs were cleared to reduce file size.
- File names were renamed to GitHub-friendly names.
- `TODO`, `pass`, and `raise NotImplementedError` placeholders were cleaned where possible.
- Dataset paths were changed to use the local `data/` folder.
- A reusable `src/utils.py` file was added for SVMlight loading.
- `.gitignore` was added to avoid uploading virtual environments, cache files, and private datasets.

## Suggested next improvements

- Add more markdown explanation before each model-training section.
- Add screenshots or result summaries after you run the notebooks with permitted data.
- Add a short project diagram to the README.
- Add model evaluation notes comparing accuracy, AUC, precision, recall, and F1.
- Add a `notebooks/README.md` if the repo grows.

## Academic/source note

If these notebooks are based on course materials or IBM/Coursera lab notebooks, check the license and your course policy before publishing. Add proper credit where required.

## License

This starter repo includes an MIT license for your original additions. Only keep the license if you have the right to publish the notebook content.
