# AI-ML Assignment – 7

## Customer Segmentation using K-Means Clustering and PCA

## Objective

The objective of this assignment is to segment mall customers into meaningful groups based on their age, annual income, and spending behavior using K-Means Clustering. Principal Component Analysis (PCA) is applied to reduce the feature dimensions to two principal components for visualizing the customer clusters.

## Dataset

The Mall Customer Segmentation Dataset is used for this assignment.

Dataset Link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

The dataset is not included in this repository. Please download it directly from the Kaggle source.

## Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Methodology

1. Loaded the Mall Customer Segmentation dataset using Pandas.
2. Displayed the first five records and examined the dataset structure.
3. Identified numerical and categorical features.
4. Checked for missing values.
5. Removed the unnecessary `CustomerID` column.
6. Selected Age, Annual Income, and Spending Score as features for customer segmentation.
7. Standardized the numerical features using `StandardScaler`.
8. Used the Elbow Method to determine the appropriate number of clusters.
9. Trained a K-Means Clustering model and assigned cluster labels to customers.
10. Applied PCA to reduce the standardized data to two principal components.
11. Visualized the customer clusters using scatter plots and PCA.

## Results

The Elbow Method was used to identify the optimal number of clusters for the K-Means model. The customers were successfully divided into distinct groups based on their demographic and spending characteristics.

The cluster analysis provides insights into different types of customers, including groups with different combinations of age, annual income, and spending behavior. The PCA visualization makes it easier to observe the separation and distribution of these customer groups in two dimensions.

The results can help businesses understand customer behavior and develop targeted marketing strategies for different customer segments.

## Conclusion

Customer segmentation using K-Means Clustering successfully grouped mall customers according to similarities in their age, annual income, and spending behavior. The segmentation can help businesses identify valuable customer groups, personalize marketing campaigns, design suitable offers, and improve customer retention. PCA was used to reduce the feature space to two dimensions, making the resulting clusters easier to visualize and interpret. However, K-Means requires the number of clusters to be selected in advance and can be sensitive to initialization and feature scaling. Overall, the combination of K-Means Clustering and PCA provides a useful approach for exploring customer behavior and supporting data-driven marketing decisions.
