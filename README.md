# 🏡 AirBnB Listings – Exploratory Data Analysis (EDA)

This project provides an in-depth **Exploratory Data Analysis (EDA)** on an Airbnb listings dataset. The goal is to uncover trends, guest preferences, pricing patterns, and factors influencing listing popularity and performance.

---

## 📌 Project Overview

With the rapid growth of short-term rental platforms like Airbnb, hosts and platform managers need data-driven insights to optimize pricing, identify high-performing listings, and understand guest behavior.

This EDA project explores:

- Neighborhood trends in pricing and availability
- Host behavior and performance
- Listing types and guest preferences
- Correlation between reviews, availability, and prices

---

## 🗃️ Dataset

- **Filename:** `air_bnb_dataset.csv`
- **Features include:**  
  - `id`, `name`, `host_id`, `neighbourhood`, `room_type`, `price`, `minimum_nights`, `number_of_reviews`, `availability_365`, etc.

---

## 📊 Key Questions Answered

- What are the most expensive and cheapest neighborhoods?
- Which room types are most popular?
- How do prices vary across room types and boroughs?
- Is there a correlation between reviews and availability?
- Who are the top-performing hosts?

---

## 🔧 Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas & NumPy** – data cleaning and manipulation
- **Matplotlib & Seaborn** – data visualization
- **Plotly (optional)** – interactive visualizations

---

## 📈 Sample Insights

- Private rooms are the most common, but entire homes generate more revenue.
- Manhattan and Brooklyn have the highest listing density.
- Prices are heavily skewed; many listings charge under $200/night, but some luxury listings exceed $1,000.
- There is a weak correlation between the number of reviews and price, but a stronger one between reviews and availability.

---

## Future Work
- Apply machine learning to predict listing price or availability
- Build a Streamlit dashboard for interactive exploration
- Integrate external data like weather, local events, or seasonality
