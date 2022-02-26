# Data-Analysis-Weather/Rainfall dataset


Weather forecasts and analysis are made by collecting as much data as possible about the current state of the atmosphere (particularly the temperature, humidity, and wind) and using an understanding of atmospheric processes (through meteorology) to determine how the atmosphere evolves in the future.

## Project Synopsis

>> This repo contains Data Cleaning, Exploratory Data Analysis, and Data Visualization of Weather/Rainfall dataset taken from the Kaggle website  [Click here](https://www.kaggle.com/).

-------------------------------
## Project Walk-through

### Data Collection

Weather/Rainfall dataset taken from the Kaggle website consisted of 23 attributes and 14.5K tuples, the attributes are: Date, Location, MinTemp, MaxTemp, Rainfall, Evaporation, Sunshine, WindGustDir, WindGustSpeed, WindDir9am, WindDir3pm, WindSpeed9am, WindSpeed3pm, Humidity9am, Humidity3pm, Pressure9am, Pressure3pm, Cloud9am, Cloud3pm, Temp9am, Temp3pm, RainToday, RainTomorrow



------------------------------


## Data Cleaning

After collecting the data, filling values were handled using mean (For numerical variables), median (For numerical variables), and mode (For categorical variables). Changes I made and what all variables & scripts I wrote:

    * Converted Date to Datetime format
    * Column for description length

-------------------------------
## EDA {Exploratory Data Analysis}

* All the imported distributions from the data cleaning data-set, I looked at the distributions of the data and the value counts for the various numerical and categorical variables.
* Using **Matplotlib & Seaborn**, categorized and crafted a beautiful data visualisation charts & plots
* Below are a few highlights from the *Pivot tables, Barplots & HeatMaps*.

![image](https://user-images.githubusercontent.com/98012611/155759203-4947f3f8-0b17-440a-849d-22a1cbfdbc86.png)

![image](https://user-images.githubusercontent.com/98012611/155759323-f713041a-b287-4f16-bc76-2264d80d2975.png)

![image](https://user-images.githubusercontent.com/98012611/155759399-cb6b68b1-276c-477c-97d8-d49a608fb1a3.png)


-----------------


## Resources Consumed for this project & where you can find them:

    Python Ver: 3.9.0
    Packages Used: Pandas, Numpy, Matplotlib, and Seaborn.

* Matplotlib Documentation: [Click here](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.boxplot.html?highlight=boxplot#matplotlib.pyplot.boxplot)
* Seaborn Documentation: [Click here](http://seaborn.pydata.org/examples/many_pairwise_correlations.html)

-----------------------------
