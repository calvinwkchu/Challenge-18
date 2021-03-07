# Cryptocurrency Challenge

## Overview

The point of the exercise is to clean the given dataset where we will then use unsupervised learning to split out clusters of data and plot those clusters on graphs.

## Deliverable 1

Cleaned the given dataset by filtering out currently trading currencies, removed any null/missing rows of data and converted columns with string values to numerical ones using encoding i.e. splits up the columns into boolean comparatives of labels.

## Deliverable 2

Given the cleaned dataset in deliverable 1, we further shrink the number of features using the PCA model down to three components. We then use the results to create a new dataframe.

## Deliverable 3

We first evaluate the dataset in deliverable 2 using KMeans to find out optimal cluster values and classify the data based on those clusters using unsupervised machine learning. We then combine with prior dataset in deliverable 1 for a complete dataframe. 

## Deliverable 4

Using the combined dataset, we graph our results based on the three PCA components and the clusters assigned. We also rescale the two other variables in totalcoinsupply and totalcoinsmined, to create a new dataframe and plot those against each other to determine if there are additional relationships to be aware of (along with the previously assigned classes).