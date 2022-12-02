# Adult income dataset visualizations and predictive models

**Author**: J. Tulani Aytch

### Business problem:

Visualization of various features from a dataset on income and testing of predictive models on the given data to help make predictions on the average income of an adult, specifically whether they would be earning more or less than 50k.


### Data:
[Data](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)

A widely cited KNN dataset with 14 features and 48842+ instances.

### Methods:
Removed columns: 'fnlwgt', 'educational-num', 'capital-gain', and 'capital-loss', as they were deemed unneccesary.
No other data was changed or removed in this dataset as it was already fairly clean.

### Results:

![image](https://user-images.githubusercontent.com/112998617/205214146-2d1fa016-785f-4fa3-a19e-1fdc67bf8e8b.png))

As you can see by this plot, the highest amount of people with low incomes was priv-house-serv. Looking into why this is the case could yield useful restuls.
Other-service is 2nd the highest and also the least specific, inquiring into this more to see what services this includes could be useful.

The highest amount of people with high incomes were, Exec-managerial, and Prof-Specialty,with around 45% of the people with these types of jobs earning incomes above 50k. Looking further into this with the other values such as Age and education could also prove fruitful.
The armed forces also have a very high deviation which could also be worth looking into.


![image](https://user-images.githubusercontent.com/112998617/204623129-2350d691-77ef-4567-a57d-e3023269f432.png)

From the chart we can see that most people were either HS-grads or Some College. As many know, a college degree typically results in a higher income, so finding a correlation here and finding out why most are not finishing college could prove useful.
### Model Results

For the models I wanted to see which model would be able to most accurately predict which income bracket an instance would be in.

I used a KNN model, a Logistic Regression model, and a Decision Tree Classifer model.

The final model I have chosen for this project will be the original DecisionTreeClassifier Model.
It had the best overall results and leaves the most room for tuning and refining.
There were still a large amount ways the model could be tuned, which would take more time to test, but the results of the model with its default parameters are promising.

![image](https://user-images.githubusercontent.com/112998617/205214945-94058fe1-9fe1-4aab-87ef-e0253064a970.png)
