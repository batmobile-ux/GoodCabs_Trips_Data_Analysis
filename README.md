# 🚖 GoodCabs Trips & Passenger Analysis

This project analyzes the **GoodCabs dataset** using **Polars** for high-performance data analysis and **Matplotlib/Seaborn** for visualization.  
We explore trips, passengers, repeat trip behavior, and city-level performance against targets.

---

## 📂 Dataset Files

The dataset consists of 10 CSVs:

1. `city_info.csv` → City-level information  
2. `city_target_passenger_rating.csv` → Target passenger ratings by city  
3. `dim_city.csv` → City dimension table  
4. `dim_date.csv` → Date dimension table  
5. `dim_repeat_trip_distribution.csv` → Repeat trip distribution by city  
6. `fact_passenger_summary.csv` → Passenger summary (new vs repeat)  
7. `fact_trips.csv` → Trip-level fact table  
8. `meta_data.txt` → Metadata about dataset fields  
9. `monthly_target_new_passenger.csv` → Monthly target for new passengers  
10. `monthly_target_trips.csv` → Monthly target for trips  

---

## ⚙️ Setup

Clone this repo and install dependencies:

```bash
git clone https://github.com/batmobile-ux/GoodCabs_Trips_Data_Analysis.git
cd GoodCabs_Trips_Data_Analysis

pip install polars matplotlib seaborn
