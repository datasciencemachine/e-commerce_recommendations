# E-commerce recomendation System
This repository contains the data and notebooks used to create recommendation models for an ecommerce website.

**Data**  
  
The data used to create the models is stored in the dataset directory. The datasets used are of Brazilian E-Commerce Public Dataset by Olist. 

**Notebooks**  
  
The notebooks used to create the models are stored in the notebooks directory. There are two notebooks present:

[eda.ipynb](https://github.com/datasciencemachine/e-commerce_recommendations/blob/main/notebooks/eda-on-data.ipynb) - This notebook performs Exploratory Data Analysis (EDA) on the data. The EDA analyzes the e-commerce sales on various aspects such as time of day, day of week, or payment methods used. Along with these, the EDA also analyzes the geographical division of sales over Brazil.  
[recommendation-model-for-e-commerce.ipynb](https://github.com/datasciencemachine/e-commerce_recommendations/blob/main/notebooks/recommendation-model-for-e-commerce.ipynb) - This notebook builds and tests the recommendation model. Two types of recommendation models are used: content-based filtering, collaborative filtering, and a hybrid of the two. The final recommendation model is compared to a baseline model that recommends the top 10 most popular products.
How to use
To use this repository, you will need to have the following installed:

Python 3
Jupyter Notebook
The libraries listed in the requirements.txt file
Once you have the necessary dependencies installed, you can clone the repository and open the notebooks in Jupyter Notebook.
