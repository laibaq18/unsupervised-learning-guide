<div align="center">

# Guide to Unsupervised Learning
### Dimensionality Reduction · Clustering · Association Rule Learning

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/-Machine%20Learning-8A2BE2?style=flat)

*A practical reference for finding structure in unlabeled data - what each method does, when to reach for it, and how to actually run it.*

</div>


## Which technique do I use?

| Goal | Use | Why |
|---|---|---|
| Visualize high-dimensional data, preserve **local** neighborhoods | **t-SNE** / UMAP | Nonlinear, keeps nearby points nearby; UMAP scales better |
| Reduce dimensions before a downstream model, preserve **global** variance | **PCA** | Linear, fast, interpretable components |
| Partition into K clusters, fast, large datasets | **K-means** | Simple, scales well, needs K in advance |
| Don't know K, want a hierarchy / dendrogram | **Hierarchical Clustering** | No pre-specified K, visual cut points |
| Arbitrary-shaped clusters, need outlier/noise detection | **DBSCAN** | Density-based, finds noise points automatically |
| "People who bought X also bought Y" style patterns | **Apriori / FP-Growth** | Purpose-built for co-occurrence in transactions |

---

## Real-world applications
- **Dimensionality reduction** : visualization, noise reduction, feature extraction before supervised models, climate pattern detection, genomics
- **Clustering** : customer segmentation, image segmentation, document/news clustering, fraud & anomaly detection
- **Association rules** : retail market-basket analysis, cross-selling, symptom–disease patterns in health records, web usage mining

---

## Full report
The complete write-up - full mathematical derivations and all references  is in [`Report.pdf`](Unsupervised_Learning_.pdf).

! TO DO: Add code files on implementation of all the different tehniques/algorithms
