#  Career Path Clustering using NLP & Machine Learning

##  Project Overview
This project applies **Natural Language Processing (NLP)** and **Unsupervised Machine Learning** to analyze resumes and cluster them into potential **career paths** such as Data Science, Web Development, and Human Resources.  
The project also uses the **Apriori algorithm** to discover frequent skill associations that validate cluster insights.

---

##  Tech Stack
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, plotly, wordcloud, mlxtend  
- **Environment:** Google Colab / Jupyter Notebook  

---

##  Workflow

### 1. Data Collection
- Resume dataset in CSV format (`resume.csv`).

### 2. Data Preprocessing
- Text cleaning (lowercasing, tokenization, stopword removal).  
- Feature extraction using **TF-IDF Vectorization**.  

### 3. Exploratory Data Analysis (EDA)
- Dataset overview (shape, missing values, samples).  
- Word frequency and word clouds.  
- Resume length distribution.  
- Top skills bar chart (static + interactive using Plotly).  

### 4. Dimensionality Reduction
- **PCA** and **t-SNE** for visualization.  

### 5. Clustering
- **KMeans** (primary algorithm).  
- Optionally checked with **DBSCAN** and **Hierarchical (Dendrogram)**.  

### 6. Evaluation Metrics
- **Silhouette Score**  
- **Davies–Bouldin Index**  

### 7. Insights
- Extracted top keywords per cluster.  
- Compared resume lengths per cluster.  
- Generated cluster-specific word clouds.  

### 8. Apriori Algorithm
- Used **Apriori (Association Rule Mining)** to discover common skill associations.  
- Example: "Python" → "Machine Learning, TensorFlow".  

---

##  Results
- Resumes are successfully clustered into **career paths**.  
- Apriori confirms strong skill associations supporting clusters.  
- Interactive Plotly visuals provide deeper insights.  

---

##  Sample Visuals
- WordCloud of resumes.  
- t-SNE cluster scatterplot.  
- Interactive bar charts & treemaps.  

---

##  How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/career-path-clustering.git
   cd career-path-clustering
