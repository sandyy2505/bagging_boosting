# bagging_boosting
Ensemble Techniques : Bagging Classfiier, Boosting Classifiers, AdaBoost, Gradient Boosting, XGBoost, Stacking, Hyperparamter tuning

# Background and Context

You are a Data Scientist for a tourism company named "Visit with us". The Policy Maker of the company wants to enable and establish a viable business model to expand the customer base. A viable business model is a central concept that helps you to understand the existing ways of doing the business and how to change the ways for the benefit of the tourism sector. One of the ways to expand the customer base is to introduce a new offering of packages.
Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information.
The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being. However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

You as a Data Scientist at "Visit with us" travel company has to analyze the customers' data and information to provide recommendations to the Policy Maker and Marketing Team and also build a model to predict the potential customer who is going to purchase the newly introduced travel package.

# Objective

To predict which customer is more likely to purchase the newly introduced travel package.

# Data Dictionary

### Customer details:

CustomerID: Unique customer ID
ProdTaken: Product taken flag
Age: Age of customer
TypeofContact: How customer was contacted (Company Invited or Self Inquiry)
CityTier: City tier
Occupation: Occupation of customer
Gender: Gender of customer
NumberOfPersonVisited: Total number of person came with customer
PreferredPropertyStar: Preferred hotel property rating by customer
MaritalStatus: Marital status of customer
NumberOfTrips: Average number of the trip in a year by customer
Passport: The customer has passport or not
OwnCar: Customers owns a car flag
NumberOfChildrenVisited: Total number of children visit with customer
Designation: Designation of the customer in the current organization
MonthlyIncome: Gross monthly income of the customer

### Customer interaction data: 

PitchSatisfactionScore: Sales pitch satisfactory score
ProductPitched: Product pitched by a salesperson
NumberOfFollowups: Total number of follow up has been done by sales person after sales pitch
DurationOfPitch: Duration of the pitch by a salesman to customer
