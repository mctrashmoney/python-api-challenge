# WeatherPy

## WeatherPy Notebook
* Compares the R^2 Values of each hemisphere in latitude compared to:
  * Temperature
  * Humidity
  * Cloudiness
  * Wind Speed
### In here I added the R-Value to the R^2 Value to show in numeric terms if it was a positive or negative correlation.
  * Includes all eight plots.

## VacationPy Notebook
* Loads the CSV file with the weather and coordinates data for each city and is read as `citi_data_df`
* Map displaying a humidity in each city is displayed using the `city_data_df` dataframe.
* After this, the cities are narrowed down to a specific subset: 
  * Max Temperature ranging between 20 and -10 with 
  * High humidity: greater than or equal to 30%
  * Zero cloudiness
* The `hotel_df` dataframe is loaded up with the criteria above and removed of any null values and found that there were no hotels within 10000 meters of the selected coordinates.
* The results were put into an interactive plot showing the selected cities, showing the humidity, the hotels, and the country.