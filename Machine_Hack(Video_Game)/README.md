# [Machine Hack- Video Game Sales](https://www.machinehack.com/hackathons/5ef5dcfff86bc10bcd96d915)
This was my submission for the Dance Form competition hosted by Hacker Earth.</br>
The task was to build a machine learning model that can accurately predict the sales in millions of units for a given game.
</br>

### Approach :
- Data Cleaning
- Feature Engineering
- Baseline models
- Ensembling
- Final predictions</br>

A more detailed approach can be found in the [Notebook](machine-hack-video-game.ipynb)

### Analysis & Results :
- The given data was fairly clean, No missing values were found
- The distribution among varoius feature categories was balanced
- Since most of the categorical features contained many feature values, one hot encoding was not usead direclty. Values were binned based on heuristics to reduce the number of values and then were one hot encoded
- One comparing baseline models some simpler models (Linear Regression, KNN) were found to perform better than the complex ones. Given the size of training data was apt it is likely the complex models were overfitting to the noise
- Predictions from all the models were concatenated with the existing features and Final predictions were made on the new dataset
- It was found that this ensembling of predictions improved accuracy
