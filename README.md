# Restaurant-Rating

## Overview
This project involves analyzing restaurant ratings in Mexico. The dataset includes information about restaurants, their cuisines, consumer demographics, preferences, and ratings. The goal is to provide insights to aid business entrepreneurs and investors in making informed decisions.

![Restuarant_Rating_](https://github.com/Ngozikah/Restaurant-Rating/assets/170735868/b9d962ef-3609-46e9-ae94-d4e651d39705)

***Data Description***
### consumer_preferences.csv
- **consumer_id**: Unique identifier for each consumer
- **preference**: Consumer preference details

### consumers.csv
- **consumer_id**: Unique identifier for each consumer
- **age**: Age of the consumer
- **gender**: Gender of the consumer
- **income**: Income level of the consumer

### ratings.csv
- **restaurant_id**: Unique identifier for each restaurant
- **consumer_id**: Unique identifier for each consumer
- **rating**: Rating given by the consumer

### restaurant_cuisines.csv
- **restaurant_id**: Unique identifier for each restaurant
- **cuisine**: Type of cuisine offered by the restaurant

### restaurants.csv
- **restaurant_id**: Unique identifier for each restaurant
- **name**: Name of the restaurant
- **Location**: Location of the restaurant
- **average_cost**: Average cost of a meal at the restaurant
- **total_reviews**: Total number of reviews

##Tools Used
-Power BI

## Analysis
### Question 1: Highest Rated Restaurants
- **Top-Rated Restaurants**
- Here are the top-rated restaurants based on the average overall ratings:
1.	Emilianos in San Luis Potosi - Average Rating: 2.0
2.	Michiko Restaurant Japones in San Luis Potosi - Average Rating: 2.0
3.	Restaurant Las Mañanitas in Cuernavaca - Average Rating: 2.0
4.	Cafe Punta Del Cielo in San Luis Potosi - Average Rating: 1.83
5.	La Estrella De Dimas in San Luis Potosi - Average Rating: 1.8

Here's the comparison of cuisines offered by top-rated restaurants against consumer preferences:
1.	Mexican Cuisine: Highly preferred by consumers (97 preferences) and offered by 3 of the top-rated restaurants. This indicates a strong alignment between what consumers prefer and what top-rated restaurants offer.
2.	Cafeteria Style: Found in one of the top-rated restaurants and has 9 consumer preferences.
3.	American Cuisine: Not found among the top-rated restaurants but has 11 consumer preferences.
4.	Pizzeria and Coffee Shop: These cuisines have some consumer preferences (9 and 8 respectively) but are not represented in the top-rated restaurants in our dataset.
This analysis suggests that while Mexican cuisine is both highly preferred and common among top-rated restaurants, other popular cuisines like American, Pizzeria, and Coffee Shop are not necessarily represented among the highest-rated establishments in this dataset.


### Question 2: Consumer Demographics
- **Demographic Analysis**:
•	Location: All consumers are from Mexico, with the majority (86 out of 138) from San Luis Potosi.
•	Age: Ranges widely from young to old.
**Detailed Demographic Attributes**
### Smoking: 109 consumers are non-smokers, 26 are smokers.
### Drinking Level:
51 consumers do not drink alcohol,
40 are social drinkers,
47 are casual drinkers.
### Transportation Method:
82 use public transportation,
42 use a car,
14 travel on foot.
### Marital Status:
124 are single,
10 are married.
### Children:
113 are independent (no children living with them),
11 have kids,
3 are dependent (living with parents).
### Occupation:
113 are students,
16 are employed,
2 are unemployed.
### Budget:
91 have a medium budget,
35 have a low budget,
5 have a high budget.

***Potential Biases and Observations***
•	Age Distribution: The presence of consumers across different age groups provides a diverse view, but specific data on age distribution would further clarify representativeness.
•	Location Bias: Given all consumers are from Mexico, and predominantly from San Luis Potosi, there's a geographic concentration that might limit the generalizability of findings to other regions or countries.
•	Marital Status and Children: The dataset is heavily skewed towards single individuals without children, which could impact preferences particularly relevant to family-friendly amenities or children's menus


### Question 3: Demand & Supply Gaps
 ***Cuisines with High Demand but Low Supply***
-Mexican Cuisine: High preference (97 consumers) with a significant gap in supply (only 28 restaurants offering it), suggesting a potential market opportunity for new or existing restaurants to focus more on Mexican cuisine.
-Coffee Shop: Preferred by 8 consumers but only available in 1 restaurant, indicating a possible niche for coffee-focused establishments.
-American Cuisine: Has a demand of 11 but a supply of only 5, pointing to a possible undersupply.
-Family Restaurants and Hot Dogs: Both have noticeable gaps where consumer interest exceeds the number of restaurants catering to these preferences.

***Cuisines with Oversupply****
-Bar Cuisine: 13 restaurants offer this cuisine, but only 3 consumer preferences, indicating a possible oversaturation in the market.
-Brewery: Offered by 6 restaurants but only preferred by 1 consumer.
-Fast Food: Although popular, with 5 consumer preferences, it is offered by 8 restaurants, suggesting a mild oversupply.

***Strategic Recommendations***
•	Expanding Mexican and Coffee Shop Offerings: Considering their high demand and relatively low supply, businesses could benefit from increasing their focus on these cuisines.
•	Reevaluating Bar and Brewery Investments: Given their lower preference rates relative to supply, current businesses may need to innovate or diversify their offerings to attract more customers.

### Question 4: Investment Characteristics
***- Key Characteristics for Successful Restaurant***
- Alcohol Service: Restaurants offering "Wine & Beer" tend to have higher ratings, especially when combined with a no-smoking policy. Full bars also tend to do well, particularly in closed areas with either no or valet parking.
- Smoking Policy: Generally, restaurants with no smoking allowed are rated higher than those with smoking sections, indicating a preference for smoke-free environments among the sampled consumers.
- Pricing Strategy: Interestingly, restaurants at both the low and high price points show high ratings, suggesting that both budget-friendly and premium dining experiences are valued. The middle price range tends to perform variably.
- Franchise vs. Independent: Both franchises and independent restaurants can achieve high ratings, but the top-rated spots are often non-franchised, suggesting that unique, independent restaurants might offer distinct qualities that resonate well with diners.
- Area and Parking: Closed areas (likely indicating indoor dining) and the absence of parking or valet parking seem to correlate with higher ratings. This could reflect a preference for dining experiences that are perceived as more exclusive or convenient


## Conclusion
The analysis of restaurant ratings in Mexico provided in this project offers significant insights for entrepreneurs and investors looking to enter or expand within the food and beverage industry. I identified key factors influencing consumer satisfaction and potential market opportunities based on the alignment or disparity between consumer preferences and the availability of certain cuisines. My findings indicate a strong market preference for Mexican cuisine, which, despite its popularity, remains underrepresented in the current restaurant offerings. This suggests a clear opportunity for new establishments or existing restaurants looking to diversify their menu options. Additionally, niche markets such as coffee shops also appear underserved and represent a potential area for growth. The demographic analysis reveals that our dataset predominantly represents young, single consumers from urban areas, particularly San Luis Potosi. This demographic trend underlines the importance of considering location-specific consumer preferences and the potential biases that may arise from a geographically concentrated dataset.
Furthermore, our strategic recommendations highlight the importance of aligning restaurant characteristics with consumer preferences, such as non-smoking policies and diverse alcohol service options, to enhance customer satisfaction and ratings.
By addressing these identified gaps between supply and demand and considering the detailed preferences and characteristics of their target market, entrepreneurs and investors can make more informed decisions, potentially leading to greater success in the competitive restaurant industry in Mexico. 
This project serves as a foundational analysis for those looking to capitalize on these insights, offering a data-driven approach to navigating the complex landscape of consumer preferences and market opportunities.
