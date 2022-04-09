# :airplane: :seat: The Models 

# Description of models

## 1. Data

We extract 1,000 tweets mentioning @JetBlue and 1,000 mentioning @SouthwestAir from the [Twitter API](https://developer.twitter.com/en) for a particular day on march 2022.  We filter out retweets during this part of the process.
During extraction we define the following variables: 

* **user** : Twitter user account originating the tweet
* **text** :  Full text content in each tweet
* **followers** :  Number of user accounts that follow the given user
* **location** :  Geographic location from the given user
* **verified** :  Indicator equal 1 if the account has this condition

Then, each team member manually tagged 500 tweets into three categories

* **1** Positive perception towards the airline
* **-1** Negative perception towards the airline
* **0** Neutral perception towards the airline


We also verify for [Twitterbots](https://es.wikipedia.org/wiki/Twitterbot) by XXXX

## 2. Feature engineering

We clean the tweets by:

- [x] Convert text to lowercase
- [x] Remove all URLs
- [x] Remove Twitter accounts (@)
- [x] Remove specific names
- [x] Trim blank spaces
- [x] Remove punctuations, symbols and numbers
- [x] Remove non-English tweets
- [x] Remove stop words
- [x] Remove hastags (#)

## 3. Algorithm

We consider the following methods


## Naive Bayes Algorithm



## Logistic Regression
Logistic regression is a classification algorithm used to assign observations to a discrete set of classes.
Logistic Regression is a Machine Learning algorithm which is used for the classification problems, it is a predictive analysis algorithm and based on the concept of probability. 
The Logistic Regression uses a more complex cost function than the Linear Regression model, this cost function can be defined as the ‘Sigmoid function’ or also known as the ‘logistic function’.
One of the main characteristics of logistic regression is that it bound the cost function to be between 0 and 1, which fails to hold under linear functions. 
To guarantee the cost function to be optimized (global minima), it is defined as a convex combination of the cost function when y = 1 and y = 0. 

This intuition can be easiliy extended for more than two categories, by using the multinomial logistic regression. 

<img src="../image/ZOnIK.png">


## References

- [Sentiment Analysis: An Introduction to Naive Bayes Algorithm](https://towardsdatascience.com/sentiment-analysis-introduction-to-naive-bayes-algorithm-96831d77ac91)
- Introduction to Logistic Regression](https://towardsdatascience.com/introduction-to-logistic-regression-66248243c148)