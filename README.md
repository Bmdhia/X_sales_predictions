![Sale](https://github.com/Bmdhia/sales_predictions/assets/136000177/c56c90d7-eee6-45fd-9f19-9f2c30abc698)
# Sales predictions
This project will be a sales prediction for food items sold at various stores

Dhia Ben Marzouk

### The objective of this is to assist the retailer in comprehending the characteristics of products and stores that have significant impacts on boosting sales.

Data Source :


Click [ here ](https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view) to download the data

 
 For this dataset, there were 8523 rows and 12 columns.

 Data Dictionary :

![image](https://github.com/Bmdhia/sales_predictions/assets/136000177/3767d344-947d-43bd-988d-180b5337c5be)


### To prepare this data, the data was cleaned, and the following processes were performed:

#### Exploratory Data Analysis

![download](https://github.com/Bmdhia/sales_predictions/assets/136000177/86a50149-9fe8-4b5a-a983-f47655fcc812)

This histogram shows that the majority of the sales are around $2000.

#### Exploratory Data Analysis

![download](https://github.com/Bmdhia/sales_predictions/assets/136000177/c9aafaae-3d3b-485c-9e26-2afb5d63db36)

The top three most consumed item type are as follows :

Fruits and Vegetables :  ``` 1232 ``` 

Snack Foods : ``` 1200 ```

Household : ``` 910 ```

The bottom three less consumed item type are as follows : 

Seafood : ``` 64 ```

Breakfast : ``` 110 ```

Starchy Foods : ``` 148 ```

## Maching Learning Using the Following Models:

- Linear Regression Model
- Decision Tree Regressor Model
- Tuned Decision Tree Regressor Model

## Models Evaluated & Results:

- Linear Regression Model (Testing Set):

  R^2: 0.57

  RMSE: 1092.69

- Decision Tree Regressor Model (Testing Set):

  R^2: 0.21

  RMSE: 1474.08

- Tuned Decision Tree Regressor Model (Testing Set):

  R^2: 0.595

  RMSE: 1057.39

The Final Model Chosen was a Tuned Decision Tree Regressor Model with the max_depth tuned to 5 , min_samples_leaf tuned to 4 and min_samples_split tuned to 2

For the testing set on the model, 59.5% of the variance in y was explained by x.

The Root Mean Squared Error had a calculation of $1057.39.

#### 🎆 Using this model to predict item outlet sales may have limitations, as indicated by an R^2 score of 0.595 and an RMSE of 1057.39, suggesting a noticeable disparity in performance metrics.

# Recommendations :
- I recommend to fine-tune input features, adjust model parameters, or explore other regression techniques to to achieve more reliable and precise predictions for item outlet sales.

# Limitations & Next Steps : 

- The way the model works now,might not completely understand all the details of how sales predictions work. This could be because some important things are missing from the information we're giving it. So we need to experiment with different ways to help the model understand sales data better, like adding more information to the data to see if that makes it work even better.

# For Further Information
For any additional questions, please contact:

Dhia Ben Marzouk

adresse.de.dhia@gmail.com
