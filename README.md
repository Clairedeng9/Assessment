# Assessment
### Self-Assessment
The Data Analytics & Visualization Boot Camp was a 24-week program to provide myself on a transformational journey that dramatically improved my skill set. During these challenging, frustrating and struggling 24 weeks, I was challenged to complete difficult exercises and trained to use big picture thinking and think critically. It is a pushing myself and to be pushed then toward to success process. Before, I belive I can make it. Now, I made it!

##### Roles in Final Project
At the beginning of the project, I am in the square role to be responsible for setting up the organization repository and add all the people into GitHub organization as owner. We created our own branch in GitHub and discuss communication portal and dates and frequencies for each segment catch up.

1st Week - I was created a Word file try to draw a big picture for this project and let everyone fit into the different aspects of component for this project. Then I turned to build up the ERD of the database and local database and integrated different tables into one main table and use the jupyter notebook `sqlalchemy` and connection string with local database.

2nd Week - I was as a parallel role in the triangle role to prepare and research a prediction or forecasting method in R to analysis our time series data and predict the gas and stock price.

3rd Week - each team member showed their work and codes to all members in the team and wrap up each one work from previous week, follow the rubics week to check if we cover all the topics and areas. Also, I changed our machine learning models to connect with local database instead of ready from exporting CSV file.  

4th Week - all members are creating their presentation pages and dashboard to get read for the presentation week.

#### Challenges Overall:
1. Our first big challenge was that we chose a time series model for our final projectm, the way to predict and machine learning modules did not introduce more about the time series data and what kinds of machines learning model we will create became our headache problem;
2. After some ideas from TA and instructor, we tried several ways to build machine learning model and in the other way we did tons of research online to see how normally people deal with time series data to build up model, to predict and to analyze, so we also use R studio and several uncovered package in R to see if we can make things happen. During the exploring, we also face some terminologies that we never knew before this project, it was really time spending on understand these terms.
3. Our team determined to use local database instead of cloud database, so the third challenge coming to us, how do we make sure we share the same data, also means that we need to start at the same dataset. First of all, we exported them from the database as CSV file, but still suggested by TA that we need to connection string and use the Jupyter notebook connection string to connect with dataset in database just in case in some steps our dataset was not consistent with each other. It was a long process to recall and research and test how the `sqlalchemy` can make it happen.
4. As for our dataset, we used time series data, on the other hand, we had different type of time format by daily, by weekly and by quaterly, to make these covert and standardize them, it was other challenge for us.

### Team Assessment

✓ Their communication protocol, including any challenges, how they were resolved, and what they would do differently next time
- Communication: Our team will be commmunicating through slack. We have also scheduled recurring zoom check-ins for Saturdays to help prepare for the week ahead. We have split role responsibilities but are also working together through the dataset and clean up.
- We have one member in the different time zone, and due to time differences, it was hard to make our Saturday catch up scheduled

✓ Their strengths as a team, including tips and tricks they would want to share with a new cohort kicking off the project 
- We have one is good at R programming language, we can make as another analysis way to compare the one with machine learning prediction model or linear regression model;
- One is good at Machines learning model, help all members deeply understand the models we will build for;
- One is good at organize and dashboard creations, helped with our ReadMe, Google slides and dashboard build up;
- One is good at mathmatics related area to answer some math models like polynomial model questions

### Summary of Project 

✓ Topic addressed
Our group came together with a shared interest in stocks. After discussing several options for our project, we decided it'd be interesting to see if there are any correlations between stocks and the high gas prices we all experienced in the last few months. We were mainly used Kaggle data and data from EIA gov website. In addition to understanding if there are any correlations between stock and gas prices, we also set out to see if the data could tell us:

- How the stock market, specifically S&P500, has changed in the last 5 years
- What drives petroleum product prices; and
- If we could predict gas or stock price behavior
✓ Machine module used
- Linear regression model
For the first model, we selected GSPC Close price as our x label and Gas Price as our Y label and created a scatter plot to see how the data behaved.

- We created a Scikit-learn and performed the linear regression on the 9 columns. Then fit the data into the model. Using Scikit-Learn to perform a Linear Regression test for 1,068 values, we get a Slope of 0.00025558 and a Y-intercept = 2.0820572529674304. The slope indicates the steepness of a line and the intercept indicates the location where it intersects an axis. The slope and the intercept define the linear relationship between two variables, and can be used to estimate an average rate of change. The greater the magnitude of the slope, the steeper the line and the greater the rate of change which means one variable is dependent of the other. In this case our line lacks steepness. Like the first model, we found that more models are needed to test correlation and find a better prediction.

✓ Results of the analysis 
SP500 and the two individual oil companies CVX and XOM are related to gas price, the coefficients of variables show as below, the slopes are not horizontal. We can also see the multiple linear regression formula above, knowing that importing amount factor was closed to zero but we cannot say the slope of the ilnear model considered to be zero.

![image](https://user-images.githubusercontent.com/103073631/189786242-ec3de6f4-9cf6-49e3-ab18-817a7741a4f5.png)





