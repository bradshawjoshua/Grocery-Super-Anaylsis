# Deploy Regression Models to Predict GrocerySuper's Future Sales
## Comparing Predictive Models to Improve Company Earnings

**Author**: Joshua J. Bradshaw 

### Business problem:

* Executive has provided a data set with $18.6+M in earnings from the last year, he would like to know more information on how to improve the companies performance for the next fiscal year.


### Data:
* The distribution of the Executive's Item Outlet Sales is $1,794, with Medium Outlet Sized Stores performing better than High and Small.
* The Medium Outlet Sized Stores are bucketed primarily as Supermarkets Type2 and Type3, with Small Outlet Sized Stores showing higher instances of Grocery Store and Supermarket Type1 for Outlet Type.
* Decision Tree Model performed slightly better than Linear Regression after tuning and optimization.

## Methods
* Conducted data cleaning and exploratory analysis on the data set to help identify which outlet size performed the best.
* Used machine learning models to identify and predict overall store sales.
  * Linear Regression
  * Decision Tree
* Deployed a Linear Regression Model, then attempted to improve my model's performance by optimizing it using a Decision Tree Model


## Results
Outlet Size Sales
* High: $2.14+M
* Medium: $7.48+M
* Small: $4.56+M
* Missing: $4.39+M

Linear Regression Metrics
  * R2 Train: 56%
  * R2 Test: 57%
  * RMSE Train: $1,139
  * RMSE Test: $1,093

Decision Tree Metrics
  * R2 Train: 60%
  * R2 Test: 59%
  * RMSE Train: $1,082
  * RMSE Test: $1,057

### Here are examples of how to embed images from your sub-folder

#### Visual 1 Title
![image](https://user-images.githubusercontent.com/83310016/176863869-1b48ed04-eaf0-426b-9a1a-2c31a6637f32.png)


> Sentence about visualization.

#### Visual 2 Title

## Model
* At first, the model's coefficient determination (R2) was performing poorly, displaying underfit and high bias. After hyperparameter tuning the Decision Tree Model, it ended up performing the best with:
* The model is making an average error of $1,057 on the test data. The RMSE is punishing those large errors with a worse score. An R2 Score of 59% means that the Decision Tree Model can explain 59% of the variation in the sales target. Overall, RMSE is better when lower and R2 Score is better when its closer to 100%.

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**
