# sales_predictions
## Analysis of grocer sales data to identify market trends and predict sales volumes.
Author: Andrew Lackey
### Accurate predictions of sale volumes:
Food supply requires stocking perishable goods in the right quantities to move goods to customers without overstocking wildly and having product spoil. Creating a model that accurately predicts necessary sales volume is critical to running a profitable venture in this industry.
### Data:
[Data can include source and high-level description (e.g. # obs)](https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/)
The data is from the Big Mart Sales Practice Problem set on datahack and gives descriptive data about various features of grocery chain logistics. e.g. item weights, prices, visibility, type, and information about the store in which they were sold.

## Methods
* Data processed to impute or remove erroneous data or missing records.
* Data trends explored by creating correlations and visualizations of those correlations.
* Linear regression and decision tree regression applied to the (split for training/testing) data set to create predictive models for the sales volumes

## Results
### Visualizations of identified trends as well as data peculiarities

Correlation between price and sales
![image](https://user-images.githubusercontent.com/25378587/172199998-d74e360e-681e-45a7-b1b0-96dc665ff5a0.png)

The nearly uniform distribution of weight amongst types.
![image](https://user-images.githubusercontent.com/25378587/172199944-4c03469e-c865-4c41-9b98-48b6c35a9a86.png)

## Model
The most accurate predictive model used was a decision tree regressor which resulted in a RMSE of ~1000 for a field with a mean of ~2200, and an R2 fit to the testing split of 0.6 which, while leaving room for improvement, gives a good first step prediction of expected sales considering the range was 33 to 8500. 

## Recommendations:
Running a more variable model might give us further improved results as the distinct skewing of the numbers by some categorical store data seems to have been an issue.

### For further information
For any additional questions, please contact ajlackey8@gmail.com

![image](https://user-images.githubusercontent.com/25378587/172199927-710442e4-b103-42e5-9cef-37e5a1cbe7db.png)
