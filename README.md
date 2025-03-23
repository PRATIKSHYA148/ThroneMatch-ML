# ThroneMatch-ML

Overview

This project applies machine learning techniques to analyze and visualize similarities between Game of Thrones characters. By using text-based embeddings and dimensionality reduction methods, we explore how different characters relate to one another based on their attributes.

Features

Data Processing: Reads character data from JSON format

Feature Extraction: Constructs a numerical representation of characters.

Similarity Computation: Uses cosine similarity, clustering, or other distance metrics to find similar characters

Dimensionality Reduction: t-SNE

Data Visualization: Plots clusters of characters to show relationships

Installation

# Clone the repository
git clone https://github.com/PRATIKSHYA148/ThroneMatch-ML.git
cd ThroneMatch-ML

# Install dependencies
pip install -r requirements.txt

Usage

# Run the Jupyter Notebook to preprocess data and visualize similarity
jupyter notebook GOT.ipynb

Dependencies

Python 3.x

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

t-SNE or UMAP (for dimensionality reduction)

Results

The project outputs:

A similarity matrix of characters

A 2D/3D visualization of character clusters

A way to input a character name and retrieve the most similar ones

Future Work

Improve feature extraction with advanced NLP models (BERT, GPT, etc.)

Enhance visualization with interactive dashboards (Plotly, Streamlit)

Expand dataset to include more contextual character details


