# **Restaurant Inspections Project**

![image](https://github.com/user-attachments/assets/7c016f6b-36b0-4ae3-bf70-beacceac4709)

*I do not own the rights to this photo*

## **Business Problem:**

This dataset includes NYC restuarant inpection data for the last three years prior to the most recent inspection and does not include restaurants that has gone out of business. Letter grading inspections were put on pause beginning March 17, 2020, until July 19, 2021, due to the COVID-19 public health emergency. Modified restaurant inspections occurred during this time. Restaurants are uniquely identified by their CAMIS number. Only restaurants that are currently active as of the date of this extraction are included in the dataset. Establishments with inspection date of 1/1/1900 are new establishments that have not yet received an inspection. These will be excluded from parts of the project. 

## **Methods**

- Using an API, I extracted Yelp data and merged it with Health Inspections data from city-wide inspections by the Department of Health in New York City for Pizza Resturants in Brooklyn.
- I only included YELP data specifically for pizza restaurants in Brooklyn,NY because, this helped to focus on a smaller dataset to search for correlation between the inspection scores and ratings.
- The use of feature engineering help to create multiple new columns in the dataset that help with gathering a more in-depth look into the data.
- Hypothesis testing was used to find out whether or not there was any correlation between better inspections scores mean better ratings on Yelp. I used Z-scores to help identify any outliers and elimnated them before performing two different hypothesis tests.
- I used multiple modeling techniques to represent the various aspects of my findings for Brooklyn Pizza Restaurants.
   
### **Data:**

https://catalog.data.gov/dataset/dohmh-new-york-city-restaurant-inspection-results

Yelp API!

## **Necessay links for understanding context within the data**

https://www.nyc.gov/site/doh/business/food-operators/letter-grading-for-restaurants.page

https://www.nyc.gov/assets/doh/downloads/pdf/rii/restaurant-grading-faq.pdf

## **NYC Inspection EDA:**

![image](https://github.com/user-attachments/assets/e7c61d9f-1b1c-4e2c-a38a-21c89c43b7b4)

![image](https://github.com/user-attachments/assets/671d829c-0f28-4ee5-8a47-1254a19b5939)

![image](https://github.com/user-attachments/assets/1c8b8a20-58f3-4d48-b276-8f378d7cf3f3)

![image](https://github.com/user-attachments/assets/80c2d8e3-471b-4970-87cc-973027f23b58)

![image](https://github.com/user-attachments/assets/ec18a675-b1a7-4332-b0f3-386613331501)

**Correlation Map between Review_Counts and Score**

![image](https://github.com/user-attachments/assets/9ee029a3-65f0-476d-8d92-6baea85e9c36)

**Correlation Map between Ratings and Review_Counts**

## **Results**

Unfortunately, there was no significant correlation found. Many different visualization tools such as matplotlib, seaborn, and pandas were used to display the data in a way that Non-Data Scientist can read. I included a Geospatial Visualization to show the complexity of my findings in a fun way!


## **Recommendations:**

## **Limitations and Next Steps**

## **Link to Notebook:**
