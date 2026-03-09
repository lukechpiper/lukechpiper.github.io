Some results are presented here for this first model for T20 cricket. The idea is that we will calculate historical 
probability distributions of individual players scores. So each player will have unique and normalised 
P(score x), for x = 0,1,2,3,4,6,W. We then simply use these probabilities to perform a Monte-Carlo simulation of cricket matches. 

Evaluation on 991 out of sample matches

Accuracy: 60.9%
Log-loss: 0.687

Baseline comparison:
Random prediction accuracy: 50%
Random log-loss: 0.693

## Future improvements

It would be interesting to see how far this sort of model can go by simply improving the probabilities by taking into account
more variables such as venue, bowler type etc and updating them distributions in a Bayesian sense. 
