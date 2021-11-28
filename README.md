# Billion-Wealth-Calculator
 
 This project uses Kaggle's Forbes Billionaires of 2021 dataset to train a model that can predict a person's networth based on it's age, country and industry. I used a very simple RandomForestRegressor model from the sklearn framework. The idea here is to test different approaches dealing with categorical values rather than finding accurate results. Any prediction will be highly biased since the model has been trained with data coming from some of the wealthiest people on the planet, don't expect it to accurately predict an average person's networth. You will find these 3 approaches:
 
 - Drop values
 - Ordinal Encoding
 - Hot-One Encoding
 
 You will find that any of the three approaches yield the same results, the main reason to this is because of the size and heterogeneity of the dataset. As I said this is intended to be a display of how to deal with categorical data and build a reusable template to test these approaches. In this case the dataset wasn poorly chosen but might work well with other datasets.

Links:
- Dataset: https://www.kaggle.com/roysouravcu/forbes-billionaires-of-2021?select=Billionaire.csv
