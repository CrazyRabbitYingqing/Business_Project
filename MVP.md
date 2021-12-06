## Business Project Minimum Viable Product

### Client: 

A construction company (specializing in residential housing) at Austin, Texas starts thier financial planning for the next year.
The manager of the financial department want to know the recent house price around the Austin area as an important factor for estimating the construction budget.


### Question/Need:

Qestion: How can we predict the house price? 

Need: House prices for houses in Austin, Texas and features related, i.e.,house location, bedroom numbers, garage spaces etc. 

### Impact：

When the contruction company get the listing house price, an estimation of the construction cost will be determined. Therefore, the financial department will
have a reliable source for planning budget for construction supply that will not be wasteful or shortage for the projects. 
This solution for evaluating company budget will be more efficient and accurate, which I will discuss in the "alternate Solution Path" Section. 

### Data Description:

I will use a data set from Kaggle about the listing house price in Austin, Texas:
https://www.kaggle.com/ericpierce/austinhousingprices?select=austinHousingData.csv

The data set contains ~10000 rows and ~47 columns.

Unit of Analysis: Use regression model to predict the relationship between the characteristics of a property that has 
been sold on Redfin with the final price listed, and then use the relationship to predict a property in the test data set.

Characteristics/Features: Time on Redfin before sold, Year Built, Property type, Community, earthquake potential...

### Solution Path:

We want to increase the accuracy of the house price prediction on Redfin --> We hypothesis that understand the relationship between
house price related features with regression methods will help us to better predict the house price--> We will use the 
optimized house price to in the end increase the user number for Redfin and increase profit.

Alternate Solution Path: If not with Data science tools, the method would involve more labor intese aspects, for instance, without advanced method, an agent 
will have to recognize a similar property with browsing the data set or website to produce an estimation which will be not efficient
and accurate. Therefore, advanced method is more desired in this case.

### Criteria for Success:

Check the optimized regression model will predict house price well with the test data set.
I also want to check if the house price prediction accuracy increases will help with the website profit( I
havn't thought of a way to figure out data).

### Assumptions and Risks:

Assumptions: Increase the accuracy of house price prediction will increase the website usage rate.
Risks: The help from increasing the accuracy of house price prediction is little to the website usage rate. If so,
       the efforts are in vain.
### Tools:

I will use python libraries for data exploratory studies.
I will use python machine learning libraries for regression analysis. Yes. I want to try out as many as regression
tools to compare the results.

MVP Goal:
In the MVP, I will show the first regression model results and validate the model with some test data.
