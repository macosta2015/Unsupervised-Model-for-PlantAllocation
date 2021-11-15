# Google slide presentation
https://docs.google.com/presentation/d/1G5hDVTpE9ugxiBCjYR5RUd0tgay0cveqQv3zAP6ep_s/edit#slide=id.p1 

https://docs.google.com/presentation/d/e/2PACX-1vSMWcpSLPs3DvifkYxo_QMtNgjV1X_ulI8UXft8mcvgTa_NDxXXBOMSV_sQLU0er_Hzfj1YNv5Z2Cpe/pub?start=false&loop=false&delayms=3000
# GitHub



## Project Presentation

In this project we'll do a **clustering job for Mexico's flora** by creating an unsupervised machine learning model. 
The main objective is to get different groups based on some features (altitude, latitude, family, color, type) in order to have a distinct plant classification, beyond the ones that already exist based in the ecosystem biodiversity.

With the model we are developing, we expect to help UNAM's (Universidad Nacional Autónoma de México) herbarium scientists predict the allocation of different plants based on some of their main characteristics and some environmental data. Besides there are some ecosystem classifications, with this project we are going to create groups in order to obtain different locations based on the variables we choose, this new groups, will help to make predictions about plant allocation and, with other models, find relationships and correlations between this flora data and fauna information.

For the development of the project, we are working with a database created inside the herbarium with Mexico's plant recollection data. By now, we are only working with the plant datapoints, which conform a database with about 173,000 rows with 63 columns. Next, an example of the data we are going to work with:

![image](Resources/Imagen1.jpg)

![image](Resources/Imagen2.jpg)

We expect to use some of the tools learned in order to solve some questions and create the corresponding deliverables.

From the database, we are going to create some queries in order to answer the following:

1.	How many families of plants are there?
2.	How many genus of plants are there?
3.	How many species of plants are there?
4.	Which families are the most diverse? Understanding the more diverse as the ones with more genus

With this information we are going to create a heatmap for the species quantity, in this map we will also include environmental layers as soil, precipitation and weather, just to mention a few. 

## Description of the communcation protocols

To store our csv. we have planned to use AWS. 
AWS will then communicate with Jupyter notebook. 
In Jupyter notebook we will be able to use the virtual computer to cluster our data. 
Jupyter notebook will then help us plott our data so that it can be easily read. 

## Branches 
#### In order to work as a team we are using branches. With a Team of three people, we are using three branches. 


## Database 

The complete database includes 173,923 rows and 63 columns. Because we are working with an unsupervised model in order to solve a classification issue, we tried to have a balanced database getting proportional chunks of information, using the family and order columns as main filters.
