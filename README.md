# Internet Firewall Data Mining Project

## Project Overview
This project applies various data mining techniques to analyze internet firewall data collected from a university's traffic records.

## Dataset
[Internet Firewall Data Set](https://www.kaggle.com/datasets/tunguz/internet-firewall-data-set)

## Techniques Implemented

1. **Preprocessing**
   - Data cleaning and preparation
   - Principal Component Analysis (PCA) for dimensionality reduction

2. **Association Rules Mining**
   - Discovering interesting relationships in the data 
   - Implemented using the Apriori algorithm in IBM SPSS Modeler

3. **Classification**
   - Decision Tree algorithm
   - K-Nearest Neighbors (KNN) algorithm

4. **Clustering**
   - K-means clustering
   - Agglomerative clustering

## Project Structure
```
├── association rules
│ ├── association_rules.str
│ └── preprocessed_cat.csv
├── classification
│ ├── decision_tree.ipynb
│ ├── KNN_cat.ipynb
│ └── KNN.ipynb
├── clustering
│ ├── agglomerative.ipynb
│ └── kmeans.ipynb
├── dataset
│ ├── clustering.csv
│ ├── dataset.csv
│ ├── pca.csv
│ ├── preprocessed_cat.csv
│ └── preprocessed.csv
├── preprocessing
│ ├── PCA.ipynb
│ └── preprocessing.ipynb
└── reports/
```

## Tools and Technologies
- Python
- Jupyter Notebooks
- Scikit-learn for machine learning algorithms
- Pandas and NumPy for data manipulation
- Matplotlib and Seaborn for data visualization

## Results and Insights
Findings and insights can be found in the `Report.pdf` file in the `reports` directory.
