# Project Title: L^3:  Listing Learning Labyrinth

## Objective
The objective of this project was to explore supervised and unsupervised models of AirBnB data from 2023. 

## Sources
- ChatGPT
- StackOverflow
- Copilot

## Team Contributions
- Meredith focused on data transformation and random forest models.
- Jennifer led the data analysis and modeling efforts.
- Sonja handled business analysis and posed critical questions for further research.
- The entire team was involved in data preparation, model experimentation, and problem-solving.

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

5. **Optimization**: 
Please see the following excel for detail list of how we optimize the model:  [Analysis process, files to use](https://github.com/mmccanse/L3/blob/main/Analysis%20process%2C%20files%20to%20use.csv)

## Executive Summary
This project aims to analyze the Denver AirBnB landscape to identify patterns and make recommendations for property owners. By leveraging machine learning techniques, we segmented Denver AirBnB properties, predicted their ratings, availability, and identified key features influencing overall ratings.

## Findings
- Successfully predicted overall ratings, clusters/segments
- Identified feature importance for overall ratings
- Models did not successfully predict price, 30 day availability

## Next Steps

Further analysis on non-contributing features and the potential of text data utilization.

Enhanced cluster analysis to refine property segmentation.

Exploration of additional predictive models to improve accuracy in price and availability predictions.

## Credits
This project was made possible through the dedicated efforts of the team and the use of resources provided by Inside Airbnb, Slidesgo (presentation template), Flaticon (icons), and Freepik (infographics & images).



