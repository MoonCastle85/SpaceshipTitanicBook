# Handle missing data
Before we get into more advanced exploration of the data, let's first visualize the data in different ways to get a better sense of it.

## Simple but useful features
We're given several useful bits of information about the data on the [competition website](https://www.kaggle.com/competitions/spaceship-titanic/data) that we can apply to create some useful features. By features, I mean new variables that are derived from existing ones. For example, Cabin is comprised of information about the cabin number, the deck and the side and PassengerId contains the passenger group id.

I've created a function that derives these new variables from existing ones. I've also created features that count the number of unique categories of different variables when related to the passenger group so that we can filter our visualizations and answer questions like 'Is any passenger group travelling from different home planets?'


























