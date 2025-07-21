# Practical-Application-1
Required Assignment 5.1: Will the Customer Accept the Coupon?
Context

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

**Overview**

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

I used quite a few things which I learned from Module 1 to Module 4 in this course.
first importing all necessary libraris such as Pandands,Seaborn,matplotliband numpy
extensive use of pandas to read / create dataset followed by 
    1) Identifying null values and deciding to drop or replace values - I used both
    2) Converting String type Age Column in to Int
    3) Cleaning / convering Age Column data in meaning ful data for rows having text values.
Use of Seanborn library to plot barplots to analyse data
artimatic and functions to calculate and round percentage values.
------------------------------------------------------------------------------------------------------------
**Conclusion of this assignment / analysis of data is - **
------------------------------------------------------------------------------------------------------------
**Bar Coupons : **
Frequency of bar Visit : Drives who go more than once to bar largely accpeted bar coupons
Passenger impact : it is clear that Adult passengers with no kids as passengers also largely accepted coupons
Passenger occupations : frequency to visit morethan ones with no kids as passenger plus occupations other than farming, fishing, or forestry largely accpeted coupons
income impact and restaurant spending : drivers going to cheap restaurants and income less than 50K are on on lower side of acceptance of coupons

**Coffee Coupons :** 
overall coffee hous coupon acceptace is half and half i.e 50%
Frequency of visits : Drivers who visited coffee house more than once has higher rate of coupoun acceptance
Temprature impact : looking at percentage , tempratures do not make that big of a difference in acceptance rate
