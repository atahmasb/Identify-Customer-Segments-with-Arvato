# Identify customer segments with Arvato

This project is a part of Udacity Data Science Nanodegree. In this project AZ Direct and Arvato Financial Solutions have provided two datasets one with demographic information about the people of Germany, and one with that same information for customers of a mail-order sales company. We apply unsupervised learning techniques on demographic and spending data for a sample of German households. We preprocess the data, apply dimensionality reduction techniques, and implement clustering algorithms to segment customers with the goal of optimizing customer outreach for a mail order company.

We look at relationships between demographics features, organize the population into clusters, and see how prevalent customers are in each of the segments obtained.

We are not allowed to publish the data provided by Arvato Financial Services due to the terms and conditions. In the notebook you can find the code and the analysis that I perfomed on the datasets. 


# Installation

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

# File Descriptions

**Identify_Customer_Segments.ipynb**

Jupyter Notebook divided into sections for completing the project. The notebook provides more details than the outline given here.


# Data

* Udacity_AZDIAS_Subset.csv: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
* Udacity_CUSTOMERS_Subset.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
* Data_Dictionary.md: Detailed information file about the features in the provided datasets.
* AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. We use this information to cluster the general population into groups with similar demographic properties. Then, we see how the people in the customers dataset fit into those created clusters. The hope here is that certain clusters are over-represented in the customers data, as compared to the general population; those over-represented clusters will be assumed to be part of the core userbase. This information can then be used for further applications, such as targeting for a marketing campaign.




# Licence
Feel free to use the code and let me know if the model can be improved. If you would like to do further analysis, it is available below under a [Creative Commons CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/) license.
 
