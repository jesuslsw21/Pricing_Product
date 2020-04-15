# Mod_7_Final

Executive Summary

Brief 

Product pricing gets even harder at scale, considering just how many products are sold online. Clothing has strong seasonal pricing trends and is heavily influenced by brand names, while electronics have fluctuating prices based on product specs. They’d like to offer pricing suggestions to sellers, but this is tough because their sellers are enabled to put just about anything, or any bundle of things,
 
Introduction

In this Final Project, I gathered data from Mercari (Provided), an online peer-to-peer shopping mall, and develop a statistical model using item condition, shipping terms, brand, product category, and words used in the item title and description. my task is to to build an algorithm that automatically suggests the right product prices. 

Models

I tested three different models (Elastic Net, Ridge Regression, and LightGBM) against a ‘baseline’ model (which did not included any NLP features) to measure the effectiveness of NLP features on the basis of out-of-sample error. 

Findings

I find that the Ridge and Light GBM models achieve comparable performance before discussing tradeoffs between accuracy and ease of implementation. 

Finally, we conclude that both the Ridge and Light GBM perform significantly better than a baseline model without textual information from the item title and description, suggesting that there is tangible business benefit to including these NLP features when Mercari suggests prices to its customers. 

Conclusion.
We conclude by considering the limitations of our study and mentioning potential opportunity areas for future research.
