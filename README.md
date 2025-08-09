---
# Airbnb Listings EDA — New York 2024

## Overview

I explored **New York Airbnb listings** to understand how prices, availability, and room types vary across neighborhoods. Using **Pandas, NumPy, Matplotlib, and Seaborn**, I cleaned the dataset, looked for patterns, and visualized the results.

![](https://github.com/abhayshrivastava1/Airbnb-Listings-EDA-New-York-2024/blob/main/image.png)
---

## Goals

- Compare **room types** and **price ranges** across boroughs.
- Identify **host trends** (single vs. multiple listings).
- Spot **price outliers** and unusual patterns.
- Suggest practical takeaways for **guests** and **hosts**.

---

## Dataset

- **20,765 listings**, 22 columns.
- Includes location, room type, price, reviews, and availability.

---

## Process

1. **Cleaned Data**: Filled missing values, fixed date formats, and removed extreme prices.
2. **Exploratory Analysis**:

   - Price distribution by borough
   - Room type popularity
   - Availability vs. reviews
   - Hosts with multiple properties

3. **Visualized Trends**: Bar charts, box plots, heatmaps, and pair plots.

---

## Key Findings

- **Manhattan** is the priciest, Brooklyn is more budget-friendly.
- **Entire homes/apartments** dominate but private rooms are cheaper.
- Higher availability often means more reviews.
- A few listings were priced unrealistically high and were removed for clarity.

---

## Recommendations

- **Guests**: Look for high-availability listings with good reviews. Brooklyn private rooms are a great budget choice.
- **Hosts**: Keep calendars open and reviews positive; price competitively within your borough.

---

## How to Run

```bash
git clone https://github.com/abhayshrivastava1/Airbnb-Listings-EDA-New-York-2024.git
pip install pandas numpy matplotlib seaborn
jupyter notebook day23_airbnb_eda.ipynb
```
