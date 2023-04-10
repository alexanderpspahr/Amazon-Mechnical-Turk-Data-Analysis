# When Will a Customer Accept a Coffee House Coupon?

Customers are surveyed about various driving scenarios under which the premise is to determine whether or not they will accept a certain coupon if they are the driver. 
Our objective is to determine the differences between the groups that choose to accept or reject the coupon for one group of coupons. In this study, we will be looking at
the coffee house coupons.

### Data
The data is soured from the UCI Machine Learning repository collected via Amazon Mechnical Turk

### Methodology
Data analysis is done using Python in a Jupyter Notebook file located in the root directory of this project.

### Goal
Deliver business actionable insights on the coffee house coupon group. What factors are highly correlated with accepting the coupon? What factors are correlated with rejecting the coupon?

# Insights
**Note: we will often refer to coffee house coupons as CH from this point forward.**

### Insight 1: Drivers who visit coffee houses more often are more likely to accept the coupon

![image](https://user-images.githubusercontent.com/129889030/230995133-af7d3638-1dfa-4a18-8d39-0f1ff9064c6e.png)

This may come as no surprise, but those who never visit CH are more likely to reject the coupon, while those who visit more often are more likely in general. This remains true
when controlled for other variables such as income, age, time of day, etc...

We can also clearly see that this trend is only for CH. It is not true that those who visit bars, restaraunts, or take-away are more likely to visit CH. Here is an example of 
what one of these graphs looks like:

![image](https://user-images.githubusercontent.com/129889030/230996220-619b0f8f-2691-412c-8f21-7564b14907f6.png)
