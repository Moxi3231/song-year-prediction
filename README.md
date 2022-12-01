# song-year-prediction

## Here we developed two main apporach:
    1. Regression Based
    2. Classification Based

### In regression based apporach we used logistic regression model to train the model and evaluate the model performance on the unseen data.
-----
### As the model didn;t perform well because due to high variance of the data.
----
###  Then we changed the prespective and tried to classify the data into years instead of regressing them. That is we considered year as ordinal attribute instead of continous.
----
###  We used Decision Tree to classify the data but didn;t get much of an accuracy because the model couldn't perform well on unseen data.
---
### Then we tried Random Forest which improved the performance by quite a margin.
----
### The code for above can be found in song_pred_approach1.ipynb
---
Lastly, to learn the hidden pattern we used Neural Networks.
The code training neural network can be found in song_prediciton.ipynb.
The Neural Network achieved highest accuracy of 88%
