# IA-Personality-behavior
# Personality Prediction System (Introvert vs Extrovert)

This project predicts if a person is **introvert** or **extrovert** using Python. It includes data cleaning, analysis, preprocessing, modeling, cross-validation, and feature selection. 
The dataset used in this project is available here:  
[Personality Traits Dataset (Kaggle)](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)
---
## 1. Tools and Libraries

The project uses the following tools and libraries:

- **Python 3**
- **Pandas** → data manipulation  
- **NumPy** → numerical operations  
- **Matplotlib** → basic visualizations  
- **Seaborn** → advanced plots (pair plots, box plots, histograms)  
- **Scikit-learn (sklearn)** → preprocessing, PCA, ML models, cross-validation  
- **PyCaret** → automatic machine learning and model comparison  

## 2. Structure of the Project

The repository includes:

1. **Preprocessing & Analysis**
   - `preprocessing.ipynb`: Data cleaning, exploratory data analysis, visualizations (pair plots, box plots, histograms, class distribution).
   - `preprocessing2.ipynb`: Normalization, PCA (3 components), and related charts.
   - Generated datasets:
     - **Cleaned** version  
     - **Normalized** version  
     - **PCA-transformed** version

2. **Modeling**
   - Notebook using **PCA dataset**: model training with confusion matrices and metrics (F1, recall, precision).
   - **Cross-validation & feature selection** notebook: shows how to choose the best features and validate models.
   - `experiments.ipynb`: PyCaret experiments and model comparison.

3. **Support Materials**
   - `personality dataset ppt.pdf`: presentation in Spanish, covers analysis, visualizations, models, normalization, PCA, outliers, and best model summary (top 3).

---

## 3. Highlights

- **Modular design**: You can run models with either **cleaned**, **normalized**, or **PCA** data.
- **Clear visual insights**: Each step (EDA, PCA, preprocessing) has visual support through charts and tables.
- **Comprehensive modeling**: Includes classical ML models, cross-validation, and feature selection.
- **Presentation included**: The PPT summarizes the whole process—very useful for sharing or reviewing.

---

## 4. How to Use This Project

1. Open and run the notebooks in order:
   - Start with `preprocessing.ipynb` to clean and explore data.
   - Then use `preprocessing2.ipynb` for normalization and PCA.
   - Check `experiments.ipynb` for automated comparisons with PyCaret.
   - Next, go to the modeling notebook (with PCA) or cross-validation & feature selection notebook.

2. You can switch easily between:
   - the **cleaned dataset**
   - the **normalized dataset**
   - the **PCA dataset**

3. Visualize your results in the notebooks or open the PPT for an overview of the project.

---

## 5. Contact / Author

- Developed by **Vanessa Herrera**.




Thank you for exploring the project! Feel free to ask if you want help explaining any part in more detail or adding features.
