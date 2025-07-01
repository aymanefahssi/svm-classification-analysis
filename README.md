#  Convex vs Non-Convex Optimization in SVM and MLP

This project compares convex and non-convex optimization techniques in machine learning, using:
- **Support Vector Machine (SVM)** with Sequential Minimal Optimization (SMO)
- **Multi-Layer Perceptron (MLP)** trained with **SGD** and **Adam**

The classification task is based on the **MNIST dataset**, filtered to digits **3** and **8**.

---

##  Objective

- Understand the impact of convex vs non-convex optimization on model performance.
- Compare training time, accuracy, and robustness of SVM vs MLP.
- Evaluate optimization methods (SMO, SGD, Adam) on a challenging binary classification problem.

---

## Dataset

- **MNIST** handwritten digits dataset (28x28 grayscale images).
- Only digits **3** and **8** are used for **binary classification**.
- Data is normalized to [0, 1] and flattened into 784-feature vectors.

---

## Tools and Libraries

- Python 3.13
- PyTorch
- Scikit-learn
- Pandas, NumPy
- Matplotlib
- Jupyter Notebook

---

## How to Run

```bash
# 1. Environnemnet 
-Install python 3.13
-Create env : python -m venv pytorch_env
-Activate environnement : pytorch_env\Scripts\activate
-Install ipykernel : pip install ipykernel
- Add environnement : python -m ipykernel install --user --name=pytorch_env --display-name "Python 3.13 - PyTorch"
# 2. Install dependencies
pip install  torch torchvision  scikit-learn pandas matplotlib numpy

# 3. Run the notebook
jupyter notebook
