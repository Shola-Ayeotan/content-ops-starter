---
title: 'eCommerce Recommendation System '
slug: case-study-1
date: '2023-10-24'
excerpt: >-
  This project developed a recommendation system for an eCommerce platform using
  a Graph-based approach to recommend products based on user purchases and
  search history. 
featuredImage:
  url: /images/Ecommerce.webp
  altText: eCommerce
  styles:
    self:
      borderRadius: large
  type: ImageBlock
bottomSections: []
isFeatured: true
colors: bg-light-fg-dark
styles:
  self:
    padding:
      - pt-5
      - pl-5
      - pb-5
      - pr-5
    textAlign: left
    borderColor: border-light
    borderStyle: none
    borderWidth: 0
    borderRadius: none
    flexDirection: col
type: PostLayout
---
In this project, I developed a graph-based recommendation system tailored for an e-commerce platform. By leveraging user purchase and search history, the system enhances product discoverability, offering personalized recommendations that improve user experience and increase sales.

##### Project Objective

To create a recommendation engine that utilizes graph-based methods to suggest relevant products to users based on their historical interactions with the platform.

##### Approach

This system transforms user interaction data into graph embeddings and uses an Approximate Nearest Neighbors (ANN) model with FAISS to deliver fast and accurate product recommendations.

##### Technology Stack

*   Languages: Python, SQL

*   Libraries: pandas, DuckDB, numpy, pecanpy, gensim, plotly, UMAP, ANN, FAISS

##### Data Overview:

The dataset for this project consisted of user interaction data from the eCommerce platform, structured across 9 attributes. These attributes included user purchase and search behaviours, which were converted into a graph format for deeper analysis and modeling.

##### Approach and Methodology:

**Problem Understanding**
Researched and outlined the requirements for a graph-based recommendation system that accurately reflects user preferences and behaviours.

**Data Preparation**
Extracted and optimized relevant data from the provided dataset using pandas, numpy, and DuckDB for efficient querying and processing.

**Graph-Based Model Training: Deepwalk and Node2Vec**

*   Performed random walks on the user-product interaction graph to generate sequences for embeddings.

*   Trained Deepwalk and Node2Vec models using the gensim library to create meaningful embeddings that capture user-product relationships.

**Analysis and Visualization:**

*   Applied UMAP to reduce the dimensionality of the embeddings, making it easier to visualize and interpret product clusters.

*   Used Plotly to create interactive 2D and 3D visualizations that highlight product groupings and relationships.

**Embedding Vector Search with FAISS**

*   Initialized the FAISS library to conduct efficient similarity searches within the embedding space.

*   Implemented a recommendation system that identifies and suggests similar products based on the proximity of their embeddings in the vector space.

##### Folder Structure

*   **Model**: Contains the trained Deepwalk and Node2Vec models.

*   **Notebooks**: Jupyter notebooks documenting various stages of the project, including:

    *   Data Optimization

    *   Data Exploration and Analysis

    *   Model Training

    *   Graph Construction

    *   Result Analysis

    *   Embedding Vector Search and Recommendations

<!---->

*   Scripts: Python scripts for automation and reproducibility of the project processes.

*   requirements.txt: A file listing all necessary libraries with their specific versions to ensure compatibility.

##### Impact:

This project explored a different approach to product recommendation by combining graph theory and machine learning. The use of graph embeddings allows for personalized recommendations, leading to better user engagement and potentially higher conversion rates on the platform.
