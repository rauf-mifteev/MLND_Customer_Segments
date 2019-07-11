# Creating Customer Segments Project for Udacity Machine Learning Engineer Nanodegree

## Project overview

This is Creating Customer Segments project for Udacity Machine Learning Engineer Nanodegree. In this project I apply unsupervised learning techniques on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data.
* First, I explore the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. 
* Then, I preprocess the data by scaling each product category and then identifying (and removing) unwanted outliers. 
* Afterwards, I apply **Principle Component Analysis** (PCA) transformations to the data and implement **Gaussian Mixture Model** (GMM) clustering  algorithm to segment the transformed customer data using **Silhouette coefficient** to choose the number of clusters. 
* Finally, I compare the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.

## Prerequisites

The code is **Python** in a **Jupyter Notebook** and it uses:

* [SciKit-learn](https://scikit-learn.org/stable/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [NumPy](http://www.numpy.org/)

You can install everything you need to run this project with [Anaconda](https://www.anaconda.com/).

## Installing
Clone this repository:

`git clone https://github.com/rauf-mifteev/MLND_Customer_Segments.git`

## Run the Code
Navigate to the cloned directories location and start jupyter notebook with costomer_segments.ipynb:

`jupyter notebook customer_segments.ipynb`
