# Creating Customer Segments with Arvato

<img src="/Image/arvato.png" width="300">

This projects with real-life data provided to us by our Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. We will use unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, we will also need to assess and clean the data in order to convert the data into a usable form.

*Note about data*: the data cannot be included since it is proprietary and needs to be removed from personal machines after use.

#### The main focus of this project is:
- Cleaning messy data by removing extreme outliers, creating NaN thresholds, and visualizing missing values.
- Encoding and Feature Engineering.
- Transforming data (imputing, scaling, etc.) to be used in the PCA algorithm.
- Reducing dimensions using PCA and selecting number of components to keep.
- Using KMeans to cluster both customer and general population into groups.
- Interpretting results and concluding which population features to focus on for sales.

#### Requirements to run this project:
- Seaborn, Matplotlib, NumPy, Pandas, Sklearn
- Note: unless data can be downloaded, the project can't be run on a personal machine.

#### Data Dictionary:
A markdown file that contains a description of each feature in the dataset. This can be used to better understand the final results of the PCA section.
