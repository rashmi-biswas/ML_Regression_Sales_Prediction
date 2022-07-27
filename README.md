<h1 align="center"> RETAIL SALES PREDICTION </h1>
<p align="center"> 
  <img src="Images/rossmann store.png" alt="rossmann store.png" width="500px" height="300px">
</p>

<h2> :book: Introduction</h2>

A major challenge for large retailers is to address the needs of the consumers more effectively on a local level, while maintaining the efficiencies of central distribution. As the demand for mass customization by consumers grows, methods focused on store level optimization increase in value.
Prediction of sales is an important application of machine learning in the retail space. Given accurate predictions, retailers can manage dynamic pricing, staff rostering and inventory so as to maximize profit and improve the customer experience. 

<p>
An accurate forecast of sales allows retail outlets to answer questions such as:
<li>Can we use dynamic pricing to maximize our profit?</li>
<li>Do we have enough stock to satisfy demand without being overstocked?</li>
<li>What are the most important factors that affect sales, and how can we optimize them?</li>
<p>

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Problem Statement</h2>

Data provided by Rossmann gives various information of about 3,000 drug stores in 7 European countries. Currently, Rossmann store managers were tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

We are provided with historical sales data for 1,115 Rossmann stores. Our task is to forecast the "Sales" column for the test set with the help of given datasets.

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Data Description</h2>

This dataset was originally used in a [Kaggle competition](https://www.kaggle.com/c/rossmann-store-sales)
The dataset contains information about the stores and its sales. Two datasets are provided.
<li>stores_data.csv - historical data including Sales</li>
<li>store.csv - supplemental information about the stores</li>

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Setup</h2>

All code for this project is written in [Python 3](https://www.python.org/downloads/). The list of dependencies can be found in `requirements.txt`. To set up your development environment, navigate to this repository and run the following on a terminal:

```
$ pip install -r requirements.txt
```

The `data/` directory contains all data files downloaded from Kaggle. The `plots/` directory contains all plots generated and all output files are recorded in the `predictions/` directory.

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Approach</h2>
<li>Loading our dataset and importing all the useful libraries</li>
<li>Data preprocessing and Feature Engineering</li>
<li>Scaling numeric features to a (0,1) range</li>
<li>Exploratory Data Analysis</li>
<li>Merging of Datasets</li>
<li>Encoding of categorical columns as one hot vectors</li>
<li>Feature Selection</li>
<li>Standardization of features</li>
<li>Machine Learning Data Modeling (for our Prediction)</li>

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Algorithms Used</h2>
<li>Linear Regression</li>
<li>XGBoost Regressor</li>
<li>Decision Tree</li>
<li>Random Forest</li>

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Conclusion</h2>
<li>Out of the four methods, Random Forest proved to be most accurate, achieving a R2_Score of 0.986449, MAE of 270.752379 and RMSE of 449.331705. </li>
<li>So, now we can say that the Rossmann store person can now implement the Random Forest Model and utilize the feature importance data for predicting the sales for next six months. </li>

![downloadnn](https://user-images.githubusercontent.com/92808101/177403088-d8cf9f58-af05-44a1-aa41-ed73de5a1ca9.png)
