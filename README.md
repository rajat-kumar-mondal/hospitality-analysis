# Hospitality Analysis Project



## 📌 Overview

This data analysis project explores key insights from hospitality industry data, focusing on booking trends, hotel performance, and month to month variations. The analysis is performed using Python libraries such as **pandas**, and **matplotlib**, and the results provide actionable insights for decision-making in the hospitality sector.

## 📂 Project Structure

```
/
    hospitality_analysis.ipynb      # Jupyter Notebook with full analysis
 data/
    dim_date.csv                    # Date dimension data for time-series analysis
    dim_hotels.csv                  # Hotel details such as name, location, etc.
    dim_rooms.csv                   # Room details including types and capacities
    fact_aggregated_bookings.csv    # Aggregated booking data for analysis
    fact_bookings.csv               # Detailed booking records
    new_data_august.csv             # Additional dataset for August
```

## 📊 Dataset Description

The project leverages multiple datasets to provide insights into the hospitality industry:

- **`dim_date.csv`**: Contains 92 date-related recods for time-series analysis. 
- **`dim_hotels.csv`**: Includes 25 hotel details such as name, type, and location.
- **`dim_rooms.csv`**: Provides room types, capacity, and associated details (4 records).
- **`fact_aggregated_bookings.csv`**: Aggregated booking data (9.2K records) for efficient trend analysis.
- **`fact_bookings.csv`**: Detailed booking data (134K+) with granular information.
- **`new_data_august.csv`**: Additional data (7 records) reflecting updates for August.

## ⚡ Key Analysis Steps

The analysis process follows these major steps:

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Correcting data types
   - Removing duplicates
2. **Exploratory Data Analysis (EDA)**
   - Visualizing booking trends across seasons
   - Identifying peak booking periods and room preferences
   - Analyzing hotel performance across regions
3. **Key Insights & Findings**
   - Understanding customer preferences
   - Highlighting influential factors in booking rates
   - Recommending strategies for maximizing occupancy rates

## 📈 Insights & Results

Key insights discovered during the analysis include:

1. **Average Occupancy Rate Range (for Room Types):** ~57% to ~59% for all types of rooms (i.e., 4 types of rooms - Standard, Premium, Elite, Presidential).
2. **Average occupancy Rate Range (for Cities):** ~56% to ~62% (for all cities, i.e., Bangalore, Delhi, Hyderabad, Mumbai).
3. **Occupancy Days Trend**: Highest occupancy on weekend days (~72%) and lowest occupancy on weekdays (50.88%).
4. **Revenue realized (for Cities):** Highest in Mumbai (~66B₹), followed by Bangalore (~42B₹), Hyderabad (~32B₹), and Delhi lowest (~29B₹).
5. **Peak Month:** Identified May showing a peak of 32K+ bookings.
6. **Booking Preferences:** The most preferred room type was RT2 (i.e., Premium Rooms), accounting for 37% of total bookings.
7. **Overbooking Patterns:** Found that only 0.07% of recorded dates experienced overbooking incidents.
8. **Net Revenue Distribution by Room Type:** Premium room (RT2) bookings contributed to the highest revenue (~33%), with an average booking value of 13K₹/day.
9. **Average Rating:** The hotels in Delhi have the highest average rating of 3.8/5, while the hotels in Bangalore have the lowest rating of 3.4/5. So, the hotels in Bangalore need to improve their service.


## 🛠 Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rajat-kumar-mondal/hospitality-analysis.git
cd hospitality-analysis
```

### 2️⃣ Install Dependencies

```bash
pip install pandas numpy matplotlib
```

### 3️⃣ Run the Analysis

Open `hospitality_analysis.ipynb` in Jupyter Notebook and execute the cells to explore the data and insights.

## 📦 Libraries & Packages

The project leverages the following key libraries:

- **pandas** – Data manipulation and cleaning
- **numpy** – Numerical computations
- **matplotlib** – Data visualization

---

