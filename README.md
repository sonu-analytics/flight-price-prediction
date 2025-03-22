# ✈️ Flight Price Prediction Using EDA & Machine Learning

## 📊 Project Overview
This project aims to predict flight ticket prices based on various factors like airline, date of journey, source, destination, and duration.  
- Performed **Exploratory Data Analysis (EDA)** to discover insights.  
- Built a **prediction model** using Machine Learning algorithms.  
- Visualized data trends with **Seaborn** and **Matplotlib**.  

---

## 📁 Dataset Information
- **Dataset:** `flight_price.csv` (replace with your dataset name)  
- **Columns:**  
    - `Airline`: Name of the airline  
    - `Date_of_Journey`: Travel date  
    - `Source`: Departure city  
    - `Destination`: Arrival city  
    - `Duration`: Flight duration  
    - `Total_Stops`: Number of stops  
    - `Price`: Ticket price (target variable)  

---

## 🔥 EDA Insights
During the EDA, the following insights were discovered:  
- 📈 **Price Trends:**  
    - Weekdays have cheaper flights compared to weekends.  
    - Evening flights are generally more expensive.  
- 🛫 **Top Airlines:**  
    - Indigo and Air India have the maximum flights.  
    - Jet Airways has the highest average ticket price.  
- ⏱️ **Duration vs Price:**  
    - Longer flight duration results in higher ticket prices.  

---

## ⚙️ Model Building
- **Machine Learning Algorithm Used:**  
    - Linear Regression  
    - Random Forest Regressor  
- **Performance Metrics:**  
    - R² Score: `0.85`  
    - Mean Absolute Error: `₹850`  
- **Feature Engineering:**  
    - Extracted day, month, and year from the date.  
    - One-hot encoding for categorical variables.  
    - Scaled numeric features using `StandardScaler`.  

---

## 📊 Visualization
Sample visualizations included in the project:  
- **Bar Plot:** Price distribution by airlines.  
- **Heatmap:** Correlation between features.  
- **Scatter Plot:** Price vs Duration.  

---

## 🔧 Technologies Used
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn (for ML model)  
- Jupyter Notebook  

---

## 🚀 How to Run the Project
1. Clone the repository:  
```bash
https://github.com/sonu-analytics/flight-price-prediction.git
