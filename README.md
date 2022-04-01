# HW-1
Repo for HW 1

1) The main difference has to do with whether the data is labelled. In supervised learning, the data and output are labelled. Therefore, the goal of supervised learning is to determine a function which correctly represents the relationship between the output and other data. With unsupervised learning, the data is not labelled. Therefore, the goal of unsupervised learning is to discover the structure of the unlabelled data.

2) A regression model has to do with the type of output. A regression model involves a quantitative output. This has to do with numerical values and can refer to quantities such as prices, miles, etc. A classification model involves a qualitative output. This output is nonnumerical in nature and can refer to qualities such as health status (alive/not alive), color of car, etc.

3) Two commonly used metrics for regression ML problems are mean squared error (MSE) and mean absolute regression (MAE). Two commonly used metrics for classification ML problems are Accuracy and F1-score.  

4) Descriptive: Here we are using a model to visually emphasize a pattern within our data.
   Predictive: Here we are using a model to predict an outcome (Y) with as little error as   
                possible. 
   Inferential: Here we are using a model to test theories. These theories allow us to ask 
                questions such as: What features of the models are significant? Can our data be   
                generalized to the broader population? etc. 

5) A mechanistic model assumes that the model is parametric in nature. From there, we can add more   parameters based off of the nature of the data. An empirical model relies more on real-world 
  data instead of theory. Here, we look at the data and have much more flexibility in creating a 
  model in comparison to a mechanistic model. Both of these models run the risk of overfitting,   
  a phenomenon where the model is to closely alligned to a particular set of data points. 
  
  In general, an empirical model is easier to understand. This is because the nature of the model 
  will always be parametric. 
  
  A model that will be less flexible (empirical model) will reduce bias and therefore provide more interpretability. However, this will also lead to a natural increase in variance (spread of data). On the other hand, a model that is less flexible (mechanistic) will increase bias and therefore decrease interpretability. However, this will also lead to a natural decrease in variance (spread of data). This is the natural tradeoff we must deal with when choosing models.
  
6) The first statement is predictive in nature. This is because you are predicting an output (vote or no vote) based off of different variables. The second statement is inferential. Here, you are asking a question about a potential variable and whether it is relevant to the model.
    