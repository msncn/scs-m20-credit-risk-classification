# Credit Risk Analysis Report

## An overview of the analysis 

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## The results 

Model 1 Logistic Regression:
![image](https://github.com/msncn/scs-m20-credit-risk-classification/assets/130943141/be3c7fe7-5fc1-497b-bb07-1b84aae86f1d)

Model 2 Logistic Regression with ReSampled Data:
![image](https://github.com/msncn/scs-m20-credit-risk-classification/assets/130943141/94c54cf1-1ced-48ef-9ceb-b26f0fc54e15)

## A summary
For precision, both models have a 1.0 for `healthy loan`, however, model 1 (0.85) has a higher result in terms of detecting the `high-risk loan` compared to model 2 (0.84).

For recall, both models have a 0.99 for `healthy loan`, however, model 2 (0.99) has a higher result in terms of detecting the `high-risk loan` compared to model 1 (0.91).

For accuracy, model 2 (0.9936781215845847) has a higher precision in terms of detecting the `high-risk loan` compared to model 1 (0.9520479254722232).

Overall, the second model *Logistic Regression with ReSampled Data* performs better as it has a higher accuracy result. And I would recommend using the second model. The performance depends on the high-risk loan as both models predict the same for the healthy loan.



