# Identifying-Customer-Segments

### Summary:
In this project, we will work with data provided by Bertelsmann and Arvato Finance Solution 
concerning a company that performs mail-order sales in Germany. 
The main question of interest is to identify facets of the population that are most likely to be purchasers 
of their products for a mailout campaign. The task at hand is to 
use unsupervised learning techniques to organize the general population into clusters, 
then use those clusters to see which of them comprise the main user base for the company. 
Prior to applying the machine learning methods, we will also need to assess and 
clean the data in order to convert the data into a usable form.

### Project Details:


1. Step 1: The Data
There are a number of files used for this project

- Udacity_AZDIAS_Subset.csv: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographic data.
- Identify_Customer_Segments.ipynb: Jupyter Notebook divided into sections. 


2. Step 2: Preprocessing
Creating a cleaning procedure to handle missing data, unknown values, and re-encoding.



3. Step 3: Feature Transformation
With the cleaned data, we will use dimensionality reduction techniques to identify relationships between variables in the dataset, 
resulting in the creation of a new set of variables that account for those correlations. We will use feature scaling 
and principal component analysis (PCA).


4. Step 4: Clustering
Finally, on your transformed data, we will apply clustering techniques to identify groups in the general demographic data. 
We will then apply the same clustering model to the customers dataset to see how market segments differ between the 
general population and the mail-order sales company. 
