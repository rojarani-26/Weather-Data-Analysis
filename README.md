# 🌦 Weather Data Analysis Using NumPy, Pandas, and Matplotlib


## 📌 Introduction

Weather data analysis plays an important role in understanding **climate patterns, seasonal variations, and environmental changes**. By analyzing historical weather data, analysts can identify trends in **temperature, humidity, and precipitation**.

In this project, historical weather data is analyzed using Python libraries such as **NumPy, Pandas, and Matplotlib**. The analysis focuses on cleaning the dataset, performing statistical calculations, and visualizing weather trends over time.

🎯 The goal of this project is to demonstrate how **data analysis techniques can transform raw weather data into meaningful insights**.


## 🎯 Objectives

The main objectives of this project are:

📥 Load and inspect historical weather data using **Pandas**  
🧹 Clean the dataset and handle missing values  
📊 Perform descriptive statistical analysis using **NumPy**  
📅 Analyze monthly weather trends using **Pandas groupby**  
📈 Visualize weather patterns using **Matplotlib**  
⚠ Identify extreme weather conditions using statistical techniques  


## 🛠 Tools & Technologies

This project was completed using the following tools:

🐍 **Python**  
📊 **Pandas**  
🔢 **NumPy**  
📈 **Matplotlib**  
💻 **Google Colab**


## 📂 Dataset Description

The dataset contains historical weather observations with the following variables:

| Column Name | Description |
|-------------|-------------|
| Date | The recorded date of the weather observation |
| Temperature | Daily air temperature value |
| Humidity | Percentage of moisture in the air |
| Precipitation | Amount of rainfall recorded on that day |


## 🧹 Data Cleaning and Preprocessing

The dataset was loaded using the **Pandas `read_csv()`** function and inspected using:

- `head()`
- `info()`
- `describe()`

📊 The dataset contains **1,096 records** with four variables:

- Date  
- Temperature  
- Humidity  
- Precipitation  

🔎 Missing values were checked using **`isnull().sum()`**, and no missing values were found.

📅 The **Date column** was converted to **datetime format** using `pd.to_datetime()` to enable time-based analysis.

After preprocessing, the dataset was **clean and ready for analysis**.


## 📊 Exploratory Data Analysis & Insights

### 📈 Descriptive Statistics of Weather Variables

**Temperature**

- Mean: **9.91 °C**
- Median: **9.06 °C**
- Standard Deviation: **11.74**

**Humidity**

- Mean: **60.85%**
- Median: **60.48%**
- Standard Deviation: **17.37**

**Precipitation**

- Mean: **3.47 mm**
- Median: **1.52 mm**
- Standard Deviation: **7.40**

💡 **Insight**

- Temperature shows **high variability**, indicating strong seasonal changes.
- Humidity remains **relatively stable around 60%**.
- Precipitation varies significantly with **occasional heavy rainfall events**.


### 📅 Monthly Temperature Trend

**Findings**

- Temperatures increase from **January to March**
- Peak temperatures occur during **March and April**
- Temperatures decline gradually after **June**
- Lowest temperatures occur between **August and October**

💡 **Insight**

The dataset shows **clear seasonal temperature variations across months**.


### 🌧 Monthly Precipitation Pattern

**Findings**

- Higher precipitation in **February, April, November, and December**
- Lower rainfall during **May and September**

💡 **Insight**

Rainfall distribution varies across the year, indicating **periods of heavy and light precipitation**.


### 🌡 Temperature Distribution

**Findings**

- Temperature ranges from **-18.9 °C to 42.3 °C**
- Most observations fall within **moderate temperature ranges**

💡 **Insight**

The histogram shows a **wide distribution of temperatures**, reflecting both cold and warm periods.


### 🔥 Extreme Temperature Events

**Findings**

- Several days recorded **extremely high temperatures above 34 °C**
- Some days recorded **extremely low temperatures below -14 °C**

💡 **Insight**

Extreme temperature events occur occasionally and represent **unusual climate conditions**.


### ⛈ Extreme Precipitation Events

**Findings**

- Some days recorded rainfall **above the 95th percentile**
- A few events exceeded **50 mm precipitation**

💡 **Insight**

Although most days have low rainfall, the dataset includes **occasional heavy rainfall events**.


## 🔍 Key Insights

🌡 Weather patterns show **clear seasonal temperature fluctuations** throughout the year.

📊 Average temperature is around **9.9 °C**, but values vary significantly.

💧 Humidity levels remain **relatively stable across the dataset**.

🌧 Rainfall distribution is **uneven**, with some months experiencing heavier precipitation.

⚠ Several **extreme weather events** were identified, including high temperatures and heavy rainfall.



## 💡 Recommendations

🌡 Monitor seasonal temperature trends to **prepare for extreme weather conditions**.

🚨 Implement **early warning systems** for extreme temperatures and heavy rainfall.

🌧 Improve rainfall monitoring during **high precipitation months**.

📊 Use historical weather data for **predictive weather analysis**.

📡 Expand datasets with additional weather variables such as **wind speed and air pressure**.



## 🏁 Conclusion

This project analyzed historical weather data using **Python, NumPy, Pandas, and Matplotlib** to identify trends in **temperature, humidity, and precipitation**.

The analysis revealed **clear seasonal patterns**, stable humidity levels, and uneven rainfall distribution. Additionally, several **extreme weather events** were detected, demonstrating variability in climate conditions.

Overall, this project shows how **data analysis techniques can transform raw weather data into meaningful insights that support climate understanding and better decision-making**.






