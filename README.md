# PROJECT-Houses-Regression
**This repository deals with houses prices regression problem, using a machine learning approach.**

**About The Dataset:**

_"Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. 
But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home."_

**Project Summary:** 

In this project I have learned so much! First of all, target was rescaled since is originally skewed. 
Then, a heavy feature engineering has been applied- 
creating many more features (using humen insights), fixing existing ones and so on.
Furthermore, I had to handle a mismatch number of features (after encoding them of course) in the train set and the test set.
Instead of encoding the features all together right from the beginning 
i insisted on encoding them separetely in the train set and the test set and managed to push them to the models coordinately.
Lastly, many different models have been tested, and a Voting Regresor mixed their predictions to create the final one.

**Thoughts for Future Improvements:**

A PCA dimensionality reduction approach has been tried, yet showed to be unuseful. There are ~170 categorical features, those are the most of the total features. 
A dimensionality reduction model which suits to categorical features should be tried- it should reduce overfitting.
A different approach then PCA for the numerical featuers would be nice as well, though is not highly prioritized in my opinion.
Also, an error analysis should be made- both in the test set, and mainly in the train-validation sets,
in order to understand where does the model fit well and where it doesn't, and fix it accordingly.
