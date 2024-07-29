# London-Bike-Sharing

Urban mobility is more than just getting from point A to point B—it's about ensuring that cities are accessible, efficient, and sustainable for everyone. In today's world, analyzing data related to transportation options like bike-sharing can provide valuable insights into how people move around urban environments. By understanding the patterns and factors that influence urban mobility, we can design better infrastructure, reduce traffic congestion, improve public health, and make our cities more livable.

Bike-sharing, in particular, offers a green alternative to traditional modes of transportation, reducing carbon emissions and promoting a healthier lifestyle. Through data analysis, we can optimize bike-sharing systems, ensuring they meet the needs of residents and visitors alike. This project on London Bike Sharing aims to contribute to a broader understanding of urban mobility and support the development of smarter, more sustainable cities.

🛠️ Project Highlights:

Data Sources: The dataset includes information from Kaggle: https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/, weather data from The data encompasses factors like temperature, humidity, wind speed, and more, influencing bike usage.



EDA in Tableau: Tableau's intuitive and powerful visualization capabilities made it easy to explore the data and uncover patterns. From seasonal trends to weather impacts on bike-sharing, Tableau provided a clear and insightful way to present the findings. Check out the dashboard here: https://public.tableau.com/app/profile/ayushi.walia/viz/LondonBikeSharingEDA/Dashboard1



Model Building with XGBoost: XGBoost was utilized to predict the number of bikes used per hour. Its ability to handle large datasets and complex relationships made it an ideal choice for this task. By incorporating features like weather conditions, holidays, and weekends, the model provides accurate predictions, aiding in better decision-making for bike-sharing services.



🔍 Key Fields in the Data:

timestamp: Grouped by hour

cnt: Number of new bike shares

t1 & t2: Real and feels-like temperature

hum: Humidity percentage

wind_speed: Wind speed in km/h

weather_code: Weather category (e.g., clear, cloudy, rain)

is_holiday & is_weekend: Indicators for holidays and weekends

season: Meteorological seasons


# The data is acquired from 3 sources:

Https://cycling.data.tfl.gov.uk/ 'Contains OS data © Crown copyright and database rights 2016' and Geomni UK Map data © and database rights [2019] 'Powered by TfL Open Data'
freemeteo.com - weather data
https://www.gov.uk/bank-holidays
From 1/1/2015 to 31/12/2016
