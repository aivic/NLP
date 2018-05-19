The given repository is based on predicting the probabilities of various tags attached to a single word.  

## Working procedure  
The task has been divided into three phases: 
* Creating a *Bag-of-Words* with associated tags and normalized occurrence (weights).
* While training, update the weights using *Adaptive boosting* procedure with few modifications for new tag(s).
* While testing, predict the probability of a tag for a word based on the weights.

The script directory holds the Ipython notebook which implements the given flow.
