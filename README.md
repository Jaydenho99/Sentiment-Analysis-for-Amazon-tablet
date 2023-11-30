# Exploring Tablet’s Online Reviews’ Sentiment from Amazon using N-gram and Part of Speech

## Overview
The popularity of e-commerce has caused the internet to become the best source to collect consumer opinions. Online retailers such as Amazon.com, Shopee, and Lazada have provided a convenient way for consumers to make remark on their products bought by giving ratings or writing a comment. Consumer reviews are essential to online retailers, product manufacturers, and shopping providers to improve their customer services and products based on the customer’s online reviews on the features and quality of the products sold. Besides that, online reviews provide valuable information for future consumers to enhance their decision-making efficiency. Hence, proper analysis and classification of consumer’s reviews enable potential consumers, retailers, and product manufacturers to visualize consumer’s positive, neutral, and negative feedback on the services and specific features of the products.

## Dataset
A sample of large datasets related to Amazon products’ online reviews is collected from Kaggle. This dataset consists of more than 34,000 rows and 21 columns of consumer reviews for Amazon products such as Kindle, Fire TV, and many more. Those data are collected from the year 2015 to 2017 in Amazon and compiled to form a large dataset. In this research, only 5000 rows of data and a single column related to reviews text are extracted to perform sentiment analysis. All the online reviews extracted are related to the Amazon tablet. Amazon is chosen as a platform for online reviews extraction because Amazon consists of approximately 310 million active users worldwide and consists of a large customer base that speaks and writes a comment in English. The research on the sentiment analysis of English online reviews for Amazon tablets is our main goal.

## Method to perform Sentiment Analysis
1. N-grams :
A feature extraction usually refers to the extraction of a consumer’s concern on a product in an online review to discover the strength and weaknesses of a product. Each of the product reviews usually consists of only adjectives, nouns, and verbs after data preprocessing. To extract important features from online reviews, the concept of N-gram is used because N-gram is useful for turning written language into data and breaking down a larger portion of data into more meaningful segments or features

![image](https://github.com/Jaydenho99/Sentiment-Analysis-for-Amazon-tablet/assets/77521676/d3c874cc-c3b5-473f-8d90-d651993700d9)
![image](https://github.com/Jaydenho99/Sentiment-Analysis-for-Amazon-tablet/assets/77521676/8048fbc9-ced7-4a31-aed8-7d1c8725e26c)
![image](https://github.com/Jaydenho99/Sentiment-Analysis-for-Amazon-tablet/assets/77521676/ca1adb76-70d5-4192-bc59-8e4208ef8a88)

2. Part of Speech :
Part of Speech (POS) tagging is one of the useful methods to extract subjective information from online reviews by assigning grammatical rules for every word of a sentence.Some of the POS tagged are DT(determiner), NN(noun), RB(adverb), VB(verb), CC(coordinating conjunction), JJ(adjective), etc. Then, each word of the POS tagged words is mapped to WordNet tags accordingly
![image](https://github.com/Jaydenho99/Sentiment-Analysis-for-Amazon-tablet/assets/77521676/d464ff4d-de9e-434e-af5c-90fb9ba11164)
