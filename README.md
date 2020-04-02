# Sarcasm Detector
A model created to classify a text as sarcastic or not.

Creates a Document Text Matrix (DTM), on which a binomial clasification model is trained to detect sarcasm.

Trained and tested on a random sample drawn from a [Kaggle dataset](https://www.kaggle.com/sherinclaudia/sarcastic-comments-on-reddit) of 1M Reddit comments which were tagged (or not) by the author as sarcastic, evenly split.

This model was able to correctly classify comments about 71% of the time (different pre-processing yielded slightly different results), as determined using Area Under ROC curve as the evaluation metric.

Given the difficulty of the task, and that it can be difficult for humans to detect sarcasm reliably, I am proud of the results.

Next step would be deploying this so that you, my good reader, can play with it and test it. Stay tuned.



