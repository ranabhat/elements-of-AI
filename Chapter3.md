# Real world AI

###### Compared to old-fashioned AI methods, Modern AI methods have the ability to deal with uncertainty because of which these methods work in the real world.

#### Odds and probabbility
-----------------------------

Ability to think of uncertainty as a thing that can be quantified at least in principle. Uncertainty is not beyond the scope of rational thinking and discussion, and probability provides a systematic way of doing just that. 

Key Points :
> * probability can be quantified (expressed as a number) and it can be right or wrong.
> * probability can be used to automate uncertain reasoning

#### The Bayes rule
-----------------------------

Used to weigh conflicting pieces of evidence in medicine, in a court of law, and in many scientific disciplines. 

```sh
    # the odds that it will rain later today(example)
    chances of rain: 206 in 365
    number of days without rain: 159
    Prior odds for rain : 206:159
    chances of clouds on a rainy day : 9 out of 10
    chance of blue skies on a rainy day: 1 out of 10
    chances of having clouds on a rainless day : 1 out of 10
    how much higher are the chances of clouds on a rainyday compared to a rainless day ?
    answer: chances of clouds are nine times higher on a rainy day than on a rainless day.
```
>  posterior odds = likelihood ratio * prior odds = 9* (206/359) = 1854:159

#### Naive Bayes classification
--------------------------------

The Bayes classifier is a machine learning technique that can be used to classify objects such as text documents into two or more classes. The classifier is trained by analyzing a set of training data, for which the correct classes are given.
> * Naive Bayes classifier can be used to determine the probabilities of the classes given a number of different observations.
> * Real world application: spam filters