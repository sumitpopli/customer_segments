# Customer Segments #
Use unsupervised training techniques to look at relationships between demographic information about the people and customers of a mail-order sales company.

## Description: ##
Customer has provided two datasets one with demographic information about the people, and one with that same information for customers of a mail-order sales company. This project looks at relationships between demographics features, organize the population into clusters, and see how prevalent customers are in each of the segments obtained.

## This project implements: ##

**Preprocessing:**
*  Missing or unknown values encoded properly in the data 
*  Features (columns) that should be removed from the analysis because of missing data
*  Consider the level of measurement for each feature in the dataset (e.g. categorical, ordinal, numeric).  
*  Features that need to be re-encoded before they can be used
*  Features that can be dropped 
*  Create a cleaning procedure that will apply first to the general demographic data, then later to the customers data.

**Feature Transformation:**

* Use dimensionality reduction techniques to identify relationships between variables in the dataset, resulting in the creation of a new set of variables that account for those correlations. 
* Feature scaling. 
* Apply principal component analysis (PCA) to find the vectors of maximal variability. Figure out how much variability in the data does each principal component capture
* Interpret associations between original features in your dataset based on the weights given on the strongest components
* Determine components to retain as part of the dimensionality reduction process

**Clustering**

* Apply clustering techniques to identify groups in the general demographic data. 
* Apply the same clustering model to the customers dataset to see how market segments differ between the general population and the mail-order sales company.
* Use the k-means method to cluster the demographic data into groups. 
* Compare the distribution of people by cluster for the customer data to that of the general population. 

