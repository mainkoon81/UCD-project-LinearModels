# Linear-Model-project (R or SAS or Alteryx)

### [Contents] 

__Lab-01.__ predicting the TCDD level in fat tissue
  - language: SAS 
  - func:

__Lab-02.__ predicting Ireland’s health-care spending  
  - language: SAS 
  - func:  

__Lab-03.__ predicting life expectancy of people  
  - language: R 
  - func:  
   
__Lab-04.__ predicting Y 
  - language: R 
  - func:    

__Lab-05.__ Finding the source of the variation in a textile factory
  - language: R 
  - func:    

__Lab-06.__ Predicting diamond prices
  - language: Alteryx 
  - func:   
----------------------------------------------------------------------
### >Lab-01. predicting the TCDD level

__Data:__ The data set 'AgOrange.xlsx' is related to a study of Vietnam War veterans who were exposed to Agent-Orange(TCDD) herbicide during the confict. The data set contians TCDD levels in both "plasma" and "fat tissue" for 20 veterans. One goal of us is to determine the degree of linear association between these two variables. We want to use "plasma" TCDD level to predict the TCDD level in "fat tissue".





### >Lab-06. predicting diamond prices

__Story:__ A diamond distributor has recently decided to exit the market and has put up a set of 3,000 diamonds up for auction. Seeing this as a great opportunity to expand its inventory, a jewelry company has shown interest in making a bid. To decide how much to bid, we will use a large database of diamond prices to build a model to predict the price of a diamond based on its attributes. Then we will use the results of that model to make a recommendation for how much the company should bid.

 - **>Step 1. – Understand the data:** There are two datasets. 
   - 'diamonds.csv' contains the data used to build the regression model. Only this dataset has prices.
   - 'new_diamonds.csv' contains the data for the diamonds the company would like to purchase. We'll be predicting prices for the 'new_diamonds.csv' dataset.
   - **Carat** represents the weight of the diamond, and is a numerical variable.
   - **Cut** represents the quality of the cut of the diamond, and falls into 5 categories: fair, good, very good, ideal, and premium. These categories can be represented by an ordinal variable, 1-5 (We can decide to use the ordinal or categorical variable).
   - **Clarity** represents the internal purity of the diamond, and falls into 8 categories: I1, SI2, SI1, VS2, VS1, VVS2, VVS1, and IF (in order from least to most pure). These categories can be represented by an ordinal variable, 1-8. 
   - **Color** represents the color of the diamond, and is rated D through J, with D being the most colorless (and valuable) and J being the most yellow.
   
 - **>Step 2. - Build the model:** 
   - When using Alteryx, we do not need to manually create dummy variables before building the model. If we select a categorical variable, like cut or clarity, then Alteryx will automatically create the dummy variables and give the correct regression output.

 - **>Step 3. - Calculate the predicted price for diamond:** 
   - For each diamond, plug in the values for each of the variables into the equation. Then solve the equation to get the estimated diamond price.

 - **>Step 4. – Make a recommendation:** 
   - If we have the predicted price for each diamond, we can calculate the bid price for the whole set. The diamond price that the model predicts represents the final retail price the consumer will pay. The company generally purchases diamonds from distributors at 70% of the that price, so our recommended bid price should represent that.
   
   



































