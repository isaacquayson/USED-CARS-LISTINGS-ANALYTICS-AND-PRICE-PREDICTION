# USED-CARS-LISTINGS-ANALYTICS-AND-PRICE-PREDICTION

## 📑 Abstract

The used car market plays a critical role in providing affordable mobility solutions, yet determining fair prices remains a challenge due to the many influencing factors such as brand, model, year, mileage, fuel type, and condition. This project applies a **data-driven approach** to analyze and predict used car prices.

Data cleaning and preparation were performed using **Excel Power Query**, while **Power BI** was used to build an **interactive dashboard** that visualizes key insights such as car conditions, mileage trends, fuel preferences, yearly price trends, and geographical distributions. In addition, a **machine learning regression model** was developed in **Python** to predict car prices. Among the tested models, **Random Forest** achieved the best performance with an **R² score of 0.83** and an **RMSE of ~2069**, outperforming Linear Regression.

By combining **descriptive analytics** through dashboarding and **predictive modeling** through machine learning, this project provides actionable insights and accurate price predictions to support decision-making for stakeholders in the used car ecosystem.

## 📖 Introduction  

The automobile industry has witnessed a massive increase in the demand for used cars as consumers seek affordable alternatives to brand-new vehicles. With multiple factors such as **make, model, mileage, year, fuel type, condition, and seller type** influencing car prices, estimating the fair market value becomes a complex process. Buyers often risk overpaying, while sellers struggle to set competitive yet profitable prices.  

To address this challenge, this project integrates **data cleaning, visualization, and machine learning** to analyze trends and predict used car prices. The combination of **Excel Power Query**, **Power BI dashboards**, and **Python regression models** ensures both clarity in understanding the data and accuracy in price forecasting.  

---

## ❓ Problem Statement  

Determining accurate used car prices is often difficult due to:  
- Variability in features such as mileage, fuel type, transmission, and condition.  
- The lack of transparency in price determinants across different sellers and regions.  
- Limited ability to derive actionable insights from large datasets without advanced tools.  

This makes it challenging for stakeholders—buyers, sellers, and dealerships—to make **data-driven decisions** regarding pricing and purchasing strategies.  

---

## 🎯 Objectives  

The main objectives of this project are to:  

1. **Clean and prepare data** using Excel Power Query to ensure accuracy and consistency.  
2. **Build an interactive dashboard in Power BI** to visualize trends such as mileage distribution, price variation across brands, and fuel-type preferences.  
3. **Develop regression models in Python** to predict used car prices based on key features.  
4. **Compare model performance** (Linear Regression vs. Random Forest) and select the best approach for accurate predictions.  
5. **Generate actionable insights and recommendations** that guide stakeholders in setting fair and competitive used car prices.  

---

## 🛠️ Tools Used  

This project was implemented using the following tools and technologies:  

- **Excel Power Query** → For initial data cleaning, handling duplicates, and structuring the dataset.  
- **Power BI** → To build an **interactive dashboard** that visualizes trends such as price distribution, mileage impact, and fuel preferences.  
- **Python (Jupyter Notebook)** → For developing regression models and evaluating performance.  
  - Libraries used include:  
    - `pandas` → Data manipulation and analysis.  
    - `matplotlib` → Data visualization.  
    - `sklearn` → Machine learning model development (Linear Regression & Random Forest).  

---

## ⚙️ Methodology  

The project followed a step-by-step data analytics and machine learning workflow:  

1. **Data Collection & Import**  
   - A dataset containing used car listings with attributes such as make, model, year, mileage, price, fuel type, transmission, and condition was imported into Excel and Python.  

2. **Data Cleaning (Excel Power Query)**  
   - Removed duplicates.  
   - Checked for missing/null values and ensured consistent formatting.  
   - Verified data types for all variables.  

3. **Exploratory Data Analysis (Power BI & Python)**  
   - Built visualizations to understand mileage distribution, pricing trends, and categorical feature influences.  
   - Created an **interactive dashboard in Power BI** to allow dynamic exploration of car listings.  

4. **Feature Encoding (Python)**  
   - Converted categorical variables (e.g., make, fuel type, transmission) into numeric form using **Label Encoding** for model compatibility.  

5. **Model Development (Python)**  
   - Defined independent variables (`make`, `model`, `year`, `mileage`, `condition`, etc.) and dependent variable (`price`).  
   - Split data into **training (80%)** and **testing (20%)** sets.  
   - Trained two models:  
     - **Linear Regression**  
     - **Random Forest Regressor**  

6. **Model Evaluation**  
   - Compared models using **R² Score** and **Root Mean Squared Error (RMSE)**.  
   - Linear Regression: R² = 0.65, RMSE ≈ 2960.  
   - Random Forest: R² = 0.83, RMSE ≈ 2069 (best performing model).  

7. **Insights & Reporting**  
   - Summarized findings into actionable insights.  
   - Combined Power BI dashboard with predictive modeling results for comprehensive analysis.  

---

## 📊 Actionable Insights  

From the data analysis and predictive modeling, the following key insights were derived:  

1. **Mileage has a strong negative correlation with price** – cars with higher mileage tend to have significantly lower resale values.  
2. **Car make and model are major determinants of price** – premium brands (e.g., Mercedes-Benz, BMW) consistently have higher price ranges compared to economy brands (e.g., Hyundai, Kia).  
3. **Fuel type influences pricing trends** – hybrid and electric cars generally attract higher market values compared to petrol or diesel cars.  
4. **Vehicle condition directly impacts resale value** – well-maintained cars in good condition are priced substantially higher than those marked as fair or poor.  
5. **The Random Forest Regressor provides more reliable predictions** than Linear Regression, capturing complex relationships between features and price with higher accuracy.  

---

## 💡 Recommendations  

Based on the findings, the following recommendations are proposed:  

1. **For Buyers:**  
   - Compare listings based on mileage, fuel type, and condition to ensure fair pricing.  
   - Use the dashboard insights to identify undervalued options among specific brands and models.  

2. **For Sellers:**  
   - Highlight vehicle condition, service history, and fuel efficiency in listings to justify higher prices.  
   - Consider market demand patterns (e.g., growing preference for hybrid/electric vehicles) when setting prices.  

3. **For Dealerships & Platforms:**  
   - Integrate predictive models like Random Forest to provide **automated price suggestions** for listings.  
   - Use dashboards to monitor trends and adjust marketing strategies accordingly.  

---

## 🏁 Conclusion  

This project demonstrated how **data analytics and machine learning** can be effectively combined to enhance decision-making in the used car market. Through **Excel Power Query**, the dataset was cleaned and structured; **Power BI dashboards** provided interactive visualizations of key trends; and **Python regression models** enabled price predictions with high accuracy.  

Among the models tested, the **Random Forest Regressor achieved the best performance** (R² = 0.83, RMSE ≈ 2069), proving its effectiveness in capturing the non-linear relationships influencing car prices.  

Ultimately, the integration of **descriptive analytics (dashboards)** and **predictive modeling (machine learning)** offers a comprehensive solution for buyers, sellers, and dealerships to make **informed, data-driven decisions** in the used car ecosystem.  

---

![](https://github.com/isaacquayson/USED-CARS-LISTINGS-ANALYTICS-AND-PRICE-PREDICTION/blob/main/Screenshot%202025-08-16%20144323.png)
