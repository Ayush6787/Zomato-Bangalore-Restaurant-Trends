# 🍽️ Zomato Bangalore Restaurant Analysis & Geospatial Visualization

This project explores the restaurant landscape of Bangalore using Zomato's dataset. It combines data cleaning, exploratory data analysis (EDA), and interactive geospatial visualization using Folium to understand restaurant density and cuisine distribution across the city.

---

## 📁 Dataset

- **Zomato Data**: Contains restaurant details including name, rating, cuisine, cost, type, and location.
- **Geographical Coordinates**: Contains latitude and longitude for Bangalore localities to enable location-based mapping.

---

## 📌 Project Highlights

### ✅ Data Cleaning & Preprocessing
- Converted ratings to float and filled missing values using median.
- Cleaned cost data by removing commas and handling missing values.
- Filled missing categorical values (`cuisines`, `dish_liked`, `rest_type`) with appropriate defaults.
- Encoded binary fields like `online_order` and `book_table`.
- Merged Zomato data with geographical coordinates using `listed_incity`.

### 📊 Exploratory Data Analysis (EDA)
- Distribution of ratings
- Top cuisines offered
- Top localities by restaurant count
- Cost vs rating scatter analysis
- Restaurant type frequency

### 🌍 Geospatial Visualization with Folium
- **Restaurant Density Map**: Shows overall restaurant concentration across Bangalore.
- **Cuisine-Specific Map**: Highlights restaurants that serve **Italian cuisine** using customized markers.
- All maps are interactive and saved as `.html` for easy sharing and exploration.

---

## 📷 Screenshots

### 🔸 Rating Distribution
![rating-plot](screenshots/rating_distribution.png)

### 🔸 Top Cuisines
![top-cuisines](screenshots/top_cuisines.png)

### 🔸 Italian Restaurants Map
![map-preview](screenshots/italian_restaurants_map.png)

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/your-username/zomato-bangalore-eda.git
cd zomato-bangalore-eda


## ✨ Author

**Ayush Argonda**  
🔗 [LinkedIn](https://www.linkedin.com/) 

[🌐 Portfolio ](https://profound-alpaca-ec7224.netlify.app/)

[📝 Medium ](https://medium.com/@ayushargonda6787)

| 💻 Machine Learning Enthusiast | 🧠 Building projects from sc
