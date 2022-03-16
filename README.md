# Bike Sharing Assignment
> This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement
	A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


	A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


	In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


	They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

	Which variables are significant in predicting the demand for shared bikes.
	How well those variables describe the bike demands
	Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
- Business Goal
	You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- Data Set and Data Dictionary
	day.csv contains the dataset
	Readme.txt contains the data dictionary

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Final model indicates that feature 'atemp' has highest positive co-efficient value followed by 'yr'. Whereas 'windspeed' has highest negative co-efficient value.
- Adj R-sq of training dataset was 82% and that of test dataset was 79%. Hence difference is just 3% which indicates that this is a very stable model
- We also observed that on the test dataset, actual and predicted values are almost overlapping. Again a confirmation that model is good
- All the assumptions of Linear Regression were found to be true with this model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3
- Jupyter Notebook
- Visualization Libraries: Seaborn, Matplotlib
- Data Analysis Libraries: Numpy, Pandas, Scikitlearn, Statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Explain Linear Regression: https://towardsdatascience.com/laymans-introduction-to-linear-regression-8b334a3dab09
- Pearson's R: https://www.analyticssteps.com/blogs/pearsons-correlation-coefficient-r-in-statistics
- Scaling: https://medium.com/@premal.matalia/what-is-scaling-why-is-scaling-performed-normalized-vs-standardized-scaling-5113c86688f8
- VIF/Multicollinearity: https://www.sigmamagic.com/blogs/what-is-variance-inflation-factor/


## Contact
Created by [@ameycancode] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># bike_sharing_assignment
