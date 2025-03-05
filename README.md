# boom-bikes-case-study-4-upgrad

> This is a linear regression project done in python to figure out and optimize the demand for a bike-rental compay


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This study is done to figure out the factors that influence the demand for the boombikes bike-sharing company. We are going to build a model that would predict the demand as accurately as possible from the pre-pandemic dataset. The predictions derived from the given features will be used by the management to understand market dynamics and strategize the business plans accordingly, to be the preferred bike-share company.

Our approach to solving the problem would be to build a model with the given features and predict the target (count of total rental bikes including both casual and registered), reliably. For this we would first understand the data, prepare the data, do the EDA. Then build a model with trainig data, evaluate it with test data.

Based on the results, we would also answer the provided subjective questions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The R-squared value of the train set is 83% whereas the test set has a value of 79.6% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.
- Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of predictors.
### Inferences from the model
- the demand is more in the fall and summer seasons. Owing to the pleasant
weather
- the demand curve against the months closely follows seasons since the months are
a subset of seasons. So the high demand in May to October
- demand is more on holidays because people do recreational activities like bicycling
more on holidays
- workingdays don't influence the demand much
- weekdays also don't influence the demand much
- demand goes high on days with nice weather. Snowy days don't have much takers

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
