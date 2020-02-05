# machine-learning-nanodegree
machine-learning-nanodegree

In this repository, there are all the files I have used to work on my Machine Learning Nanodegree from Udacity. <br>

For the capstone project, I decided to work on data from AirBnB in New York City to build and backtest different models 
based on machine learning to predict the prices of stays depending on the different caracteristics.

# Machine Learning Engineer Nanodegree - Udacity

## Capstone Project - Predicting AirBnB prices using machine learning and deep learning

### Introduction

AirBnB is an online platform that allows renters/home-owners ('host') to put their flat/room/house ('listing') available online to rent. In exchange of the night, the guests will pay for it. Even though hosts are expecting to put their own price on the platform, putting the right price is something much more difficult. After looking at the different products available on the Internet, there exists no software that gives the price without being free. Furthermore, they require a base priceand will adapt the prices according to the season, the day of the week, ...

As one may think, AirBnB pricing is really important, as much as a great cover picture. Indeed, a overpriced listing will not attract anyone and an underpriced listing will attract many people but for  the owner there is a clear loss of opportunity to increase profits. Hence, the host needs to find the right balance between the occupancy and revenue.

This project aims to use machine learning techniques (including deep learning) to predict the base price for properties in New York City. The project also provides some data visualization to help hosts understand how they position with regards to other hosts. It does not aim at providing the best model in terms of MSE but also a model that would rely on features that makes economic sense and not only the many features available.

### Conclusion

After looking at many models, the best model was a four-layer neural network including so L1 regularisation. The model achieves 65% of the price variance. It is possible that the rest of the variance is linked to some informations not available through data, 
