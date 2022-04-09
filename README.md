# :cocktail: :tropical_drink: :wine_glass: The Models :tumbler_glass: :bubble_tea: :cup_with_straw:

# Description of models

## 1. Data

We get the data from 

Then, we clean the tweets by:

- [x] Convert text to lowercase
- [x] Remove all URLs
- [x] Remove twitter accounts (@)
- [x] Remove specific names
- [x] Trim blank spaces
- [x] Remove punctuations, symbols and numbers
- [x] Remove non-English tweets
- [x] Remove stop words

## 2. Feature engineering

We create four variables from the raw data:

* **user** : Account 
* **text** :  Tweet
* **followers** :  Number of accounts that follow the given user
* **location** :  Geographic ubication of the given user
* **verified** :  Indicator equal 1 if the account has this condition

## References

- [Sentiment Analysis: An Introduction to Naive Bayes Algorithm](https://towardsdatascience.com/sentiment-analysis-introduction-to-naive-bayes-algorithm-96831d77ac91)