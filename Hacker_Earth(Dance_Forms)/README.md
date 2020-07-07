## [Hacker Earh - Dance Forms](https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-identify-dance-form/machine-learning/identify-the-dance-form-deea77f8/)
This was my submission for the Dance Form competition hosted by Hacker Earth.

### Approach : </br>
Given the small train dataset consisting of around 300 images, a fairly straight forward Transfer Learning approach was used with some minor tweaking in learning_rates and num_epochs</br>

### Analysis : </br> 
- Model was found to converge with 5 - 10 epochs with a _learning-rate_ of 0.01
- Later it was reduced to 0.0001 for next 5 epochs
- No other hyperparameter tuning was performed apart from _num-epochs_ and _learning-rate_
- Resnet18 seemed to perform better than deep models
- Given the small test size there were high chances of manual prediction for a domain expert.</br>
- Overall achieved a decent accuracy of around 85.

_Note_ : Because of time constraints I was not able to further improve my submission (I worked on this problem for 2 days). 
 </br>
 
### Possible Improvements : </br>

- Experimenting with other iamge augmentation techniques
- Hyper parameter tuning
- Using ensambles
