# Analysis of The Effects of Drug Testing and Sex on Powerlifting 
### Authors: Alexander Straub, Anudeep Metuku
## Project code and results
https://as2032.github.io/PowerLiftingAnalysis.html

## Introduction
This Jupyter notebook is a comprehensive analysis of powerlifting performance, focusing on the effects of drug testing and sex differences. The project utilizes data from major powerlifting federations like USAPL, USPA, and IPF to investigate how these factors influence athletes' performance in the sport.

## Analysis Overview
1. **Dataset Overview:**  We begin with an exploration of the dataset, filtering and preparing it for detailed analysis.
2. **Data Visualization:** We utilize various visualization techniques, including pie charts, bar plots, and violin plots, to understand the distribution and characteristics of the powerlifting data. These visualizations offer insights into tested vs. untested lifters, the distribution of DOTS scores, and the distribution of lifters across federations.
3. **Comparitive Analysis:** We conduct a comparative study of tested and untested lifters across different federations. We also examine the performance of male and female lifters, especially in the context of weight classes and drug testing policies.
4. **Machine Learning:** We apply machine learning algorithms including RandomForest, K Nearest Neighbors, and SGD Linear Classifier, to predict testing status and sex based on performance data.

## Machine Learning Conclusions
The machine learning models demonstrate high accuracy in predicting the tested status and sex of the lifters, supporting the hypothesis of discernible performance differences between tested and untested lifters, as well as between male and female lifters.

## Dependencies and Use
To use this notebook, clone the repository and ensure you have the necessary Python packages installed:
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. scikit-learn
