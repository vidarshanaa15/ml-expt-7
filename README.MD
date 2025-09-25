# Experiment 5:  Dimensionality Reduction and Model Evaluation (With and Without PCA)

## 🎯 Objective
To implement and analyze the performance of clustering algorithms on the Human Activity Recog
nition dataset:
- **Model A:** K-Means Clustering.
- **Model B:** DBSCAN (Density-Based Spatial Clustering of Applications with Noise).
- **Model C:** Hierarchical Agglomerative Clustering (HAC).
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

## 📈 Clustering Algorithm Performance
| Algorithm     | Silhouette | Davies-Bouldin | Calinski-Harabasz | ARI    | NMI    |
|---------------|------------|----------------|-------------------|--------|--------|
| K-Means       | 0.3274     | 1.7458         | 3605.2632         | 0.3279 | 0.5163 |
| DBSCAN        | 0.1411     | 2.8599         | 825.3915          | 0.2760 | 0.4262 |
| Hierarchical  | 0.2548     | 1.9275         | 3350.0213         | 0.3422 | 0.5397 |

## 🙌 Credits

This experiment is part of the course **“ICS1512-Machine Learning Algorithms Laboratory”** at **SSN College of Engineering**.
