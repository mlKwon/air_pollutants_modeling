# ozone_no2_co_modeling
South Korea : monthly averages of O3, NO2 and CO concentrations during 2002~2020 at 1km x 1km grid resoultion.<br>

We used random forest, light gradient boosting and neural network algorithm for estimating those gaseous air pollutants.<br>
Now we are writing manuscript to submit to SCI-grade journal. <b4>

## about coding
I preprocessed the data by using Google Earth Engine (javascript base), SEDAC, and health-related determinants data using R and python. <br>
Modeling work is also carried out by R and python (+ pytorch). <br>

I shared the example code of Google Earth Engine on my github, so you can see how i extracted the features from Google Earth Engine roughly.<br>
Actually, this is just example code so we adjusted different shape file we made.<br><br>
link : https://github.com/mlKwon/GoogleEarthEngine_public
