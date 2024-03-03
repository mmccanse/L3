# Hi - Draft - 

# Project Title: L^3:  Listing Location Learnings

## Objective
The objective of this project was to explore supervised and unsupervised models of AirBnB data from 2023. 

## Sources
- ChatGPT
- StackOverflow
- Copilot

## Method
1. **Data Selection**:
    - We utlize the same AirBnB data as our project 1 

2. **Data Preparation**:
    - Conversion of data types
    - Addressed nulls
    - Selected appropriate columns for model creation
    - Encoded and scalled
    - Removed outliers

3. **Unsupervised Learning**:
    - Created the following models: PCA & KMeans, K-Means, Birch, Agglometric
    - Used the following to assess accuracy: Elbow, cummulative variance explained, Silhouette, and Davies-Bouldin 

4. **Supervised Learning**:
    - Key learning - classification models don’t apply to continuous data.
    - First ran Random Forest Regression for availability and price, followed by Random Forest Classifier for cluster
 

## Findings
    - Successfully predicted overall ratings, clusters/segments
    - Identified feature importance for overall ratings
    - Models did not successfully predict price, 30 day availability



