# Weather Data Analysis Using NumPy, Pandas, and Matplotlib

## 1. Introduction

Weather data analysis plays an important role in understanding climate patterns, seasonal variations, and environmental changes. By analyzing historical weather data, analysts can identify trends in temperature, humidity, and precipitation. In this project, historical weather data is analyzed using Python libraries such as **NumPy, Pandas, and Matplotlib**. The analysis focuses on cleaning the dataset, performing statistical calculations, and visualizing weather trends over time. The goal of this project is to demonstrate how data analysis techniques can transform raw weather data into meaningful insights.

---

## 2. Objectives

The main objectives of this project are:

- Load and inspect historical weather data using **Pandas**
- Clean the dataset and handle missing values
- Perform descriptive statistical analysis using **NumPy**
- Analyze monthly weather trends using **Pandas groupby**
- Visualize weather patterns using **Matplotlib**
- Identify extreme weather conditions using statistical techniques

---
## 3. Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## 4. Dataset Description

The dataset contains historical weather observations with the following variables:

| Column Name | Description |
|-------------|-------------|
| Date | The recorded date of the weather observation |
| Temperature | Daily air temperature value |
| Humidity | Percentage of moisture in the air |
| Precipitation | Amount of rainfall recorded on that day |

---

## 5. Data Cleaning and Preprocessing

The dataset was loaded using the **Pandas `read_csv()`** function and inspected using functions such as **`head()`**, **`info()`**, and **`describe()`**.

The dataset contains **1,096 records** with four variables: Date, Temperature, Humidity, and Precipitation.

Missing values were checked using **`isnull().sum()`**, and no missing values were found. The **Date column**, originally stored as a string, was converted to **datetime format** using `pd.to_datetime()` to enable time-based analysis.

After preprocessing, the dataset was clean and ready for analysis.

---

## 6. Exploratory Data Analysis & Insights

### 6.1 Descriptive Statistics of Weather Variables

Findings:

Temperature  
- Mean: 9.91 °C  
- Median: 9.06 °C  
- Standard Deviation: 11.74  

Humidity  
- Mean: 60.85%  
- Median: 60.48%  
- Standard Deviation: 17.37  

Precipitation  
- Mean: 3.47 mm  
- Median: 1.52 mm  
- Standard Deviation: 7.40  

Insight:

- Temperature shows high variability, indicating strong seasonal changes.
- Humidity remains relatively stable around 60%.
- Precipitation varies significantly, with occasional heavy rainfall events.

---

### 6.2 Monthly Temperature Trend

Findings:

- Temperatures increase from **January to March**.
- Peak temperatures occur during **March and April**.
- Temperatures gradually decline after **June**.
- The lowest temperatures are observed between **August and October**.

Insight:

The dataset shows clear **seasonal temperature variation** across different months.

---

### 6.3 Monthly Precipitation Pattern

Findings:

- Higher precipitation levels are observed in **February, April, November, and December**.
- Lower rainfall is observed during **May and September**.

Insight:

Rainfall distribution varies across the year, indicating periods of heavier and lighter precipitation.

---

### 6.4 Temperature Distribution

Findings:

- Temperature ranges from **-18.9 °C to 42.3 °C**.
- Most observations fall within moderate temperature ranges.

Insight:

The histogram visualization shows a wide spread of temperature values, reflecting both cold and warm periods.

---

### 6.5 Extreme Temperature Events

Findings:

- Several days recorded extremely **high temperatures above 34 °C**.
- Some days recorded extremely **low temperatures below -14 °C**.

Insight:

Extreme temperature events occur occasionally and represent unusual weather conditions.

---

### 6.6 Extreme Precipitation Events

Findings:

- Some days recorded **very high rainfall exceeding the 95th percentile**.
- A few events exceeded **50 mm of precipitation**.

Insight:

Although most days have low rainfall, the dataset includes occasional **heavy rainfall events**.

---

## 7. Key Insights

- Weather patterns show clear **seasonal temperature fluctuations** throughout the year.
- Average temperature is around **9.9 °C**, but values vary significantly.
- Humidity levels remain relatively stable across the dataset.
- Rainfall distribution is uneven, with some months experiencing higher precipitation.
- Several **extreme weather events** were identified, including unusually high temperatures and heavy rainfall.

---

## 8. Recommendations

- Monitor seasonal temperature trends to prepare for extreme weather conditions.
- Implement early warning systems for extreme temperature and heavy rainfall events.
- Improve rainfall monitoring during high-precipitation months.
- Use historical weather data for **predictive weather analysis**.
- Expand datasets with additional weather variables such as wind speed and air pressure.

---

## 9. Conclusion

This project analyzed historical weather data using **Python, NumPy, Pandas, and Matplotlib** to identify trends in temperature, humidity, and precipitation.

The analysis revealed clear **seasonal patterns**, stable humidity levels, and uneven rainfall distribution. Additionally, several **extreme weather events** were detected, demonstrating the variability in climate conditions.

Overall, the project demonstrates how data analysis techniques can transform raw weather data into meaningful insights that support climate understanding and decision-making.






