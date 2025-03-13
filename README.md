# **DSA210-Project**

## **Overview**

Understanding personal shopping behavior can reveal significant insights about decision making patterns that influence spending habits. By analyzing my own purchases, I aim to identify the key factors that drive my choices as a consumer. This analysis will look at how time patterns, physiological cycles and outside influences such as discounts impact my purchases. By gaining these insights, I hope to develop more mindful and intentional spending habits that align with my financial and personal goals.
***
## **Project Goal**
By tracking when I shop, what I spend across different categories, and potential influences including my menstrual cycle, I aim to develop insights into my consumer psychology and create strategies for making more intentional purchasing decisions. With the data I get from my credit card transactions, these hypotheses will be tested:

### **Hypotheses**

* H0 (Null Hypothesis): My spending on clothing is proportionally distributed and does not significantly vary based on external factors such as time of the month, discounts or hormonal cycle.

* H1 (Alternative Hypothesis): My spending on clothing is significantly influenced by factors such as time of the month, discounts or hormonal cycle.
---
## **Data Sources and Preprocessing**
This study will focus exclusively on my own shopping data, collected from 2024 through May 2025.


### Primary Data Collection


The dataset will be built using three main sources: transaction records, order confirmations and menstrual cycle tracking data from the period tracker app Flo. Item characteristics such as product name, original price and discount details will be gathered from transaction records and order confirmations from e-commerce platforms. Only spending on clothing will be analyzed to examine how factors like time of the month, discounts and other influences affect my purchasing decisions.

### Data Structure

The dataset will include these variables:


* Purchase date: The exact date the purchase was made.
* Day of the week: Which day of the week the purchase was made.
* Item name: The name of the purchased clothing item.
* Price: The price of the item.
* Discount amount: Any discount applied to the item (if applicable).
* Hormonal cycle: Whether I was on my period or not on the date of purchase (tracked through the Flo app).
