
# 🍽️ Restaurant Data Analysis Project

Hey there! In this project, I'm excited to walk you through a restaurant dataset I worked on during my Data Analysis Internship with **Cognifyz Technologies**. It's packed with information about thousands of restaurants from around the world, and my goal was to explore it, clean it, and extract meaningful insights — just like a real data analyst would in the industry.

---

## 📘 Project Background

This project is based on a real-world restaurant dataset that includes detailed information about **9,500+ restaurants** operating across **15 countries** and **141 cities worldwide**. It captures a wide variety of restaurant-related attributes such as names, locations, cuisines served, pricing, customer ratings, delivery and booking services, and more.

The dataset serves as the foundation for performing both basic and advanced data analysis tasks. It allows us to explore various dimensions of the food industry — from identifying top cuisines and affordable areas, to analyzing the effect of online services and customer engagement through ratings and votes.

This analysis is conducted as part of the **Data Analysis Internship Program by Cognifyz Technologies**, a company known for delivering cutting-edge data science and AI solutions. The core objective of the internship is to help aspiring data analysts gain hands-on experience by working on real datasets. Interns are required to apply key skills such as data cleaning, visualization, feature exploration, and insight generation to answer business-driven questions.

The goal of this project is not just to summarize the data but to **derive actionable insights** that reflect **customer preferences**, **pricing behavior**, **popular cuisines**, and **service availability trends** — all of which can help food delivery platforms or restaurants make better strategic decisions.

---

## 🧾 Dataset Overview

Here’s what the dataset looks like at a high level:

- **Total Rows:** 9,551  
- **Total Columns:** 21  
- **Countries Represented:** 15  
- **Unique Cities:** 141  
- **Cuisine Combinations:** 1,825  
- **Price Categories:** 1 (low) to 4 (high-end)  
- **Rating Scale:** 0.0 to 5.0 with categories like "Excellent", "Good", "Average"

---

## 🗂️ Column-Wise Description

These are the main columns you'll find in the dataset, and what they represent:

- `Restaurant ID`: Unique identifier for each restaurant
- `Restaurant Name`: Name of the restaurant
- `Country Code`: Numeric code identifying the country
- `City`: City where the restaurant is located
- `Address`: Full postal address
- `Locality`: Neighborhood or zone within the city
- `Locality Verbose`: Extended version of locality
- `Longitude` & `Latitude`: Used for geo-mapping
- `Cuisines`: Types of food offered
- `Average Cost for Two`: Estimated cost for two people
- `Currency`: Currency used in pricing
- `Has Table Booking`: Indicates if advance booking is available
- `Has Online Delivery`: Indicates if online ordering is supported
- `Is Delivering Now`: Real-time delivery status (mostly "No")
- `Switch to Order Menu`: Static field (usually "No")
- `Price Range`: Category of pricing (1 = low, 4 = high)
- `Aggregate Rating`: Average customer rating
- `Rating Color`: UI color linked to rating
- `Rating Text`: Descriptive rating like "Good", "Excellent"
- `Votes`: Number of ratings/votes received

---

## 🌐 Geographical Coverage Summary (Cities + Countries)

- The dataset spans **141 cities** in **15 countries**.
- **India** dominates with over **8,600 restaurants**, which is more than 90% of the dataset.
- **Top Indian Cities**:
  - New Delhi: 5,473 entries
  - Gurgaon: 1,118 entries
  - Noida: 1,080 entries
- Other cities like Faridabad and Ghaziabad are also included.
- Apart from India, the dataset has entries from:
  - United States (434 entries)
  - United Kingdom, Brazil, UAE, South Africa (~60 each)
  - Others: New Zealand, Turkey, Australia, Philippines, Singapore, Canada, and more.
- While global in scope, insights from this data are mostly **India-centric** due to its sheer volume.

---

## 🎯 Internship Task Objectives (from Cognifyz Technologies)

During the internship, I worked on tasks across 3 levels. Here’s what I tackled:

### 🔹 Level 1: Basic EDA
- Identified top 3 cuisines and their percentages
- Found city with most restaurants
- Calculated city-wise and highest average rating
- Analyzed price range distribution
- Checked % of restaurants offering online delivery
- Compared delivery vs non-delivery ratings

### 🔸 Level 2: Intermediate Analysis
- Analyzed rating distribution and most common rating
- Calculated average votes
- Discovered popular cuisine combinations
- Plotted restaurant locations using coordinates
- Detected restaurant chains and compared ratings

### 🔺 Level 3: Deep-Dive Insights
- Analyzed review text sentiment & keyword trends (if available)
- Found restaurants with highest & lowest votes
- Explored vote–rating correlation
- Analyzed relationship between price range & services

---

## 📊 Results & Insights Summary

- **Top Cuisines**: North Indian, Chinese, and Fast Food emerged as the most offered cuisines.
- **City with Most Restaurants**: New Delhi stands out with 5,473 listings.
- **Delivery Services**: Nearly 32% of restaurants support online delivery; these tend to have slightly higher ratings.
- **Rating Trends**:
  - Most restaurants fall in the 3.5 to 4.0 rating band.
  - A moderate positive correlation (around 0.41) exists between the number of votes and ratings.
- **Popular Combinations**: Certain multi-cuisine combinations (like North Indian + Chinese) are more prevalent and receive more votes.
- **Price vs Services**: Higher-priced restaurants more often support table booking but not necessarily delivery.
- **Restaurant Chains**: Chain restaurants like "Domino’s Pizza" and "Cafe Coffee Day" are spread widely but vary in quality across locations.

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (if used for maps/interactive visuals)
- Jupyter Notebook

---


## ✅ Final Thoughts

I really enjoyed diving deep into this dataset — cleaning, analyzing, and learning through each step. This project helped me strengthen my skills in **Pandas**, **visualization**, and understanding **real-world business problems**. If you're into food analytics or looking to explore customer behavior in the restaurant space, this is a great dataset to start with.

---

Thanks for reading! Feel free to explore the notebook or connect with me on LinkedIn to share feedback or suggestions 🚀
www.linkedin.com/in/hemantagase47
