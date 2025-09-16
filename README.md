**OVERVIEW**

In this application, you will explore a dataset from Kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a car more or less expensive. As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.


**BUSINESS UNDERSTANDING**
From a business perspective, we are tasked with identifying key drivers for used car prices. In the CRISP-DM overview, we are asked to convert this business framing to a data problem definition. Using a few sentences, reframe the task as a data task with the appropriate technical vocabulary.

The current task is to identify the primary factors that determine prices for used cars.

We first assess the situation, including noting inventory of what used cars belonging to the salesmen are preferred to be sold, assumptions that this task will ultimately aid in the sale of their used cars, and the risks, costs, and benefits of following the findings of this task.

Utilizing a dataset of over 400,000 entries outlining the characteristics of used cars, we will clean and refine the data and analyze it via data modeling techniques to determine which facets of used cars are the biggest determinants in the car's price such as brand, damage, cleanliness, year etc. We will generate graphs to visually compare different categories such as the correlation between brand and year for example.

By the end of this data analysis, the goal is for the dealership to utilize the results to increase profits, used car sales, and aid in knowing what charactersitics to highlight when attempting to make a sale to customers, all of which will increase revenue for the business.


**EVALUATION**
With some modeling accomplished, we aim to reflect on what we identify as a high-quality model and what we are able to learn from this. We should review our business objective and explore how well we can provide meaningful insight into drivers of used car prices. Your goal now is to distill your findings and determine whether the earlier phases need revisitation and adjustment or if you have information of value to bring back to your client.

Comparing Ridge Regression and Lasso Regression, Ridge Regression has better performance and is more stable.

However, Ridge Regression seems to convey around 30% price distribution. On the other hand, Lasso Regression has worse performance with Roote Mean Squared Error (RMSE) being considerably high and predictions show high margin of error.

In terms of impact to the business, most of the data categories in the dataset seem to not have a relevant effect as to what factors determine the prices of the cars. It may be beneficial to explore more categories of data to add to the dataset. Regardless, there are no noticeable problems with the data preprocessing phase.

As the use of Ridge Regression retains more variables and has better performance than Lasso, it is a better modeling technique for this task with strong predictors being odometer and the age of the car. On the other hand, the results from Lasso regression indicates that most of the data categories in the dataset are not good indicators of relation to the prices of the cars.
<img width="910" height="420" alt="image" src="https://github.com/user-attachments/assets/de601149-6119-4afa-be29-30b76f6446b5" />



**DEPLOYMENT**
Now that we've settled on our models and findings, it is time to deliver the information to the client. You should organize your work as a basic report that details your primary findings. Keep in mind that your audience is a group of used car dealers interested in fine-tuning their inventory.


**SUMMARY**

Utilizing a dataset of over 400,000 entries outlining the characteristics of used cars, we cleaned and refined the data and analyze it via data modeling techniques to determine which facets of used cars are the biggest determinants in the car's price such as brand, damage, cleanliness, year etc. We generated graphs to visually compare different categories such as the correlation between brand and year for example.

By the end of this data analysis, the dealership is able to utilize the results to increase profits, used car sales, and aid in knowing what charactersitics to highlight when attempting to make a sale to customers, all of which will increase revenue for the business.


**RESULTS**

The use of Ridge Regression was the best modeling technique, painting a picture of around 30% of the price distribution in the cars.

The use of Lasso Regression was did not perform well in terms of the age of the car and the odomoeter readings.

There are some more unique data entries that affected the results. For example, there are some outliers such as more luxurious cars with higher end price brackets. This indicates more refined data cleaning may have been needed.

Important Factors for Categories

Age of the Car – Newer cars correlate to higher prices
Odometer Reading – Higher odometer correlates to lower prices
Manufacturer – Some higher end cars have large price differences.
Fuel Type – Hybrid and electric cars correlate to higher prices.
Transmission Type – Automatic transmissions are somewhat correlated to higher prcies
Vehicle Condition – Better vehicle conditions correlate to higher prices.
What does this mean for the business?

Introduce more categories of data related to potential affect to car prices
In tandem with this, better data cleaning may be needed such as sensitivity to outliers (luxury car brands)
Observe combinations of multiple factors, some can be derived logically such as the age of the vehicle correlating to the odometer reading.
What to focus on for higher profits

Newer Cars
Lower Odometer Readings
Be Cognisant of outlier models such as exotic/luxury cars
Hybrid and electric cars are considered high end and premium
Better physical conditions of the car
