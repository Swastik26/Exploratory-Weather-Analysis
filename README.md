# EDA on Weather Data ☁️🌦️

## Introduction 🌍
This project provides a comprehensive Exploratory Data Analysis (EDA) on a weather dataset 🌡️. The primary goal was to uncover meaningful insights from variables like temperature 🌡️, humidity 💧, pressure 🌬️, wind speed 💨, and precipitation 🌧️.

## Data Overview 📊
The dataset contains weather observations across multiple locations, including:
- **Temperature** (°C) 🌡️
- **Humidity** (%) 💧
- **Pressure** (hPa) 🌬️
- **Wind Speed** (km/h) 💨
- **Precipitation** (mm) 🌧️
- **Date** (timestamp) 📅

## Data Quality and Preprocessing 🔧
- **Missing Data**: Missing values were handled by imputing using mean for temperature and median for humidity 🔍.
- **Outliers**: Extreme values were detected in wind speed 💨 and precipitation 🌧️ and appropriately managed.
- **Data Transformation**: The date column was transformed into datetime format, creating new features like day of the week and month 📅.

## Data Distribution 📈
- **Temperature**: The average temperature was **22°C** 🌡️, with a range from **-5°C** to **38°C** 🌞.
- **Humidity**: Values ranged from **40%** to **90%** 💧, with **60%** being the most frequent.
- **Pressure**: Average atmospheric pressure was **1012 hPa** 🌬️, with extremes between **1005 hPa** and **1020 hPa**.
- **Wind Speed**: Right-skewed, with most values under **20 km/h** 💨; extreme values reached **60 km/h**.
- **Precipitation**: **60%** of the observations recorded **0 mm** 🌧️, while heavy rainfall above **50 mm** occurred only **3%** of the time.

## Key Insights 🔍

### Correlation Analysis 🔗
- **Temperature vs Humidity**: A moderate negative correlation of **-0.6** suggests that as temperature 🌡️ rises, humidity 💧 decreases.
- **Temperature vs Pressure**: A weak positive correlation of **0.3** 🌬️ shows that higher temperature slightly increases pressure.
- **Wind Speed vs Precipitation**: A positive correlation of **0.5** 💨🌧️ indicates higher wind speeds are associated with precipitation.

### Distribution of Variables 🧑‍💻
- **Temperature**: **40%** of data had temperatures between **20°C** and **25°C** 🌡️.
- **Humidity**: **30%** of data recorded humidity levels between **60%** and **70%** 💧.
- **Wind Speed**: **50%** of the observations showed wind speeds under **10 km/h** 💨.
- **Precipitation**: **60%** recorded no precipitation 🌧️, while heavy rainfall occurred in only **3%**.

### Seasonal Trends 🌞❄️
- **Temperature and Humidity**: Temperature peaked in **June, July, and August**, while humidity was highest in the summer months 🌞.
- **Precipitation**: Precipitation was most frequent from **June to September**, aligning with the monsoon season 🌧️.

### Extreme Weather Events ⚡
- **Temperature Extremes**: The lowest recorded temperature was **-5°C** 🌨️, and the highest reached **38°C** 🌞.
- **Heavy Rainfall**: **50 mm** of rainfall was recorded only **3%** of the time 🌧️.
- **High Wind Speeds**: Wind speeds above **50 km/h** 💨 were recorded in just **2%** of data, coinciding with storms.

## Contributions 💡
I was responsible for:
- **Data Cleaning**: I handled missing values and outliers, ensuring the integrity of the dataset 🔧.
- **Feature Engineering**: I created new features like day of the week 📅 and month to uncover seasonality patterns 🌦️.
- **Data Visualization**: I created histograms, boxplots, and heatmaps to communicate insights effectively 📊.
- **Statistical Analysis**: I performed correlation analysis and identified key seasonal trends 🔍.

## Conclusion 🎯
This EDA highlighted key patterns in the weather dataset 🌡️, including relationships between temperature and humidity, seasonal variations, and the distribution of extreme weather events ⚡. This analysis forms a strong base for predictive modeling and further climate studies 🌍.

## Contact Me 📬
Feel free to reach out if you have any questions, suggestions, or need help with similar projects! I’m happy to connect and assist:
- **Email**: [swastikchattopadhyay.2024@gmail.com](mailto:swastikchattopadhyay.2024@gmail.com) 📧
- **Twitter**: [SWASTIKCHA43552](https://x.com/SWASTIKCHA43552) 💻
- **LinkedIn**: [swastik-chattopadhyay-398551251](https://www.linkedin.com/in/swastik-chattopadhyay-398551251/) 👔

