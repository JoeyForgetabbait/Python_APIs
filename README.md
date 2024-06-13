# Weather_Vacation Py

## Code Path::
#### JoeyForetabbait/Python_APIs/Weather_Vacation_py
## Output Data Path::
#### JoeyForetabbait/Python_APIs/output_data

## Use python to generate weather data on cities globally, and pandas to analysze the data to locate the users(mine) most diserable vacation locations based on custom weather condition filters. 

#### When looking at the correlation betweeen weather conditions and geo location ('latitude' - N.H./S.H) there were some interesting, but seemingly logical/predictalbe results. Max Temperature and Latitude in the Northern Hemisphere had a shockingly largly negative correlation value, more likley because of the other weather events that brind down the temp in the N.H. The Southern Hemisphere however had R^2 value of 0.72, being a relatively strong correlation, which makes sense as the closer you get to the equator, and subsequently the Southern Hemisphere, the temperature rises. The correlation between humidity and laditude in the Northern Hemisphere is weak, which also makes sense, being that there is larger exposure to cool dry air in the Northern Hemisphere, while interestingly enough the correlation is also weak in the Southern Hemisphere regarding humdity. Cloudiness and laditiude in both the Northen and Southern Hemisphere had a weak correlation which is somewhat suprising as Southern Hemisphere locations usually go by the stereotype they are more sunny. Wind conditions and latidude in both Northern and Southern Hemisphere both had a weak correlation, but was slightly more positively correlated in the Northern Hemisphere which perhaps checks out when you concider the fact there is a larger clash of both cold and warm air in the Northern Hemisphere. The Vacation.py file uses tools to map geographic locations filtered by different weather conditions most optimal to the users preferance. 


## Global Cities Map Scaled by Humidity
<img width="1043" alt="Screenshot 2024-06-06 at 9 26 18 PM" src="https://github.com/JoeyForgetabbait/Python_APIs/assets/113046643/a0fff83e-0f67-4e4d-8579-552d5ace3383">

## Global Map of Hotels in Cities With the User's(mine) Optimum Weather Conditions. 
<img width="1031" alt="Screenshot 2024-06-06 at 9 26 32 PM" src="https://github.com/JoeyForgetabbait/Python_APIs/assets/113046643/9fe1dfbb-4254-47f3-9f23-8b3df1cbb407">
