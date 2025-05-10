
# Clustering Algorithms: Complexity Analysis and Experimental Evaluation

**Concordia University – Department of Computer Science & Software Engineering**  
Course: *COMP 6651 NN – Algorithm Design Techniques*  
Team: *Divyesh Pravinkumar Patel, Farid Faraji, Nitheesh Kumar Kambala, Sotirios Damas*  

---

## 1. Project Overview
This two-part project is a deep dive into classical and modern **clustering algorithms**, combining rigorous complexity analyses with practical implementations.  

We:

* **Studied, derived, and analysed** nine algorithms and seven evaluation metrics in a formal IEEE-style report (Part I).  
* **Implemented and benchmarked** the algorithms from scratch *and* via [`scikit-learn`](https://scikit-learn.org/stable/index.html#), ran them on three real-world datasets, and investigated accuracy pitfalls and feature-selection strategies (Part II).  

The repository therefore serves as:

1. A **mini-toolbox** of clean, notebook-based Python implementations.
2. A **reproducible experimental suite** that compares baseline code to `scikit-learn` optimisations.
3. A **reference** on complexity analysis, metric suitability, and practical improvement tricks.


---

## 2. Algorithms Covered
| Paradigm | Algorithms Implemented |
|----------|-----------------------|
| **Density-based** | DBSCAN, OPTICS |
| **Centroid / Medoid** | k-means, k-medoids |
| **Distribution-based** | Gaussian Mixture Models  |
| **Hierarchical** | BIRCH, Agglomerative Clustering |
| **Exemplar-based** | Affinity Propagation, Mean-Shift |

Each notebook provides **pseudo-code, complexity derivation, diagnostics plots, metric tables**, and a **side-by-side comparison** with `sklearn`.

---

## 3. Evaluation Metrics Investigated
Silhouette Score • Davies-Bouldin • Calinski-Harabasz • Adjusted Rand Index • Mutual Information • Split • Diameter  
We discuss mathematical definitions, interpretations, and *tight* complexity bounds.

---

## 4. Datasets Used
| Dataset | Domain | Size | Link |
|---------|--------|------|------|
| **Iris** | Plant morphology | 150 rows, 5 columns | [Kaggle](https://www.kaggle.com/datasets/himanshunakrani/iris-dataset) |
| **AI Global Index** | Country AI indicators | 62 rows, 13 columns | [Kaggle](https://www.kaggle.com/datasets/katerynameleshenko/ai-index) |
| **Recent Earthquakes** | Seismology events | 1137 rows, 37 columns | [Kaggle](https://www.kaggle.com/datasets/shreyasur965/recent-earthquakes) |

Custom preprocessing utilities for numeric + categorical scaling are provided.

---

