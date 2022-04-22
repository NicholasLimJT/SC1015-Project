![image](https://user-images.githubusercontent.com/87572499/164483268-9bb973f7-2d28-4dc6-9cd3-028685b5b91c.png)

# SC1015 Mini Project

Contents
========

- [Introduction](#Intro)
- [Team Members](#Team)
- [Problem Definition](#Problem)
- [Data Set](#Data)
- [Exploratory Data Analysis](#EDA)


## Introduction
<a id = "Intro"></a>
This is SC16 Group 6's take on our Mini Project for SC1015 which explores the data set of [SGcarmart Prediction](https://github.com/xianjinseow92/Data-Science-Projects/blob/master/Project_2_SgCarMart%20Price%20Prediction/notebooks/sgcarmart_used_cars_prices.csv)


## Team Members
<a id = "Team"></a>

| Name                 | 
|----------------------|
| Nicholas Lim         |
| Shrey Tibrewal       |  
| Heng Yin Cang        |


## Problem Definition
<a id = "Problem"></a>
Buying a car in Singapore is infamous for its high cost, yet its every Singaporeans' dream to own one and avoid squeezing into public transport. So, this lead our team to formulate this question:
#### > How do we as a buyer, decide if a car purchase is worth it and get the biggest bang for our buck? 

## Data Set and Preparation
<a id = "Data"></a>
Through a lot of discussion, our team went through multiple data sets before settling on [This Dataset on GitHub](https://github.com/xianjinseow92/Data-Science-Projects/blob/master/Project_2_SgCarMart%20Price%20Prediction/notebooks/sgcarmart_used_cars_prices.csv) that conforms with what we wanted to discover.

This Dataset is interesting as it gives a Singaporean context. To illustrate, ![image](https://user-images.githubusercontent.com/87572499/164482835-26a3ef01-c95a-44aa-832a-54e0eb8f5b1f.png)
![image](https://user-images.githubusercontent.com/87572499/164482545-587cf914-6353-4b27-95fa-91b3d4bcd546.png)
As car prices are exorbitant in Singapore comapred to the other countries. It is a good idea to stick to Singapore only. 

## Exploratory Data Analysis (EDA)
<a id = "EDA"></a>
Based on our EDA, we discovered that the data is heavily skewed to the right, this shows that cars do not tend to go on sale for lower prices while it can also soar to an exuborantly high price. This discovery led us to delve further into analysing the outliers and figuring out what leads to the extremely high prices.

#### Outliers
By diving into an Outlier only data set, we found that the main culprits of the high prices are 3 brands, BMW, Mercedes-Benz and Porsche

<img src="https://logos-world.net/wp-content/uploads/2020/04/BMW-Logo.png" width="300" height="175"> <img src="https://logos-world.net/wp-content/uploads/2020/05/Mercedes-Benz-Logo-700x394.png" width="300" height="175"> <img src="https://logos-world.net/wp-content/uploads/2021/04/Porsche-Logo.png" width="300" height="175">

- This could be due to how popular these brands are amongst the general populace of Singapore, most households will know these 3 brands and whenever a luxury car brand is mentioned, people will frequently state these 3. 

We also took a look into an extreme case in our outliers and discovered a McLaren 720s that went for 938000 Dollars, what does this show?
<img src="https://i.i-sgcm.com/cars_used/201908/846345_1b.jpg" width="800" height="500">

Some possible theories:
 - The McLaren is a limited car, with only a certain number of vehicles every built, making it highly sought after.
 - The reputation of the McLaren brand of sports cars is good enough to warrant the price.
 - Singapore's procedures that obtain a car and the COE greatly ramps up the price, on top of a McLaren being a luxury vehicle.

#### Non-Outliers
For the data that fell within the desired ranges, we found that the most common brands are Toyota, Honda and Mercedes-Benz
<img src="https://logos-world.net/wp-content/uploads/2020/04/Toyota-Logo-700x394.png" width="300" height="175"> <img src="https://logos-world.net/wp-content/uploads/2021/03/Honda-Logo-700x394.png" width="300" height="175">

What does this mean?
- Toyota and Honda cars are seen daily on the roads of Singapore, and the 'normal' citizens will still have the ability to purchase one.
- Mercedes_Benz vehicles are becoming more accesible to the general populace?
- Perhaps the quality of living in Singapore is reaching a point where previously 'luxury' vehicles are affordable.

## Models Used


1. [Linear Regression]

2. [Lasso Regression]

3. [Ridge Regression]


## Conclusion
<hr>

- All 3 Models were quite similar. The team has decided that any of the 3 models are good indicators of 

- 

## Learning Points
<hr>

- 

- 
