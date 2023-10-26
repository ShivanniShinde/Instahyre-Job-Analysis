# Instahyre-Job-Analysis

# Introduction
Welcome to the InstaHyre Data Analysis and Visualization Project! We extract data from InstaHyre using Selenium, analyze it using K-means clustering, and visualize the results on a custom webpage.

# Objectives

- **Data Extraction:** Our project employs Selenium, a powerful web automation tool, to extract data from the InstaHyre website. This data includes job listings, company information, and various other relevant details.

- **Data Analysis:** To make sense of the extracted data, we implement a K-means clustering model. This model groups job listings and companies into clusters based on common characteristics, allowing users to identify trends and patterns.

- **Webpage Creation:** We've created an interactive webpage using HTML and CSS that displays the analyzed data in a user-friendly and visually appealing manner. Users can explore insights, trends, and visual representations, making data more accessible and understandable.





# K-Means Clustering

K-Means is a machine learning technique used for data clustering. It groups similar data points into clusters based on their characteristics. In our project, we used K-Means clustering to discover patterns and relationships within job listings and companies, making it easier to identify trends and insights in the data.




## Model creation
<div style="display: flex; justify-content: space-between;">
    <div style="flex: 1; margin-right: 20px;">
        <img src="https://github.com/ShivanniShinde/Instahyre-Job-Analysis/assets/143825606/c574f75d-3465-4f31-9f55-afd21deacaa6" alt="Image Description" width="350" align ='right'>
    </div>
    <div style="flex: 2;">
       <li> We employed the Scikit-learn library for K-Means clustering. Scikit-learn is a powerful machine learning library in Python, and we harnessed its capabilities to implement a K-Means clustering model. </li><li>This model groups job listings and companies into clusters based on common characteristics, enabling the identification of valuable trends and patterns in the data.</li>
        <li>Our use of Scikit-learn ensures that the clustering process is efficient and robust, allowing for meaningful insights to be extracted from the data.</li>
    
  </div>
</div>

## Evaluating Model
A Silhouette Score is a metric used to evaluate the quality of clusters in K-Means clustering or other clustering algorithms
Silhouette Score of 0.97998 indicates strong and well-separated clusters in your K-Means model.
<p align="center">
  <img src="https://github.com/ShivanniShinde/Instahyre-Job-Analysis/assets/143825606/7c238a9a-957f-4519-9153-6686ac25a39e" alt="Image Description" width="350">
</p>

## Elbow Clustering for K-Means

Elbow clustering, often used in K-Means, is a technique to determine the optimal number of clusters (k) for a dataset. It involves running K-Means for a range of k values and then looking for the "elbow point" on a plot of the cost or variance against k. The elbow point indicates the point where increasing the number of clusters no longer significantly reduces the within-cluster variance.

By applying elbow clustering, we aim to find the most appropriate number of clusters for our data, ensuring that our K-Means analysis is well-structured and provides meaningful insights.

<p align="center">
  <img src="https://github.com/ShivanniShinde/Instahyre-Job-Analysis/assets/143825606/43425f33-2f39-460f-9277-e23ddf57cb80" alt="Image Description" width="450">
</p>

## Webpage Creation

We've designed a user-friendly and visually appealing webpage to showcase the results of our analysis. This webpage was created using HTML and CSS, combining elegant design with informative content.

On this webpage, you can explore the insights, trends, and visual representations derived from our K-Means clustering analysis of InstaHyre data. Whether you're a recruiter seeking valuable talent insights or a job seeker looking to stay updated with industry trends, this webpage provides a seamless experience for data exploration.

Feel free to visit the webpage [here](http://127.0.0.1:5000/), and discover the power of data visualization in recruitment analysis.




  

