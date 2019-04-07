# Car-Price-Multiple-Linear-Regression

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. 

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

Which variables are significant in predicting the price of a car
How well those variables describe the price of a car
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the Americal market. 

Business Goal:  Model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market. 
  
Constraints:
  1. There is a variable named CarName which is comprised of two parts - the first word is the name of 'car company' and the second is the 'car model'. For example, chevrolet impala has 'chevrolet' as the car company name and 'impala' as the car model name. You need to consider only company name as the independent variable for model building.

Steps:
  1. Load and understand the data.
  2. Perform EDA to get the intuition of the data.
  3. Prepare the data for the model, using ending, dumm variables, train-test-split and perform scaling.
  4. Use RFE(from sklearn library) to jot down the top 15 variables after which manually analyze each variable.
  5. Built the model from statsmodels api.
  6. Check out the summary of the model and calculate the VIF values. Based on the p-value and VIF value remove the redundant variable.
  7. Repeat step 6 and 7 until the best model is built.
  8. Check for the assumptions whether the hold true or not.
  9. Perform the predictions on the test set and check out different metrics values.
