# Module 12 Report

## Overview of the Analysis

Maching Learning Logistics Regression Model ANalysis

* The purpose of this report is analyize credit risk using Machine Learning.
* The financial information is provided in a .csv file.  The end goal is to predict whether 
    a loan was health or not.  A healthy loan was not a rist for default.
* Part of the challenge was to ensure a balance data set for training purposes.
* During this project efforts were made to understand the data and bring it into
balance.  As such, oversampling method was used in order to provide adequate test data.


## Results

* Machine Learning Model 1: Logistical Regression using Original data
  * The original data was heavily weighted with "healthy" loan data which
      may contribute to overtraining.  It can also lead to issue of being able
      to predict unhealthy loans.



* Machine Learning Model 2: Logistical Regression with Oversampling
  * This methoed allows us to improve the accuracy of predicting 
      unhealthy loans.

## Summary

In summary
* Logistical Regression with Oversampling provided a higher accuracy
    of predicting "unhealthy" loans.
* An emphasis should be made to determing whether management deems the performance
    of this model.  Is it more important to predict the `1`'s, or predict the `0`'s?

In conclusion, further assessment is needed to determine the final recommendation to managemnt.
Further discussions surrounding the purpose of the final outcome of
the prediction would behelpful.  For example, will the results be used to aprove loans
or to initiate collection proceedings.
