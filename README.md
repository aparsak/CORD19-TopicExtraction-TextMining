# 🦠 COVID-19 Text Mining and Clustering Project 📊

## 📖 Overview

In this project, we explored text mining techniques on a subset of the widely recognized CORD-19 dataset from the TREC conference. Our goal was to preprocess text, reduce dimensionality, visualize complex patterns, and extract meaningful topics from clusters of research papers. We also aimed to cluster similar articles to enhance search and retrieval in large text corpora.

## 🔍 Features

- **Text Preprocessing**: Tokenization, lemmatization, and more.
- **Dimensionality Reduction**: Techniques like PCA to handle high-dimensional data.
- **Clustering**: Grouping similar articles using K-Means clustering.
- **Topic Modeling**: Discovering meaningful topics in clusters.
- **Visualization**: Using t-SNE for 2D visualization of clusters and data patterns.

## 🛠️ Technologies Used

- **Python Libraries**:
  - `pandas` 
  - `numpy` 
  - `matplotlib` 
  - `seaborn` 
  - `scikit-learn` 
  - `spacy` 
  - `langdetect` 
  - `tqdm` 
  - `plotly` 

## 📑 Dataset

The CORD-19 dataset is a comprehensive collection of research papers related to the COVID-19 pandemic. CORD-19 stands for "COVID-19 Open Research Dataset." The dataset provides a rich source of information for analyzing research trends, topics, and the evolution of scientific knowledge related to COVID-19.

## 🚀 Getting Started

1. **Install Required Packages**:
   ```bash
   pip install langdetect scispacy spacy
   pip install https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.5.4/en_core_sci_lg-0.5.4.tar.gz
   ```

## 📚 Usage

- **Preprocessing**: Clean and prepare text data by tokenizing and lemmatizing.
- **Dimensionality Reduction**: Apply PCA to reduce the number of features while retaining 95% of the variance.
- **Clustering**: Use various clustering methods and compare their performance using silhouette scores to group similar articles.
- **Topic Modeling**: Extract topics from clusters using LDA.
- **Visualization**: Create interactive plots to explore clusters and topics.

## 🤝 Contributing

Feel free to fork the repository and submit pull requests. Any contributions or suggestions for improvements are welcome!

## 📧 Contact

For any questions or feedback, please contact aprsa.kahdem@gmail.com.

##
This project was part of the Data Mining Course at Amirkabir University of Technology.

Coded by Parsa Khadem and Sarvin Baghi.
