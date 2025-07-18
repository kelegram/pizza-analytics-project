# 🍕 Pizza Sales Dashboard

**Repository:** `pizza-sales-dashboard`  
**Author:** KELECHI EGBE 
---

## 📚 Table of Contents

- [🔧 Tools Used](#-tools-used)
- [📊 Key Metrics & DAX Measures Created](#-key-metrics--dax-measures-created)
  - [🧮 Measures (DAX)](#-measures-dax)
  - [🧱 Calculated Columns & Transformations](#-calculated-columns--transformations)
- [📌 Business Questions Answered](#-business-questions-answered)
  - [🕒 Sales Trends](#-sales-trends)
  - [🍕 Popular Products](#-popular-products)
  - [💰 Revenue Analysis](#-revenue-analysis)
  - [🥦 Customer Preferences](#-customer-preferences)
  - [🧾 Order Patterns](#-order-patterns)
  - [💸 Pricing Insights](#-pricing-insights)
  - [🕐 Time-Based Insights](#-time-based-insights)
- [📷 Dashboard Preview](#-dashboard-preview)
- [📁 Project Structure](#-project-structure)
- [✅ Summary](#-summary)

---

## 🔧 Tools Used

- **Power BI** for data modeling, DAX measures, and visualization.
- **Power Query** for time transformation and custom column generation.
- **Excel** for early-stage data preprocessing (e.g., veggie classification).

---

## 📊 Key Metrics & DAX Measures Created

### 🧮 Measures (DAX):

- `Total Quantity`
- `Total Sales`
- `Total Orders`
- `Average Order Value`
- `Average Sales`
- `Average Unit Price`

### 🧱 Calculated Columns & Transformations:

- **Veggie / Non-Veggie Classification:** Created using an `IF` statement in Excel before importing to Power BI.
- **Order Hour:** Separated date and time using Power Query to extract the `Hour` from the timestamp.
- **Price Range:** Created in Power Query by categorizing unit prices into ranges.
- **Day of the Week:** Extracted using Power Query to analyze order trends across weekdays.

---

## 📌 Business Questions Answered

### 🕒 Sales Trends:

- **What are the peak order times for pizzas?**  
  → Peak month: **January**  
  → Peak day: **Friday**  
  → Peak time: **12 PM**
🔗<img width="922" height="533" alt="Image" src="https://github.com/user-attachments/assets/663c5732-38f9-4d2e-b3e5-03b50705aa32" />

🔗<img width="937" height="543" alt="Image" src="https://github.com/user-attachments/assets/45e20a6b-e627-48fc-83b0-cb6a0239a6f0" />



🔗<img width="916" height="525" alt="Image" src="https://github.com/user-attachments/assets/a1d9691f-e4a4-44b4-ad01-db6fc2246e23" />


- **Which days have the highest number of orders?**  
  → **Friday**, **Thursday**, **Saturday**, and **Wednesday** all exceed 3,000 orders.

### 🍕 Popular Products:

- **Which pizza is the most ordered?**  
  → **Classic Deluxe Pizza**
<img width="1062" height="622" alt="Image" src="https://github.com/user-attachments/assets/5891e20d-56e2-4c43-904b-2ebc52a6dece" />

- **What is the most popular pizza size (M or L)?**  
  → **L size** pizzas are the most ordered based on quantity.

🔗<img width="1050" height="618" alt="Image" src="https://github.com/user-attachments/assets/07b8ea4c-7f80-433c-8fa1-b116c6fbf61f" />


- **What is the most popular pizza category (Classic, Veggie, Supreme)?**  
  → **Classic** category dominates in orders and revenue.
  🔗<img width="1071" height="618" alt="Image" src="https://github.com/user-attachments/assets/86861990-5a49-4f38-8ad3-094efd788aad" />


### 💰 Revenue Analysis:

- **Which pizza generates the highest revenue?**  
  → **Thai Chicken Pizza**

🔗<img width="1101" height="629" alt="Image" src="https://github.com/user-attachments/assets/bb5ce08e-acfd-4075-9a3d-d310610ade18" />

- **What is the average order value?**  
  → **$38.30**
🔗<img width="173" height="94" alt="Image" src="https://github.com/user-attachments/assets/f7374ddc-394d-4b30-b326-1c2ba3c81d74" />

- **How does the revenue compare between different pizza categories?**  
  → **Classic category leads** with a total revenue of **$220,053**.
🔗<img width="1083" height="678" alt="Image" src="https://github.com/user-attachments/assets/cae41c94-870f-48a4-85d5-e4badc541837" />


### 🥦 Customer Preferences:

- **Is there a preference for vegetarian or non-vegetarian pizzas?**  
🔗<img width="1089" height="645" alt="Image" src="https://github.com/user-attachments/assets/3a1114d9-c274-40a4-85fc-181cc7d74d55" />

  → Yes. **Non-vegetarian pizzas account for 76%** of all sales.

### 🧾 Order Patterns:

- **How often do customers order more than one pizza at a time?**

| Quantity                                                   |   | % of Total Orders |
| ---------------------------------------------------------- | - | ----------------- |
| 1 Pizza                                                    |   | 96.8%             |
| 2 Pizzas                                                   |   | 3.6%              |
| 3 Pizzas                                                   |   | 0.1%              |
| 4 Pizzas                                                   |   | 0.01%             |
| → Most customers order **just one pizza per transaction**. |   |                   |

🔗<img width="1092" height="655" alt="Image" src="https://github.com/user-attachments/assets/12ccbfd3-6dfb-41cb-a4cc-ec0178b36535" />

### 💸 Pricing Insights:

- **What is the price range of the pizzas sold?**  
  → Prices range from **$9.75 to $35.95**  
  → Most sold prices:

  - `$12.00` → 5,744 units  
  - `$12.50` → 3,380 units  
  - `$16.00` → 4,522 units  
  - `$16.50` → 4,111 units  
  - `$16.75` → 4,380 units  
  - `$20.75` → 8,891 units (highest single value)
🔗<img width="1111" height="635" alt="Image" src="https://github.com/user-attachments/assets/2c08b9eb-958c-498c-97fa-b5c192442cc2" />

- **How does the unit price of pizzas vary across different sizes and categories?**

🔗<img width="1114" height="630" alt="Image" src="https://github.com/user-attachments/assets/de5164ba-c2b8-4eea-92e1-a12c8a4e29c8" />


### 🕐 Time-Based Insights:

- **Are there any time periods with unusually high or low sales?**  
  - **High Sales Days:** Friday ($129,690.90), Thursday, Saturday  
  - **High Sales Hours:**
    - **12 PM** and **1 PM** have the strongest sales across all days.
    - **6 PM – 8 PM** also perform well consistently.
  - **Low Sales Hours:**
    - **10 AM** and **11 PM** consistently have the lowest sales.
🔗<img width="1118" height="640" alt="Image" src="https://github.com/user-attachments/assets/803fca7c-da7a-408e-b7f8-4d5e9fec92fa" />

---

## 📷 Dashboard Preview

<img width="1117" height="666" alt="Image" src="https://github.com/user-attachments/assets/0a09372b-e9e4-4a55-9322-976b45359868" />


---


## ✅ Summary

This dashboard provides insights into:
- Sales performance over time
- Customer preferences between veggie/non-veggie
- Pricing trends and revenue generation
- Peak order periods and volume analysis

It demonstrates proficiency in Power BI, DAX, and data storytelling.
