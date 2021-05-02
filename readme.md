# Project: Analyze A/B Test Results
## by Stanislava Stachova
---


## Table of Contents
* Introduction
* Part I - Probability
* Part II - A/B Test
* Part III - Regression
* Conclusion
---


## Dataset
This project focuses on understanding of the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who __"convert"__, meaning the number of users who __decide to pay for the company's product__. 

The goal is to work through this notebook to help the company understand if it should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

---


## Conclusion
Probability in Part I gives us too general information which could be a bit risky for business to rely on only. The results may be distorted by Simpson's paradox as we calculate results based on groups only. The final result of 50% probability is not very helpful in decision making process. Such results are too simple and dive not deep enough to make decision.

A/B test results evaluation in Part II. shows that as a result of hypothesis setting and testing, p-value is higher comparing to alpha. This tells us that there is no statistically significant influence and we fail to reject null hypothesis. As a result,  business would probably not use new webpage. Using this technique might have its drawbacks, as we did evaluate only factor related to old and new page. However there are plenty of other factors which might influence user in purchase decision (time for decision, time take to test groups, discounts, attractivity of product, etc.).


Results from regression in Part III. supports the results in Part II., however p-value even though it is still higher than alpha 0.05, it is much lower than in p-value calculation in Part II. Results supports that there is no statistically significant relationship and we fail to reject null hypothesis. All in all, the Company should evaluate also other factors and add it to the model in order to have better understaning what may impact the decision to convert. However, this may bring also the problem with multicillinearity, which could be reduced through carefull review of other possible factors.
