# JonhsHonky_covid_prediction
In this project, I have built the model where we can forecast the covid19 cases for a specific country or region based on past cases data..
# Domain Analysis
Confirmed cases: confirmed cases of Covid-19 based on global (whole Country).
    
Deaths cases: Death cases of COVID-19 based on global (whole Country). 
    
Recoveries cases:Recovery cases of COVID-19 based on global (whole Country).
    
Province/State	:Province/State are showing COVID-19 cases of State of country.
    
Country/Region: Country/Region are showing COVID-19 cases based on Country.
    
Lat: Latitude is showing measurment of globe or map of location north or south of the equator.
    
Long: Longitude is showing measurment of globe or map of location east or west of the equator.
    
Dates: Dates are showing how many cases came per day. 
# Data Analysis Report
I have used the 2 model for covid19 case prediction as linearRegression and Decision Tree Regression.We got the 99.96 % r2 score from decisiontreeregression which are maximum as cpmaored to other,So I will consider decision tree regression will be the best model for covid prediction.
# Suggestions to the government health department of the country for preparation
According to the dataset, we understood in the initial stage cases were less but in few days this virus was spread very fast all over the world. So My suggestion to government heath department, whenever we get covid-19 case, we should be very carefull and
take immediately action and patient should be quarantine for 14 days in doctors  observation.patients should be cover his/her mouth and nose with mask and sensitise their hand frequentely and make 2 meter distance from other.government should spread awareness about covid-19 virus and take vaccination.
# Challenges faced During Project
In this project, we had three dataset as confirmed ,deaths and recoveries cases and We needed to make the model prediction for covid-19 cases.
I felt little difficulty when i was doing this project because there were three dataset.During the implimentetion, I spent lots of time to understand the dataset.
Which features i felt not important i just droped that and Using the iloc function Extract the dates from dataset.Dates features is target variable and confirmed, deaths and recoveries are independent variable.
after that i created the empty list as world confirmed cases,world death cases and world recoveries cases and then sum the confirmed,deaths and recoveries cases and append in the emply list variables.
change the date into days using the for loop.Again  i create the unique country variable where i store all the unique country names. I Have done the Exploratory data analysis where analysed the world confirmed cases with unique country.
after that analysed the top 10 countries confirmed cases and Using the Plot graph compared all the cases as confirmed, deaths and recoveries in one graph and extract the insight.
I have compared the india confirmed cases with world confirmed cases and extact the insight.After completing the EDA ,Did the feature selection where we changed the rows and columns using the reshape function from numpy.
During the model creation Used the linearRegression and got the r2 score 99.92% and Decision Tree Regression and got the r2 score 99.96%. Both model gave us very good score that means Our model will perform very well for covid-19 prediction.
No need to used other model because both score is very good and I considered decision tree regression has very good model for covid-19 case prediction.
