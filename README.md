# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Linear Regression of a US based housing company which tried to enter Australian Market.
- Need to predict the parameters that impact housing Sale Price
- This would help the company to make decision to which properties are undervalued and make right decision to buy or not.
- Dataset: train.csv
- Data Definition: Data Defintion.txt

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-Regular Linear Regression with all Columns included:

-Train R2 Score: 0.970, Test R2 Score: -0.0635827670402502

========================================

-Ridge + RFE:

R-Square for Training Set:  0.9166792947105542
R-Square for Test Set:  0.80
RSS for Training Set:  1.3752973911929183
RSSS for Test Set:  9.177619858635754
MSE for Training Set:  0.05742887147280618
MSE for Test Set:  0.09697060913229046

=========================================

-Ridge Regression:

R-Square for Training Set:  0.9096859889725758
R-Square for Test Set:  0.8189583410011175
RSS for Training Set:  1.490729385003399
RSSS for Test Set:  7.577743745473288
MSE for Training Set:  0.05979038895607673
MSE for Test Set:  0.08811402672916242

==========================================

-Lasso Regression:

R-Square for Training Set:  0.8723206736948281
R-Square for Test Set:  0.8156853791734743
RSS for Training Set:  2.107483893310431
RSSS for Test Set:  7.714737993955898
MSE for Training Set:  0.0710909150973423
MSE for Test Set:  0.08890694385670009


=============================================

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python Library: version 3.0
- Scikit
- Pandas
- NumPy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was created as a case study assignment for UPGRAD & IIIT-B EDA module


## Contact
Created by Balakumar Seethapathy(balakumar.log@gmail.com)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->