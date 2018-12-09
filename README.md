# Identify_customer_segments_unsupervised_learning
Identifying German customer segments using Arvato Financial Services dataset

### Table of Contents

1. [Installation](#installation)
2. [Project Description](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.*. Following are the libraries used in this project.

1. pandas
2. numpy
3. matplotlib
4. ast
5. sklearn
6. torch


## Project Description<a name="motivation"></a>

A dataset on general German population with 85 different features was clustered into different customer segments using unsupervised learning(KNN). To reduce the dimensionality of the PCA was used preserving just over 80% of the variability.

Then this general population segments were compared to a data on core customer segment of a small mail order company. Then company core customer segment was compared with general population cluster to identify general population segment(s) the company should target to get maximum response.


## File Descriptions <a name="files"></a>

* Identify_Customer_Segments: This file is where all the intrepretation, manipulations on data is applied. This is were unsupervised learning is applied on the general population dataset.
* AZDIAS_Feature_Summary_custom.csv: Since all the features of the dataset was in German and custom table was made to convert them in English for easy intrepretation.

## Results<a name="results"></a>

1) I was able to categorize the general population into 15 clusters and identify the cluster(s) that match the profile of the company's core customers.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Arvato Financial Services for the data. Otherwise, feel free to use the code here as you would like!
