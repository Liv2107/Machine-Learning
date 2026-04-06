# Machine Learning Coursework

This repository contains coursework and practical implementations for machine learning concepts, focusing on data analysis, dimensionality reduction, and visualisation techniques using Python.

---

## 📌 Overview

The project explores key machine learning techniques including:

- Data preprocessing and normalisation  
- Covariance matrix estimation  
- Principal Component Analysis (PCA)  
- Dimensionality reduction  
- Data reconstruction and visualisation  

The main objective is to analyse high-dimensional data (blood vessel shapes) and reduce it to a lower-dimensional representation while preserving key structural information.

---

## 📊 Principal Component Analysis (PCA)

PCA is used to:

- Identify directions of maximum variance in the data  
- Reduce dimensionality (from 1845 → 5 dimensions)  
- Reconstruct original data from compressed representations  

### Manual PCA

- Mean centering of data  
- Covariance matrix computation  
- Eigen decomposition using NumPy  
- Projection onto top principal components  
- Reconstruction of original data  

### Scikit-learn PCA

- PCA using `sklearn.decomposition.PCA`  
- Comparison with manual implementation  
- Validation of eigenvalues, eigenvectors, and reconstruction  

---

## 📈 Visualisation

The project includes 3D visualisation of blood vessel shapes:

- Original vessel structures  
- Reconstructed vessels after PCA compression  
- Overlay plots to compare reconstruction quality  

---

## 🧠 Key Concepts Demonstrated

- Eigenvalues and eigenvectors  
- Variance maximisation  
- Orthogonal feature spaces  
- Data compression vs information loss  
- Reconstruction accuracy  

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📂 Project Structure
.
├── data/
├── notebooks/
├── scripts/
├── results/
└── README.md

---

## 🚀 How to Run

1. Clone the repository:

`git clone https://github.com/Liv2107/Machine-Learning.git`
`cd Machine-Learning`

2. Install dependencies:

`pip install numpy matplotlib scikit-learn`

3. Run the scripts or notebooks:

`python main.py`

or open the notebooks in Jupyter.

---

## 📌 Results

- PCA successfully reduces dimensionality from 1845 to 5  
- Reconstructed vessel shapes preserve overall structure  
- Some fine detail is lost due to compression  
- Manual PCA results closely match scikit-learn implementation
- Manual restoration had a 0.993 variance scrore.

---

## 👤 Author

Olivia Emms  
MSc Advanced Computer Science (Artificial Intelligence) @ University of Leeds 2026

---

## 📄 License

This project is for academic use.
