# Twitter Sentiment

Data was gathered from [this data challenge](https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/)
My interest was specifically to re-engage in using a Neural Network while using my skills in NLP.

## Problem Statement

To create a model that will identify which tweets are hate speech.


## Exploritory Data Analysis

While I did go straight into modeling, I did find that the second highest correlation to a tweet with hate speech was "trump" with the most correlated was "allahsoil" which is likely a hashtag, but a phrase I am personally not familiar with.  Further research into this term is warrented.
## Modeling

My best model was one with an initial layer of 100 neurons and with each subsequent layer being 10 less than the previous with the second to last layer having 5 neurons.  Currently I'm using a model with higher numbers of neurons at the start to better account for the large number of features.

## Future Steps
- Include hashtages in the words
- Hashvectorize to make it faster once it's in the NN
- Upgrade to a Convolutional Neural Network to see if that's better (and/or LSDM in a Recurrent Neural Network)
- Set up the Results_df & have it update after every run.
- Do research into "allahsoil" and any other words or hashtags that we're currently unfamiliar with.
