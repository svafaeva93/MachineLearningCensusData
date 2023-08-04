# MachineLearningCensusData

Project 4 Proposal: Population Classification based on Canada’s Census Data

Project Description: 

Use Canada  census data to segment customers based on demographics and make  predictions. We will be forming clusters based on demographics of people in Canada (socioeconomic status) and using this to gather valuable insights for future sales of products/services. 

Technologies: python, machine learning, tableau, sql, pandas

Database: Statistics Canada 

Question we are interested in: 
Clustering nationwide and provincewide data based on income; Features we are interested in are education, age, population and dwelling counts, income; 

Demographic segmentation is the process of dividing a population into distinct groups or segments based on specific demographic characteristics. These characteristics can include age, gender, ethnicity, education level, occupation, income, marital status, and more. The goal of demographic segmentation is to identify meaningful patterns and differences within a population that can aid in understanding the behavior, preferences, and needs of different subgroups.

In the context of using census data for demographic segmentation in Canada, we have access to a vast dataset containing information about the entire Canadian population. This data includes various demographic features for each individual or household, such as age, gender, ethnicity, education level, employment status, and more. By employing clustering algorithms and unsupervised learning techniques, we can group individuals or households based on their similarities in these demographic attributes without any predefined labels.

Tasks: 
Data Emgineering: cleaning, merging datasets 
Machine Learning: Unsupervised learning, PCA 
Visualizations will be made with Tableau, having several dashboards and a story.

Group Members and tasks each will do: 
Taruna - look for datasets, ETL, perform machine learning algorithms once data is prepared  
Shakhnoza  - ETL, Tableau
Riley -  check ETL, and machine learning model, presentation, data analysis
Samita -  READme, data engineering, data engineering tableau dashboard/story


Data Engineering Steps: 

1. read csv
2. filter for "Country"
3. get the maximum levels for details in a list (hierarchy)
4. Add the level columns in the dataframe
5. populate initially based on levels
6. populate the dessendents/ below level hierarchy 
7. export the output/dataframe 

Machine Learning: 

1. Standard scaler module
2. Kmeans algorithm for clusters
3. PCA components for clusters
4. Sub clusters
5. PCA for sub clusters
6. K3mix

Tableau:
1. Visualizations of machine learning outcomes
2. Presentation stories