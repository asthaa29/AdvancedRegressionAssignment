# Project Name
> In this programming task, the objective is to construct a multiple linear regression model that involves assessing potential properties for acquisition in the Australian market. To construct a regression model that incorporates regularization techniques. The objective is to predict the true values of these prospective properties, aiding Surprise Housing in making informed investment decisions based on the model's predictions.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Surprise Housing, a housing company headquartered in the United States, has made the strategic decision to expand its operations into the Australian market. Leveraging data analytics, the company aims to acquire properties at prices lower than their intrinsic values and subsequently sell them for a profit. To facilitate this expansion, the company has gathered a dataset comprising information from the sale of houses in Australia.
The resulting model will serve as a valuable tool for management, offering insights into the nuanced relationship between house prices and the identified variables. This understanding will empower the management to strategically adjust the firm's approach, focusing efforts on areas poised to generate optimal returns. Additionally, the model will provide a comprehensive overview of pricing dynamics in a new market, enhancing the management's comprehension of the intricacies involved.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

#### Score for both Ridge and Lasso regression.
- Ridge : Train :90.9 Test :88.8148
- Lasso : Train :91.1932 Test :88.6552


#### Top 5 most significant variables in Ridge are:
- PavedDrive_Y               0.080
- GarageFinish_Unf           0.073
- GarageFinish_RFn           0.069
- GarageFinish_No Garage     0.048
- GarageType_No Garage       0.043

#### Top 5 most significant variables in Lasso are:
- PavedDrive_Y               0.086
- GarageFinish_Unf           0.075
- GarageFinish_RFn           0.072
- GarageFinish_No Garage     0.048
- GarageType_No Garage       0.043

- Optimal Value of lamda for ridge : 20
- Optimal Value of lamda for Lasso : 0.001

Because of Feature selection as well we can choose Lasso regression in this case.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - 3.11.3
- Numpy - version 1.23.5
- Pandas - version 1.5.3
- Matplotlib - version 3.7.0
- Seaborn - version 0.12.2
- sklearn - version 0.24.1
- statsmodels - version 0.13.5.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Connect with me on LinkedIn:-
- [Astha Agarwal](https://www.linkedin.com/in/asthaagarwal/)