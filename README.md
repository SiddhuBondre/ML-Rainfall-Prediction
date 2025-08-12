🌧️ Rainfall Prediction using Machine Learning

📌 Objective

The objective of this project is to predict whether it will rain using daily recorded weather data.
We use a Random Forest Classifier to learn patterns between meteorological parameters and rainfall occurrence.

📂 Dataset

Source: Custom daily weather observations

Format: CSV file with the following columns:

Column                                                                 Description 

day	                                                            Day number in the dataset

pressure	                                                      Atmospheric pressure (hPa)

maxtemp                                                       	Maximum temperature (°C)

temparature	                                                    Average daily temperature (°C)
mintemp	                                                        Minimum temperature (°C)
dewpoint                     	                                  Dew point temperature (°C)
humidity	                                                      Relative humidity (%)
cloud                                                         	Cloud cover (%)
rainfall                     	                                  Target variable (Yes/No)
sunshine	                                                      Sunshine duration (hours)
winddirection                                                   Wind direction (degrees)
windspeed	                                                      Wind speed (km/h)
