## Business Project Proposal

### Client: 

A manager from Redfin observed that there's discussion online about Zillow performs better estimations than Redfin. The manager wants to find a way to perform better 
Single Family Housing price estimation than before.


### Question/Need:

How can we predict the house price more accurately? We can use regression models to predict the house price based on multiple important
features.

For EDA, I want to clean up the data from Redfin and gather more related hazard data as extra features to put into the regression
model. For data science model, I will adopt linear regression, polynomial regression, random forest, and some other more advanced
regression methods.

### Impact：

I want to help Redfin better predict house price in the San Francisco Bay Area.

After Redfin developing a more robust and accurate prediction system, it will help gain confidence and interests of the customer
and increase profit for the website.

### Data Description:

I want to scrape data from Redfin or Zillow. Use Redfin API. Also, I want to obtain some hazard data, e.g., the distance between the
active fault and the property, by simply calculate the distance. I can also find some foundation soil properties around the bay area
to estimate the properties' risk level under an earthquake. 

Unit of Analysis: Use regression model to predict the relationship between the characteristics of a property that has 
been sold on Redfin with the final price listed, and then use the relationship to predict a property in the test data set.

Characteristics/Features: Time on Redfin before sold, Year Built, Property type, Community, earthquake potential...

### Solution Path:

We want to increase the accuracy of the house price prediction on Redfin --> We hypothesis that understand the relationship between
house price related features with regression methods will help us to better predict the house price--> We will use the 
optimized house price to in the end increase the user number for Redfin and increase profit.

If not with Data science tools, the method would involve more labor intese aspects, for instance, without advanced method, an agent 
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
