**Introduction**:

Welcome to the world of OYO Rooms, where comfort meets affordability. In this data-driven journey, we'll explore the fascinating landscape of OYO hotels across 10 vibrant cities in India. From luxurious retreats to budget-friendly stays, OYO offers a diverse range of accommodations tailored to suit every traveller's needs.

**Data Description**:

The dataset comprises information about OYO hotel rooms, scraped from the OYO website using the BeautifulSoup package in Python. It includes the following features: 
1.	Hotel Name: The name of the hotel.
2.	Area: The location or area where the hotel is situated.
3.	Original Price: The original price of the hotel room before any discounts or promotions.
4.	Discounted Price: The price of the hotel room after applying discounts.
5.	User Rating: The rating given by users for the hotel.
6.	Total Ratings: The total number of ratings received by the hotel.
7.	Region: The region or city where the hotel is located.
8.	Rating Summary: A summary of user ratings, such as 'Excellent', 'Very Good', 'Good', etc.
9.	Hotel Category: The category of the hotel, which could include 'Flagship', 'Super OYO', 'Collection O', 'OYO Hotels', etc.
10.	Tax Additional: The additional charges of the hotel room.
11.	Region: The city in which the OYO located.
12.	Amenities: list of amenities 

**Target Variable**:

The target variable in this problem is the Discounted Price.

**Problem Statement**:

Using a dataset scraped from the OYO website, the goal is to predict the discounted price for hotel rooms using machine learning algorithms. The dataset contains various features related to hotel properties, including location, original price, hotel category, user ratings, and more. By leveraging the available information, we aim to build a predictive model that can accurately estimate the discounted price of OYO hotel rooms

**Insights**:

Overview:

•	The dataset comprises 1960 hotel rooms.
•	The average original price is ₹3889, while the average discounted price is ₹917.

City Insights:

•	Hyderabad boasts the highest count of hotels, followed by Delhi and Bangalore.
•	Delhi leads in the number of flagship category hotels, with 107 out of 281 total hotels.

Hotel Categories:

•	The flagship category dominates, with 501 hotels, followed by others with 455 and collection with 352.
•	Among the hotel categories, 'very good' is the most common rating summary, received by 665 hotels.

Region-wise Analysis:

•	Jaipur's Raja Park hosts the only Palette hotel, offering premium amenities and services.

Price Analysis:

•	Palette - Madhogarh commands the highest price, ₹4567 + ₹588 tax, reflecting its premium status.
•	On the other hand, SPOT ON Sunshine Hotel in Jaipur's Govind Nagar offers the lowest price, ₹399 + ₹78 tax, catering to budget-conscious travellers.

**Recommendations**:

For Customers:

•	For travellers seeking luxury and upscale amenities, Palette hotels offer an unparalleled experience. Madhogarh in Jaipur is a top recommendation.
•	Budget-conscious travellers can opt for SPOT ON hotels like Sunshine Hotel for affordable yet comfortable stays.

For OYO:

•	OYO should continue to expand its flagship category, which enjoys popularity across all cities, ensuring consistent quality and affordability.
•	Emphasize the uniqueness and exclusivity of Palette hotels to attract premium clientele, focusing on personalized experiences and top-notch services.

**Conclusion**:

OYO Rooms stands as a beacon of hospitality, offering a diverse array of accommodations tailored to meet the diverse needs and preferences of travellers. Whether you seek luxury, affordability, or something in between, OYO has something for everyone, ensuring memorable stays and delightful experiences. 

**Dashboards**:

![OYO 1](https://github.com/VasumathyApparsundar/OYO-ROOMS/assets/167323908/fb791ace-9fcb-479b-a2ce-a634303847f0)

![OYO 2](https://github.com/VasumathyApparsundar/OYO-ROOMS/assets/167323908/e237d5dc-210a-4f27-9a3d-9dbb3e34fe49)

![OYO 3](https://github.com/VasumathyApparsundar/OYO-ROOMS/assets/167323908/ab35f060-b0fa-4b76-b048-c34fec196920)

![OYO 4](https://github.com/VasumathyApparsundar/OYO-ROOMS/assets/167323908/6b0a1ade-87b2-4fc6-9fd4-467a0d2979fc)


**Machine Learning Outcomes**:

After applying various machine learning algorithms to the OYO Rooms dataset, including Linear Regression, Decision Tree, Random Forest, and XGBoost, we obtained the following results:

Linear Regression:

R-squared value: 0.86
This indicates that our linear regression model explains approximately 86% of the variance in the discounted prices of OYO hotel rooms. With such a high R-squared value, linear regression appears to be the best-suited model for predicting discounted prices in this dataset.

Decision Tree, Random Forest, and XGBoost:

While the R-squared value for linear regression was 0.86, the performance of other algorithms such as Decision Tree, Random Forest, and XGBoost may vary.
Further analysis and fine-tuning may be required to optimize these algorithms and improve their predictive accuracy.

Overall, the linear regression model demonstrates strong predictive power in estimating the discounted prices of OYO hotel rooms based on the available features in the dataset.

![image](https://github.com/VasumathyApparsundar/OYO-ROOMS/assets/167323908/5f33ee8d-135e-4d43-8913-3065cc9728eb)

**Overview of Streamlit App for OYO Room Price Prediction:**

This Streamlit app provides a user-friendly interface to predict OYO room prices based on various factors, enhancing accessibility and usability for your project.

Purpose: The Streamlit app predicts the discounted price of OYO rooms based on user input.

Inputs: Users can input the area, user rating, total ratings, region, rating summary, and hotel category.

Processing: The app preprocesses user inputs, converts categorical data into numerical format, and scales the input data using a StandardScaler.

Prediction: Using a pre-trained Linear Regression model, the app predicts the discounted price of the OYO room.

Output: The app displays the predicted price to the user.

![image](https://github.com/VasumathyApparsundar/OYO-ROOMS/assets/167323908/16f05fc6-6830-4cca-a585-4f87022127d9)



