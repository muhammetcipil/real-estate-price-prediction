# real-estate-price-prediction

# Introduction
![](https://media.istockphoto.com/id/1400262642/tr/vekt%C3%B6r/print.jpg?s=612x612&w=0&k=20&c=5P5e9dUYMibp5TsbdA4lJ3Q7mC_bK2IWQxnu7sON8Jw=)

Hello everyone,

I will briefly tell what I have done in my project and which resources I followed. I created this project by following this [YouTube video series](https://youtube.com/playlist?list=PLeo1K3hjS3uu7clOTtwsp94PcHbzqpAdg&si=VgwePgdyLbC6I4VC) with my own comments.Based on the “Data Science Roadmap” content creator Codebasics that I have been following for a long time for becoming data scientist.

In our project, I used the “bengaluru-house-price-data” dataset, which provides information about house prices and features in a state in India.

Firstly, we loaded our dataset and removed missing data because it did not follow any specific pattern. Next, we handled outliers by replacing outliers with boundary data using the 1.5 quantile method. Finally, we performed encoding transformations for relevant features.

Moving on to the Model Building phase, we initially created our model using linear regression. We then evaluated the score obtained from linear regression using cross-validation. Afterward, we used hyperparameter tuning (GridSearchCV) to find the best model and parameters among three models (Linear Regression, Lasso, DecisionTreeRegressor).

In the Model Evaluation stage, we examined all evaluation metrics based on the Linear Regression model, as it occured the best scores.


If you are confused, you can check out the sources or contact me. Also, please keep in mind that I am still learning and my models not perfect as statisticly, so if you spot any incorrect explanations or anything, please let me know. Enjoy your journey, as well. 📊🔍🤖
