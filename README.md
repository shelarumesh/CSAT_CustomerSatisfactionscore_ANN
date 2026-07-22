# CSAT_CustomerSatisfactionscore_ANN


### Project Overview

* **Project Title**: The project is titled "EDA and DL on Customer Data".


* **Author**: The analysis and modeling were completed individually by Umesh Prakash Shelar.


* **Main Objective**: The goal is to predict Customer Satisfaction (CSAT) scores in real-time for an e-commerce platform named Shopzilla without relying on post-interaction surveys.



---

### Key Data Insights

* **Dataset Size**: The dataset contains 85,907 customer support interactions spread across 20 different data columns.


* **Score Distribution**: Customer ratings are mostly positive, with 69.39% of the tickets receiving a perfect CSAT Score of 5.


* **Speed Matters**: Slower response times directly lead to unhappy customers. Tickets with the lowest scores (1 or 2) had an average response time of over 215 minutes. Tickets with the highest scores (5) had an average response time of only 95 minutes.


* **Support Channels**: Inbound calls make up about 79.3% of the volume and have high satisfaction rates. Outbound calls (Outcall) perform the worst, with an average score of 3.98.


* **Trouble Areas**: Inquiries about Returns and Refunds cause the most customer frustration, resulting in the lowest average CSAT scores.


* **Agent Experience**: Highly experienced agents (over 90 days on the job) receive significantly higher CSAT scores than new agents who are still in training.



---

### Machine Learning Models

* **Tested Algorithms**: The project experimented with three main models: a Baseline Deep Learning Artificial Neural Network (ANN), a Random Forest Classifier, and an XGBoost Multi-Class Classifier.


* **The Winner**: An Optimized Deep Learning Artificial Neural Network (ANN) was chosen as the final prediction model.


* **Why It Won**: The Optimized ANN was selected because it is highly skilled at finding complex patterns between mathematical data (like wait times) and unstructured text (like customer remarks).


* **Ready for Use**: The final model and its preprocessing tools were saved into export files (such as `.keras` and `.joblib`) so they can be deployed onto a live business server.
