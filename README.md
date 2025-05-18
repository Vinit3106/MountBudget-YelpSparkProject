# MountBudget – The Smart Travel Assistant for Mountain Lovers


##  Project Overview

MountBudget is a smart travel assistant designed for **budget-conscious adventure seekers** who want to explore scenic mountain towns across Alberta and British Columbia.

Using **real-time Yelp API data**, Apache Spark, and Spark SQL, we collected, cleaned, analyzed, and visualized thousands of business listings to help users discover:
- Top-rated **restaurants, hotels, and cafes**
- **Adventure activities** like hiking, skiing, and kayaking
- **Budget-friendly options** based on Yelp’s price ratings

---

##  Technologies Used
- **Yelp Fusion API**
- **Apache Spark & Spark SQL**
- **PySpark**
- **Pandas / json_normalize / explode**
- **Matplotlib, Seaborn, and Folium for visualizations**
- **Jupyter Notebook**

---

##  Files Included

| File | Description |
|------|-------------|
| `mountbudget_cleaned.csv` | Final normalized dataset |
| `MountBudget_raw_yelp_data.csv` | Raw Yelp data |
| `Final_Project.ipynb` | Full project notebook |


---

##  Key Insights

- **Banff and Whistler** have the highest number of adventure businesses
- **Canmore and Jasper** are ideal budget towns with quality experiences
- **Hiking, skiing, and cafes** are top trending activity categories
- Our Spark SQL queries helped extract actionable insights like:
  - Top-rated businesses per town
  - Price category distribution
  - Adventure counts by city

---

##  Future Steps

- Integrate **weather API** and **Google Maps**
- Add **personalized filters** for food lovers, hikers, etc.
- Enable **offline trip saving** and **itinerary export**
- Deploy as a **web app using Streamlit or Heroku**
