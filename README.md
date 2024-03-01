# Penguin Data Analysis and Clustering

`Author:` [Kaíque Freire dos Santos]<br>
`Date:` [2024/02/29]

This notebook performs an exploratory analysis and clustering of a penguin dataset using unsupervised machine learning techniques. The dataset used is available in the `penguins.csv` file.

## Goal
The main objective is to better understand the characteristics of penguins and identify possible groups or patterns present in the data.

## Project steps

1. **Importing and Reading Data:** Initially, the necessary libraries are imported and the data is read from the CSV file.

2. **Exploratory Data Analysis:** Several stages of exploratory analysis are carried out, including:
    - Visualization of the first and last lines of the data set.
    - Statistical description of the data.
    - Checking information about the dataset, such as data types and count of non-null values.
    - Treatment of missing values and unnecessary records.
    - Graphical visualizations for analyzing counts and distributions.

3. **Data Pre-processing:** In this step, data is pre-processed to improve quality and consistency, including:
    - Categorization of variables.
    - Standardization of variable values to place them on the same scale.

4. **Dimensionality Reduction:** Using the PCA (Principal Component Analysis) technique, data is reduced to just two dimensions, facilitating visualization and interpretation.

5. **Determining the Number of Clusters:** The Elbow method is used to determine the ideal number of clusters, allowing for more accurate clustering.

6. **Clustering with KMeans:** Clustering experiments are carried out with different numbers of clusters, using the KMeans algorithm. Clusters are visualized in scatter plots to better understand the patterns found in the data.

## Results

The final results include the identification of penguin clusters and the visualization of data grouped according to the identified clusters. These results can provide valuable insights into the distribution and characteristics of penguins present in the dataset.

## Next steps

This project can be expanded and improved in several ways, such as:
- Explore other clustering algorithms.
- Experiment with different data preprocessing techniques.
- Carry out a more detailed analysis of the characteristics of each identified cluster.
- Apply cluster validation techniques to evaluate the quality of clusters.

For more details on the implementation and results, see the notebook above.
