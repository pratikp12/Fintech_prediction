# Fintech_prediction

Directing Customers to subscription products through app behaviour analysis

# Table of Content
1. [Project Overview](#project)
2. [Business Challenge](#Business_Challenge)
3. [Dataset Overview](#dataset)
4. [Steps](#steps)
5. [Model Choose](#model)
6. [Summary](#summary)
<a name="project"></a>
## Project Overview
In today's market, Many companies have a mobile presence.Oftern, these companies provide free products/services in their mobile apps in an attempt to transition their customers to a paid mambership.
some examples of paid products, whihc originate from free ones, are YouTube Red, Pandora Premium, audible Subscription, and You need a Budget. Since marketing efforts are never free, these companies need to know exactly who to target with offers and promotions.

- __market__: The target audiance is customers who use a company's free product. In this case study, this refers to users who installed (and used) the company's free mobile app.

- __Product__: The paid memberships often provide enhanced versions of the free products already given for free, alongside new features. For example, YouTube Red allows you to leave the app while still listening to a video.

- __Goal__: The objective of this model is to predict which users will not subscribe to the paid memberships, so the greater marketing efforts can go into trying to __"convert"__ them to paid users.
- 
<a name="Business_Challenge"></a>
## Business Challenge
- In this Case study we will be working for fintech compnay that wants to provide its customers with a paid mobile app subscription that will allow them to track all of their finances in one place.
To attract customers, the company releases a free version of their app with some of the main features unlocked.

- The company has tasked you to identify which users will most likely to NOT enrol in the paid product, so that additional offers can be given to them. Because of the costes of these offer, the company does not want to offer them to everybody, especially customers who were going to enroll anyways.

<a name="dataset"></a>
## Dataset overview
- By working for the company, we have access to each customer's app behaviour data. This data allows us to see the date and time of app installation, as well as the features the user engaged with withinthe app.App behaviour is characterized as the list of app screens the user looked at, and wehether the user played the financial mini-games available.
- The app usage data is only from user's first day in the app.This limitations exists beacause users can enjoy
a 24-hour free trial of the premium features, and the company wants totarget them with new offers shortly after the trial is over

<a name="steps"></a>
## Steps  
1. Access, Clean and Analyze Data

This step involves Data cleaning process and Classification based on different group of users.
2. Training Data and Models
In starbuck case, what I like to predict is whether the promotion offer will be efficient for certain users. It is a binary classification problem.

The target will be the efficient offer.

The features to train will be the other features in the data, include the users demographic characteristics and also the offer duration, type, offer channels, etc.

I defined the dataset as labeled data, so we will use supervised learning models.

What I want to predict is a categorical form, will be YES or NO, 1 or 0.
The target will be the efficient offer.

<a name="model"></a>
## Model Choose

I tried logistic regression model to check which model 


<a name="summary"></a>
# Summary
![](data/star1.PNG)
### 
