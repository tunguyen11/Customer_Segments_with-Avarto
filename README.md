
# Overview 
This project belong to the unsupervised learning project of Udacity Data Scientist Nano Degree. 
AZ Direct and Arvato Financial Solutions provided two datasets with demographic, finance and consumption behaviors information. 
One is the survey of population in Germany, and one with the same information for customers of a mail-order sales company. 
I apply unsupervised learning techniques on demographic and spending data for a sample of German households. I preprocessed the data, applied Principal Component Analysis for dimensionality reduction, and implemented KMeans clustering algorithms to segment customers with the goal of optimizing customer outreach for a mail order company.

# Install 
* Jupyter Notebook
* Python 3 
* sklearn, Pandas, Numpy, seaborn, matplotlib

# Data 
* Udacity_AZDIAS_Subset.csv: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns). 
* Udacity_CUSTOMERS_Subset.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
* Data_Dictionary.md: Detailed information file about the features in the provided datasets.
* AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. We use this information to cluster the general population into groups with similar demographic properties. Then, I see how the people in the customers dataset fit into those created clusters. The hope here is that certain clusters are over-represented in the customers data, as compared to the general population; those over-represented clusters will be assumed to be part of the core userbase. This information can then be used for further applications, such as targeting for a marketing campaign.


