# **Restaurant Inspections Project**

![image](https://github.com/user-attachments/assets/7c016f6b-36b0-4ae3-bf70-beacceac4709)

*I do not own the rights to this photo*

## **Business Problem:**

This dataset includes NYC restuarant inpection data for the last three years prior to the most recent inspection and does not include restaurants that go out of business. Letter grading inspections were put on pause beginning March 17, 2020, until July 19, 2021, due to the COVID-19 public health emergency. Modified restaurant inspections occurred during this time. Restaurants are uniquely identified by their CAMIS number. Only restaurants that are currently active as of the date of this extraction are included in the dataset. Establishments with inspection date of 1/1/1900 are new establishments that have not yet received an inspection. These will be excluded from parts of the project. 

##**Methods**

- Using a API, I extracted Yelp data and merged it with health inspections data from city-wide inspections by the department of health in New York City for Pizza Resturants in Brooklyn.
- I only included YELP data specifically for pizza restaurants in Brooklyn,NY. This helped to focus on a smaller dataset to search for correlation between the inspection scores and ratings.
- The use of  feature engineering help to create multiple new columns in the dataset that help with gathering a more in-depth look into the data.
- Hypothesis testing was used to find out whether or not there was any correlation between better inspections scores mean better ratings on Yelp. I used Z-scores to help identify any outliers and elimnated them before performing two different hypothesis tests.
- I used multiple modeling techniques to represent the various aspects of my findings for Brooklyn Pizza Restaurants.
   
### **Data:**

https://catalog.data.gov/dataset/dohmh-new-york-city-restaurant-inspection-results

Yelp API!

## **Necessay links for understanding context within the data**

https://www.nyc.gov/site/doh/business/food-operators/letter-grading-for-restaurants.page

https://www.nyc.gov/assets/doh/downloads/pdf/rii/restaurant-grading-faq.pdf

## **Results**

Unfortunately, there was no significant correlation found. Many different visualization tools such as matplotlib, seaborn, and pandas were used to display the data in a fun way that Non-Data Scientist can read. I included a Geospatial Visualization to show the complexity of my findings.

### Model 1

### Model 2

## **Describe Your Final Model**

## **Recommendations:**

## **Limitations and Next Steps**

## **Link to Notebook:**
