# detecting-distracted-drivers-icp4d
This demo is created to showcase the various capabilities of IBM Cloud Pak for Data. It shows how it's possible to use a visual recognition model to detect drivers who are distracted on the road. It shows all the end to end capabilities.

The full android application can be retrived from this repo: https://github.com/anchalbhalla/detecting-distracted-driver-cloud 

## Collect 

In collect part data connections need to be created. A Data connection was created for Db2 Warehourse on Cloud. To do that the following was done: 

##### Steps
1. Create a analystics project 
2. Create a data source  
3. Add host, username, password, DB name 
4. Test connection 
5. Add connection

## Organize 

This is the task of a data engineer. In this step <b>data discovery</b> will be performed, <b>business glossary terms</b> will be added and <b>governence rules and policies</b> are added. <b>Data lineage</b> will be also be demonstrated with this. 

### Data Discovery 
Used to analyse the data quality and assign terms to the datasets and project. 

##### Steps 
1. Add the connection 
2. Select analyse data quality
3. Select assign terms
4. Click Discover
5. Assign the terms from the appropriate category 

<img src = "https://github.com/anchalbhalla/mortgage-default-prediction-icp4d/blob/master/gifs/discovery.png">

### Business Glossary 

Create a business glossary understood by everyone

##### Steps
1. Create a category
2. Create a terms
3. Save
4. Repeat 2 to 3 until done 

<img src = "https://github.com/anchalbhalla/mortgage-default-prediction-icp4d/blob/master/gifs/terms.png">

### Goverence 
Compliance to rules and policies of the industry is very important for every business 

<img src = "https://github.com/anchalbhalla/mortgage-default-prediction-icp4d/blob/master/gifs/rules.png">

### Data Lineage  
Data lineage shows the interconnection between all terms, rules and the datasets. It can seen how the terms and rules are linked to the appropriate dataset.

## Analyze

### Dashboards 
Dashboard created to show that the image dataset is varied:

### CNN Model on Notebooks 
This notebook shows how a CNN model can be created to classify images and then later deploy it as a WML (watson machine learning) model. 
....link ...

## Android Application 
Here is a demo of the final application in action
