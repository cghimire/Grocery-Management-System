<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Building Grocery Management System using Data Analytics</h3>

<div align="center">

</div>

## 📝 Table of Contents
- [About](#about)
- [Data Understanding and Exploring](#data_understanding_and_exploring)
- [Data Preparation](#data-preparation)
- [Data Modeling](#data-modeling)
- [Model Evaluation and Conclusion](#model-evaluation-and-conclusion)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
This project is based on real spending data for three months. Using this data we applied three techniques such as Cluster, Association, and neural network analysis. We were trying to solve following questions.

* What are the categories and stores that we frequently purchase our daily stuffs?
* How is our buying pattern and What are the items that we most likely buy together?
* How can we optimize our spending on grocery?

## 🎈 Data Understanding and Exploring <a name="data_understanding_and_exploring"></a>

![alt text](https://github.com/cghimire/Grocery-Management-System/blob/master/Grocery%20img/grocery_1.png "metadata")

**This is a metadata of the data set**.

![alt text](https://github.com/cghimire/Grocery-Management-System/blob/master/Grocery%20img/grocery_dataviz.png "Visualization")

**The above histogram represents the amount spent on different merchandise category across various stores.** 

## ⛏️ Data Preparation <a name = "data-preparation"></a>

### Clustering

I used K-means clustering to classify the data based on category, store name, items, and amount.

## 🚀 Data Modeling <a name = "data-modeling"></a>

### Association Analysis

![alt text](https://github.com/cghimire/Grocery-Management-System/blob/master/Grocery%20img/grocery_frequentItems.png "Most frequent Items")

**Above histogram shows the most frequent items in the data set**.

### Recommendation Rule

![alt text](https://github.com/cghimire/Grocery-Management-System/blob/master/Grocery%20img/recom%20rule.png "recommendation rule")     

**We created Association Rules: min support as 0.01, confidence as 0.05 and sorted with ‘high-confidence’ rule. The rules with confidence of 1  imply that, whenever the LHS item was purchased, the RHS item was also purchased 100% of the time**.

### Neural Network Model

**After splitting data set into training and testing set, I added column to each training and test data to see if the model is fit**.

![alt text](https://github.com/cghimire/Grocery-Management-System/blob/master/Grocery%20img/neural%20net.png "neural net")

**Above matrix shows that out of 59 Needs 55 were predicted correctly, and out of 21 want 20 were predicted correctly**.

## Model Evaluation and Conclusion <a name = "model-evaluation-and-conclusion"></a>

The neural net model is used to predict our spending and optimize our budget loading data for April month.

![alt text](https://github.com/cghimire/Grocery-Management-System/blob/master/Grocery%20img/neural%20net_1.png "neural net_1")

**As we can see when we purchase Red onions from Columbia Store it is classified as our Needs, meaning the Red onion is something we can’t avoid buying**.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
I would like to thank Sushil Tiwari for the contribution on this project. 
