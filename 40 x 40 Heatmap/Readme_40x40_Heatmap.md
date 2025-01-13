# Heatmap of NZ Lotteries Data
Martin La Grange, 01/2025

## Student's T-Test
The Student’s t-test is a statistical hypothesis test used to determine if the difference between the means of two groups is statistically significant. It is particularly useful for small sample sizes, typically less than 30 observations. There are different types of t-tests, including the one-sample t-test, which compares the mean of a single group to a known value, and the two-sample t-test, which compares the means of two independent groups. Additionally, there is the paired t-test, which compares the means of the same group measured at two different times or under two different conditions. The test assumes that the data are normally distributed and that the variances are equal, though there are modifications for when these assumptions are not met.

## Heatmap
A **heatmap** is a graphical representation of data that uses color to show variations in magnitude or density of a third variable in a two-dimensional plot. Typically, the x-axis represents a variable such as time or categories, and the y-axis represents another variable defining different categories in the data. Each rectangle in the heatmap corresponds to a value, with colors indicating the magnitude or density, helping to visualize patterns and changes in the data.

## Interrelation
When combining a Student’s t-test with heatmaps, the heatmap can be used to visualize the results of the t-test, making it easier to identify patterns or significant differences between groups. For example, in educational settings, a heatmap can be used to highlight differences in survey results between different demographic groups, such as race/ethnicity or grade level. The heatmap can visually represent the outcomes of a Student’s t-test, showing which groups have statistically significant differences in their responses.

To use heatmaps effectively in conjunction with a Student’s t-test, it is important to follow a structured process. This includes establishing a clear goal, conducting the t-test, and then visualizing the results on a heatmap to understand the “what” and then moving to interpret the “why” through further analysis or additional data collection.

## Contrast in Heatmaps - Random compared with Non-Random
When discussing contrasts in heatmaps, particularly the comparison between random and non-random clustering, several key points emerge:

* Random Clustering: This method does not follow a specific pattern or hierarchy. In the context of biological data analysis, random clustering might involve grouping data points without considering the underlying structure or similarity between the data points. This approach can be useful for exploratory analysis but may not capture the true underlying patterns in the data.

![image](https://github.com/Deepshark5/Data-Processing-1---Heatmaps-for-forecast-evaluation/blob/main/Images/Heatmap_Random.jpg=400x250)
  
* Non-Random Clustering (Hierarchical Clustering): This method involves grouping data points based on their similarity, leading to a hierarchical structure. Hierarchical clustering can be divisive (top-down) or agglomerative (bottom-up). This approach is more likely to reveal meaningful patterns and relationships within the data, making it a preferred choice for many biological and web analytics applications.

![image](https://github.com/Deepshark5/Data-Processing-1---Heatmaps-for-forecast-evaluation/blob/5daa44e0300dfa633f1aa0b6435aadf9ef50e36c/Images/Heatmap_Clusters.jpg=400x250)
  
* ClusterExperiment Package: The clusterExperiment package in R provides tools for comparing different clustering methods, including the ability to plot heatmaps that show significant genes per contrast. The plotContrastHeatmap function within this package can be used to visualize contrasts in gene expression data, where the clustering method (random or hierarchical) can influence how the data is grouped and presented.
* Interactive Clustered Heat Map Builder: This tool allows users to generate heatmaps with different clustering options, including hierarchical clustering. It provides a user-friendly interface for transforming and filtering data, making it accessible to those without extensive bioinformatics or statistical expertise.
* Color Contrast in Heatmaps: When creating heatmaps, choosing the right color palette is crucial. Sequential color scales are effective for showing raw data values (all non-negative), while diverging scales are better for standardized data that includes both up-regulated and down-regulated values. Ensuring color contrast is also important for accessibility, especially for users with color vision deficiencies.

In summary, the choice between random and non-random clustering in heatmaps depends on the specific goals of the analysis. Non-random clustering methods, such as hierarchical clustering, are generally preferred for revealing meaningful patterns in the data, while random clustering can be useful for exploratory purposes.

A Random 
