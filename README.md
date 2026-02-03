# Flight Price Analysis – Exploratory Data Analysis & Feature Engineering

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Feature Engineering** on a **Flight Price dataset** to understand the factors affecting airline ticket prices. The notebook focuses on uncovering patterns, cleaning the data, and transforming features to make the dataset ready for machine learning models.

---

## 📂 Repository Structure

```
├── FLIGHT_EDA & FEATURE ENG.ipynb
├── README.md
```

---

## 🗂 Dataset Description

The dataset contains information about flight journeys, airlines, travel dates, routes, and ticket prices.

### Key Columns

* **Airline** – Name of the airline
* **Date_of_Journey** – Journey date
* **Source** – Departure city
* **Destination** – Arrival city
* **Route** – Flight route details
* **Dep_Time** – Departure time
* **Arrival_Time** – Arrival time
* **Duration** – Total journey duration
* **Total_Stops** – Number of stops
* **Additional_Info** – Extra flight-related information
* **Price** – Ticket price (target variable)

---

## 🔍 Analysis Performed

### 1. Data Cleaning

* Handling missing and inconsistent values
* Parsing date and time features
* Converting duration into numerical format

### 2. Exploratory Data Analysis (EDA)

* Airline-wise price comparison
* Impact of total stops on ticket prices
* Price trends based on source and destination
* Distribution of flight prices

### 3. Feature Engineering

* Extracting day, month from journey date
* Encoding categorical variables
* Transforming time-based features
* Preparing numerical features for modeling

---

## 📊 Tools & Libraries Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **Jupyter Notebook**

---

## 📈 Key Insights

* Ticket prices increase with the number of stops
* Certain airlines consistently have higher average fares
* Journey date and duration strongly influence ticket prices

*(Detailed visualizations and findings are included in the notebook.)*

---

## 🧠 Future Work

* Build regression models for price prediction
* Compare multiple machine learning algorithms
* Perform feature importance analysis

---

## ✍️ Author

**VIKAS KUMAR**

---

## 📜 License

This project is for educational and learning purposes only.
