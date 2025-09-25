# Experiment 5:  Dimensionality Reduction and Model Evaluation (With and Without PCA)

## 🎯 Objective
To implement and analyze the performance of clustering algorithms on the Human Activity Recog
nition dataset:
- Model A: K-Means Clustering.
- Model B: DBSCAN (Density-Based Spatial Clustering of Applications with Noise).
- Model C: Hierarchical Agglomerative Clustering (HAC).
and to visualize and compare the clusters formed by each algorithm, report results, and
analyze performance.

---

## 🧰 Tools & Libraries Used
- **Python 3.10+** – Primary language for implementation
- **NumPy** – Efficient numerical operations and array handling
- **Pandas** – For loading, preprocessing, and managing datasets
- **Scikit-learn** – For implementing K-Means, DBSCAN, Hierarchical Clustering, PCA/t-SNE, and evaluation metrics
- **Matplotlib** – For visualizing clusters, elbow curves, silhouette scores, and metric comparison plots
- **Seaborn** – For enhanced visualization of cluster distributions and evaluation metrics

---

## 📁 Folder Structure
```bash
ml-expt-7/
├── README.md                        # Overview, tools, file summary, run instructions
├── datasets/ 
│   ├── train                        # Dataset used for clustering
│   └── test             
├── Experiment-7/
│   ├── expt-7.ipynb                 # Implementation notebook
├── screenshots/
│   ├── expt-7_5_0.png             
│   ├── expt-7_7_7.png
│   ├── expt-7_8_0.png
│   ├── ...
│   └── expt-7_22_0.png
├── Assignment7_ML_Vidarshanaa.pdf  # Lab report
├── Assignment7_ML_Vidarshanaa.tex  # Latex report
└── requirements.txt                # Python packages and versions used
```

## 🚀 Instructions to Execute the Code

1. **Clone the Repository**
```bash
   git clone https://github.com/vidarshanaa15/ml-expt-7.git
   cd ml-expt-7
```

2. **Open the Notebooks**
- **Using Google Colab:**
  - Go to Google Colab
  - Click File > Upload Notebook and upload any .ipynb file from the Experiment-7 folder
  - *Or* paste the GitHub URL directly in Colab to open from repo
    
- **Running Locally with Jupyter Notebook:**
  - Install required packages:
  ```bash
  pip install -r requirements.txt
  ```
  - Then run
  ```bash
  pip install notebook
  jupyter notebook
  ```
  - Navigate to the Experiment-7 folder and open a notebook in your browser

## 📈 Model Performance (No-PCA vs With-PCA)
| Model              | Performance (No-PCA)| Performance (With-PCA) |
|--------------------|---------------------|------------------------|
| SVM                | 0.9314              | 0.9245                 |
| Naive Bayes        | 0.7254              | 0.8329                 |
| KNN                | 0.9108              | 0.9085                 |
| Logistic Regression| 0.9130              | 0.9176                 |
| Decision Tree      | 0.8902              | 0.8741                 |
| Random Forest      | 0.9245              | 0.9085                 |
| AdaBoost           | 0.9153              | 0.9016                 |
| Gradient Boosting  | 0.9314              | 0.9085                 |
| XGBoost            | 0.9405              | 0.9108                 |
| Stacked Models     | 0.9199              | 0.9199                 |

## 🙌 Credits

This experiment is part of the course **“ICS1512-Machine Learning Algorithms Laboratory”** at **SSN College of Engineering**.
