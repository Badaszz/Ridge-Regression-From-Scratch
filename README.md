# Ridge Regression from Scratch

This repository contains my implementation of **Ridge Regression (L2-regularized least squares)** from scratch using Python and NumPy.  
The project was completed as part of the **Machine Learning course (Columbia University)**.

---

## 📌 Project Overview
Ridge Regression is a regularized version of linear regression that helps prevent overfitting by penalizing large weights.  
The penalty is controlled by a parameter **λ (lambda)**.

In this project, I:
- Implemented the closed-form solution for Ridge Regression from scratch (without scikit-learn).
- Ensured the **intercept term is not regularized** using mean-centering.
- Evaluated the model using **Mean Squared Error (MSE)** and **R² score**.
- Visualized predictions using Matplotlib.

---

## 📂 Repository Structure
```
Ridge-Regression-From-Scratch/
│
├── Ridge_regression_from_scratch.ipynb   # Jupyter Notebook with full implementation
├── requirements.txt                      # List of dependencies
├── README.md                             # Project documentation
└── .gitignore                            # Ignore notebook checkpoints, cache, etc.
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Ridge-Regression-From-Scratch.git
   cd Ridge-Regression-From-Scratch
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Mac/Linux
   venv\Scripts\activate      # On Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:
   ```bash
   jupyter notebook Ridge_regression_from_scratch.ipynb
   ```

---

## 📊 Results
- Achieved an **R² score of ~0.8** on the dataset.
- Visualized true vs predicted values with a **scatter plot** (perfect prediction line shown).
- Line plots demonstrated how predictions track actual values across samples.

---

## 🛠️ Built With
- [Python](https://www.python.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/) (for CSV loading)

---


## 📖 References
- Columbia University, *Machine Learning* (Course materials).

---

## 👤 Author
- **Yusuf Solomon**  
- GitHub: [@Badaszz](https://github.com/Badaszz)  
- LinkedIn: [Yusuf Solomon](https://linkedin.com/in/yusuf-solomon)

---
