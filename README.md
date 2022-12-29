# Amazon Vine Analysis 

## Overview

The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. This program is a service that allows manufacturers and publishers to receive reviews for their products. There are many different review datasets for this analysis, however, Amazon Kitchen Department Review Dataset was chosen for this analysis.

## Analysis

The first part of this analysis includes looking at Vine(***Paid***) and Non-Vine(***Unpaid***) reviews. This is an essential part of the analysis as we'll see the relationship of the reviews dependeing on being paid vs unpaid. 

In order to identify the paid and unpaid Vines, the dataset needed to be filtered accoridngly. By filtering the dataset to have **total_votes** of more than 20 it was ensured the dataset is helpful. Furthermore, all rows that contained **helpful_votes** divided by **total_votes** of equal to or greater than 50% were retrieved. 

Based on the filtered data, there were **1207** Vine and **97839** Non-Vine Reviews:

<img width="483" alt="Screenshot 2022-12-29 at 2 10 47 AM" src="https://user-images.githubusercontent.com/111609994/209936608-c6229076-a1c8-413a-b345-509c778fd748.png">

In addition, it was essential to understand which **5-star** reviews were paid and which ones were unpaid. Out of all the **five-star** data, only 509 were Vine, the rest, ***45,858*** were Non-Vine.

<img width="974" alt="Screenshot 2022-12-29 at 2 13 21 AM" src="https://user-images.githubusercontent.com/111609994/209936957-cb26a64b-efa3-4204-a61b-f2f64778a018.png">

Based on this, another question that occurs is to retrieve the percentage of non-Vine and Vine five star reviews. Here we can see that ***Paid***, Vine reviews were only 1.1% of the all five-star reviews, while non-Vine reviews were 98.9% of the total five-star reviews:

<img width="793" alt="Screenshot 2022-12-29 at 2 16 26 AM" src="https://user-images.githubusercontent.com/111609994/209937195-8cb52f6a-e44c-4925-8fbb-60cca8ea1a43.png">

## Summary

From this analysis it is clear that the non-Vine reviews outnumber the Vine reviews by a huge number. From this dataset that was filtered to have mostly helpful reviews, non-Vine reviews were ***97,839*** compared to Vine reviews of ***1,207***. In addition, the dataset was further filtered to include only ***Five Star*** reviews to understand the satisfaction among customers. Here, we can also observe a huge difference between Non-Vine (**45,858**) and Vine(**509**) Reviews. Based on such a huge difference between paid and unpaid Vines and their percentages (**1.1%** AND **98.9%** respectively), we can clearly state that there is no **positivity bias** for reviews in Vine program. Most of the reviews and most of the five star reviews as well are left by unpaid invdividuals. 
