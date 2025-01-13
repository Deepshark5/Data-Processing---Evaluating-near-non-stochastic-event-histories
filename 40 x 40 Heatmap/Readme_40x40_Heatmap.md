# Heatmap of NZ Lotteries Data
Martin La Grange, 01/2025

## Student's T-Test
The Student’s t-test is a statistical hypothesis test used to determine if the difference between the means of two groups is statistically significant. It is particularly useful for small sample sizes, typically less than 30 observations. There are different types of t-tests, including the one-sample t-test, which compares the mean of a single group to a known value, and the two-sample t-test, which compares the means of two independent groups. Additionally, there is the paired t-test, which compares the means of the same group measured at two different times or under two different conditions. The test assumes that the data are normally distributed and that the variances are equal, though there are modifications for when these assumptions are not met.

## Heatmap
A **heatmap** is a graphical representation of data that uses color to show variations in magnitude or density of a third variable in a two-dimensional plot. Typically, the x-axis represents a variable such as time or categories, and the y-axis represents another variable defining different categories in the data. Each rectangle in the heatmap corresponds to a value, with colors indicating the magnitude or density, helping to visualize patterns and changes in the data.

## Interrelation
When combining a Student’s t-test with heatmaps, the heatmap can be used to visualize the results of the t-test, making it easier to identify patterns or significant differences between groups. The heatmap can visually represent the outcomes of a Student’s t-test, showing which groups have statistically significant differences in their responses.

To use heatmaps effectively in conjunction with a Student’s t-test, it is important to follow a structured process. This includes establishing a clear goal, conducting the t-test, and then visualizing the results on a heatmap to understand the “what” and then moving to interpret the “why” through further analysis or additional data collection.

Within the examination of the historical Lottery data, the Heatmap process in the code example makes use of historical data to deliver a contrast and linkages between each ball drawn e.g. between 1 and 40, and the probability value associated with a 1 drawn at the same time as a 40.

## Contrast in Heatmaps - Random compared with Non-Random
When discussing contrasts in heatmaps, particularly the comparison between random and non-random clustering, several key points emerge:

* Random Clustering: This method does not follow a specific pattern or hierarchy. Random clustering might involve grouping data points without considering the underlying structure or similarity between the data points. This approach can be useful for exploratory analysis but may not capture the true underlying patterns in the data.

![image](https://github.com/Deepshark5/Data-Processing-1---Heatmaps-for-forecast-evaluation/blob/main/Images/Heatmap_Random.jpg)
  
* Non-Random Clustering (Hierarchical Clustering): This method involves grouping data points based on their similarity, leading to a hierarchical structure. Hierarchical clustering can be divisive (top-down) or agglomerative (bottom-up). This approach is more likely to reveal meaningful patterns and relationships within the data, making it a preferred choice for many biological and web analytics applications.

![image](https://github.com/Deepshark5/Data-Processing-1---Heatmaps-for-forecast-evaluation/blob/5daa44e0300dfa633f1aa0b6435aadf9ef50e36c/Images/Heatmap_Clusters.jpg)
  
The choice between random and non-random clustering in heatmaps depends on the specific goals of the analysis. Non-random clustering methods, such as hierarchical clustering, are generally preferred for revealing meaningful patterns in the data, while random clustering can be useful for exploratory purposes.

## Random and Non-Random Lottery Heatmaps - a Cautionary Note, relating to the T-test.

The heatmap of the lottery draw seen in this example from the last 700 draws does indicate that there is a definite lack of randomness, and that this is a function of time, and the Prior Fallcy - that is, what was in the past is affecting the future.

It is more accurate to say that these heat-mapping changes are _in flux_ - a bit like the pattern of bumps on the surface of boiling of water in a pot on a stove. There's definitely a structure, but this changes from draw to draw, and the pattern of those changes are not immediately apparent. **The caveat of using the heatmap is that it delivers a snapshot of time**, and while instructive, is not definitive beyond perhaps a single draw forward - and not even then. 

The heatmap does offer a sophistication, though. The degree of non-randomness in a ball-to-ball comparison is readily apparent, even on a small dataset. It is possible to start a heatmap at 50 datapoints, and then accumulate a series of these heatmaps in time, plotting the changing relationship of the balls over that advancing period.

Recursive and LTSM ANN's offer the possibility, when connected to Bidirectionality (to eliminate bias-drift while training) to use the heatmap data to potentially make a forecast - and with the **second caveat that, no matter how well trained, the result will very likely be catastrophically wrong !**
