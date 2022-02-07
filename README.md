# Bike Share Predictor
Predict the demand for bike sharing.

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

**Business Goal**:
Required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

BoomBikes want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands



## Conclusions
1. From the given dataset, we can conclude that below features/variables affect the number of bikes booked.
  'const', 'yr', 'holiday', 'weekday', 'workingday', 'atemp', 'windspeed', 'LightRain', 'Mist', 'spring', 'summer', 'winter'
2. The number of registered users have grown even the year  and hence yr has the direct positive correlation. 
3. It is also observed that there is more consumption when the temperature is higher and lower consumption when there is rain.
4. Working days brings in more users compared to holidays.


## Technologies Used
- The project is built on python using numpy, pandas.
- The project using matplotlib and seaborn for graphs.
- sklean and statsmodel is used for linear regression.

## Acknowledgements
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}
	
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)


## Contact
Created by [@lasrado] - feel free to contact me!