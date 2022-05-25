# food-sales-predictions

### Project 1
This is my first project in the Coding Dojo Data Science Fundamentals and Machine Learning Course. As I progress though the course I will be adding layers to this project with my new skills.

- Part 1: Importing libraries and dataframe
- Part 2: Explore data and imputing missing values
- Part 3: Exploratory visualizations
- Part 4: Explanitory visualizations
- Part 5: Prepare data for machine learning

# Predict Item Sales to Drive Profit
## Machine Learning Model Transforming Item Data into Sales

**Author**: Brian Lafferty

### Business problem:

Transfering raw descriptive data about a product and turning it into a prediction model for item sales.


### Data
Over 8500 item oberavtions from many different store outlets. Data included information about the product (weight, fat content, category, etc.) and sales establishment infomation (size, type, etc.).


## Methods
- Data cleaned and prepared using imputing and category standaraization strategies.
- Visualization of data to explore and find underlying trends.
- Analyized data using multiple machine learning models to optimize results.

## Model
The Machine Learning Model selected for this project was a Regression Tree. This model preformed best with the data when compared with a Linear Regression model. The Regreesion Tree had a R^2 value above 0.996 when working with the test data.

## Results

![sample image](fig1.png)

> Identified categories with opportunity for growth and product segmentation.

#### Key Heatmap Correlations
![sample image](fig2.png)

> Using provided data I created an additional column of Unit_Sold. This information improves data analysis and model preformance.

#### Regression Tree Metrics

> - The Mean Squared Error is 45.38. This shows that the models average error is $45.38 per item prediction. The average value of Item_Outlet_Sales is $2181.29, so the error represents approximately 2% of the total sales.
> - The model can predict the Item_Outlet_Sales target within $100 dollars 88.64% of the time.
> - The model had 7 predictions that were over $500 off of the actual value. That represents approximately .5% of the predictions.
> - 50% of the values had predictions less than $21 from the actual value.

## Recommendations:




## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**
