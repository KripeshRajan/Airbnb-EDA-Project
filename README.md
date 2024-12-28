
# Airbnb EDA Project with Python
![download](https://github.com/user-attachments/assets/960b58a3-a509-4928-ad62-574f2048d99f)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on New York Airbnb data to uncover trends and patterns in rental listings.  Using libraries like **Pandas, Numpy, Matplotlib, Seaborn**for cleaning, visualization, and analysis. 

## Objective
The goal of this project is to:
-  Analyze **room types, prices, and availability** across different neighborhoods.
-  Understand **host behavior** and listing patterns.
-  Detect potential **outliers** in prices.
-  Provide recommendations for guests and hosts based on insights.
## Project Files

- **airbnb_project.ipynb**
- **airbnb_project.pdf**



## Tools and Libraries
This project utilizes the following Python libraries:
- **Pandas**: Data manipulation and analysis.
- **Matplotlib** : Static data visualizations.
- **Seaborn**: Static data visualizations.
- **NumPy**: Numerical computations.




## Visualizations and Insights
 **Price Distribution**

![img1](https://github.com/user-attachments/assets/1e3cb9ff-0807-49c7-82cf-3c13dc6b3c39)
- A significant proportion of Airbnb listings are priced between `$0` and `$200`, indicating a prevalence of relatively affordable options.

**Price per Bed by Neighbourhood Group**




![img3](https://github.com/user-attachments/assets/3d1ec8d8-f7c8-43c5-a68a-6337dd8ac74e)

- The average price per bed in `Manhattan` is significantly higher compared to other neighborhood groups, exceeding `$140`. This indicates that `Manhattan` is the most expensive area for Airbnb accommodations, likely due to its prime location, tourist attractions, and high demand.


**Price per Bed by Room Type**


![img4](https://github.com/user-attachments/assets/b4e5fdf0-40ed-483e-aa23-b63a25d3c67b)
- `Hotel rooms` command the highest price per bed, exceeding `200 $`, making them the most expensive accommodation type on Airbnb. Conversely, `shared rooms` offer the lowest price per bed, at just over `50 $`, representing the most budget-friendly option.

**Variation in Price per Bed Across Neighbourhood Groups and Room Types**

![img5](https://github.com/user-attachments/assets/3f4d6674-9f37-4608-b30e-19c065e68879)

- `Neighbourhood group` and room type significantly impact the price per bed on Airbnb
- `Manhattan` is generally more expensive than other neighbourhoods for all room types
- `Shared rooms` offer the most affordable option, while `hotel rooms` are the most expensive

**Impact of Number of Reviews on Price Across Different Neighbourhood Groups**


![img6](https://github.com/user-attachments/assets/f3485a4a-2a15-409c-b6f5-4baa6111e4b5)


- Most listings have prices concentrated in the lower range (`0-400 $`). Listings with higher prices (`above 400 $`) are less frequent and tend to have fewer reviews.
- Across all neighbourhood groups, the `number of reviews decreases as the price increases`. This suggests that more affordable listings tend to receive more reviews, possibly due to higher occupancy rates.


**Exploring Relationships Between Listing Characteristics by Room Type**

![img9](https://github.com/user-attachments/assets/670f3473-7332-4675-aeb3-c854c3196a6f)






**Geographical Distribution of Airbnb Listing**

![img6](https://github.com/user-attachments/assets/1c918f64-fbd3-4bf3-bc72-f602d1d46ab1)

-  `Concentration of Listings:`The majority of Airbnb listings are concentrated in specific areas, particularly in `Manhattan` and `Brooklyn`. These boroughs show a high density of listings, indicating their popularity among hosts and guests

- `Room Type Distribution:` `Entire homes/apartments` (orange dots) and`private rooms` (blue dots) are the most common types of listings. `Shared rooms` (red dots) and `hotel rooms` (green dots) are less frequent.

- `Entire homes/apartments` and `private rooms` are densely packed in certain regions, showing their prominence in the Airbnb market.

**Correlation Matrix of Airbnb Listing Features**

![img8](https://github.com/user-attachments/assets/18790857-6af7-4dcc-a438-78da0786594c)

- `Price and Beds:` There's a moderate `positive correlation (0.42)` between `price` and the `number of beds`. This indicates that listings with more beds tend to have higher prices
- There's a moderate `negative correlation (-0.044)` between `price` and `number of reviews`. This suggests that as price increases, the number of reviews tends to decrease.



## Recommendations
- **For Guests**: 
   - Look for listings with high availability and good reviews for a better experience.
   - **Private rooms** in Brooklyn offer affordable stays compared to Manhattan.

- **For Hosts**:  
   - Improve **availability** and **review response rates** to attract more bookings.
   - Manage pricing effectively to compete within the borough's market.

