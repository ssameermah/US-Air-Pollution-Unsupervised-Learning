# US-Air-Pollution-Unsupervised-Learning

The project uses various techniques such as descriptive statistics, dimensionality reduction using PCA, Pattern Mining and Clustering using Unsupervised Machine Learning algorithms like Kmeans and Kmodes, SARIMAX was used for time series prediction of air pollutant values.

## Research Questions that are answered in the project
1.   To identify the top states with highest pollutant values for NO2, SO2, O3, CO we will be using statistical and ranking methods like mean to check the top 10 states having the highest pollutant values from year 2000 to 2016
2.   We will be using either spearman rank correlation and Pearson rank correlation to check if there is any correlation among the top 10 ranked states in US.
3.   We will be using K-means clustering to check for clustering patterns among NO2, CO, SO2, and O3. To see if there is a clustering pattern that can help us identify some insights about US Air pollution status.
4.   We will also cluster US cities accordingly and plot them on US map to visualize any findings we find. This will help us visualize the cities that are clustered together and is there any location influences air pollution.
5.   For our query to check if the regions with higher pollutant values have an effect on neighboring regions, we will we plotting the average pollutant value for:
  1.   State-wise from the year 2000 to 2016 to see the variation among all pollutants
  2.   We will be plotting monthly variation which will make us visualize the daily dispersion of air pollution values and check if there is a neighboring effect which we strongly believe that it should be the case.
6.   We will be using Regression to predict pollutant value and multi regression to check the strength of the pollutant variable (dependent in this case) and other independent values.
7.   We will be doing a time series analysis to check if there is a seasonal pattern for air pollutant values.

## Findings

**Air pollutant trends**

<img width="559" alt="image" src="https://user-images.githubusercontent.com/46833935/168952751-035bd623-103f-4d42-ad15-52519b21ca8c.png">

We can see that there is a downward trend for all the pollutants from 2000 to 2016. This is in fact good as we can infer that United States is taking correct measures to curb down the air pollutant levels throughout the years. 

**Top pollutant states**

<img width="691" alt="image" src="https://user-images.githubusercontent.com/46833935/168952887-80edc91a-a2d3-4109-8404-ed1d0c802588.png">


**Air Pollutant values are affected by nearby regions**

![](https://github.com/ssameermah/US-Air-Pollution-Unsupervised-Learning/blob/master/july%20month%20o3.gif)

As we see when pollutant level rises in some area, the pollutant level starts rising in the nearby area. Also, when the pollutant level starts decreasing the nearby areas also reflect this change.

**City Clustering**

<img width="679" alt="image" src="https://user-images.githubusercontent.com/46833935/168952020-85186e37-b988-4709-9713-ce03e1d8555d.png">

The Map shows distribution of different cluster over US map. 
1.	We can see that cluster0 which is defined by Color Red, has the majority points in East Coast. There is a neighboring effect on this cluster and through this study we know that the air pollutant values for the east coast is a bit higher.
2.	Cluster1 defined by Color Violet is scattered across entire US. 
3.	Similarly, Cluster2 defined by Light Blue Color is scattered across US like Cluster1.
4.	Finally, Cluster3 defined by Green Color is mostly falling on West Coast.

**Moreover, Cluster 0 denoted by Red**
1.	Has 2nd Highest average NO2 AQI values (less than Cluster 3)
2.	Highest average O3 AQI values
3.	Highest average SO2 AQI values
4.	Has 3rd Highest average CO AQI values (less than Cluster 2 and Cluster 3)

**Cluster 1 denoted by Violet**
1.	Has Lowest average NO2 AQI values
2.	Has 2nd Highest average O3 AQI values (less than Cluster 0)
3.	Has Lowest average SO2 AQI values
4.	Has Lowest average CO AQI values

**Cluster 2 denoted by Light Blue** 
1.	Has Highest NO2 AQI values
2.	Has 3rd Highest O3 AQI values
3.	Has 3rd Highest SO2 AQI values
4.	Has 3rd Highest CO AQI values

**Cluster 3 denoted by Green**
1.	Has 3rd Highest NO2 AQI values
2.	Has Lowest O3 AQI values
3.	Has 2nd Highest SO2 AQI values
4.	Has Highest CO AQI values






