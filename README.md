# Mall Customer Segmentation (Hierarchical Clustering)

An unsupervised machine learning project that segments 200 retail mall customers into 5 actionable personas based on **Annual Income** and **Spending Score** using **Agglomerative Hierarchical Clustering**.

## Highlights
* **Tech Stack:** Python, Pandas, NumPy, Scikit-Learn, SciPy, Matplotlib
* **Model:** `AgglomerativeClustering` (`n_clusters=5`, Euclidean distance, Ward's linkage)
* **Validation:** Optimal $k=5$ confirmed via SciPy dendrogram analysis and a **Silhouette Score of `0.5530`**

## Customer Segments

| Cluster | Persona | Income | Spending | Strategy |
| :--- | :--- | :--- | :--- | :--- |
| **0** | **Careful** | High | Low | VIP loyalty rewards & premium memberships |
| **1** | **Standard** | Average | Average | Seasonal promotions & cross-selling |
| **2** | **Target Group** | High | High | Exclusive launches & luxury offerings |
| **3** | **Careless** | Low | High | Flash sales, bundles & flexible payments |
| **4** | **Sensible** | Low | Low | Discount coupons & budget essentials |

## Quick Start

```bash
git clone [https://github.com/YOUR-USERNAME/mall-customer-segmentation.git](https://github.com/YOUR-USERNAME/mall-customer-segmentation.git)
cd HierarchicalClustering_basics
pip install numpy pandas scikit-learn scipy matplotlib jupyter
jupyter notebook h-clustering.ipynb
