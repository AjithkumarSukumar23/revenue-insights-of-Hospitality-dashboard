# Hospitality Domain Data Analytics Project

## Overview
This project, inspired by a resume challenge by **Codebasics**, focuses on AtliQ Grands, an imaginary five-star hotel chain operating across multiple cities in India. The project addresses AtliQ Grands' challenges in market share and revenue loss within the luxury/business hotel category. The goal was to create a comprehensive data analytics solution to provide actionable insights and support effective decision-making.

---

## Project Objectives
1. **Metrics Creation:** Develop KPIs and metrics as per stakeholder requirements.
2. **Dashboard Development:** Build a dashboard based on mock-ups provided by stakeholders.
3. **Insight Generation:** Extract insights beyond predefined metrics to aid decision-making.

---

## Data Overview

### **Hotel Information**
- **Locations:** 4 cities across India.
- **Properties:** 7 luxury hotels.
- **Room Categories:** Elite, Premium, Presidential, Standard.
- **Booking Platforms:** 6 main platforms plus others.

### **Datasets Used**
1. **`dim_date`:** Contains date attributes like week numbers and day types.
2. **`dim_hotels`:** Details of properties, including property IDs, names, and categories.
3. **`dim_rooms`:** Room details categorized by room ID and class.
4. **`fact_aggregated_bookings`:** Aggregated data on bookings, capacities, and check-in dates.
5. **`fact_bookings`:** Comprehensive booking details, including revenue, ratings, platforms, and status.

---

## Project Workflow

### **1. Metrics Development**
- Created key financial and performance metrics, such as:
  - **Financial Metrics:**
    - Revenue
    - RevPAR (Revenue per Available Room)
    - ADR (Average Daily Rate)
  - **Performance Metrics:**
    - DSRN (Daily Sellable Room Nights)
    - DBRN (Daily Booked Room Nights)
    - DURN (Daily Utilized Room Nights)
    - Cancellation %
    - Average Rating
    - Booking Platform Performance

---

### **2. Dashboard and Visualization**
- **Tools Used:** Power BI.
- **Dashboard Features:**
  - Revenue breakdown by hotel, room category, and city.
  - Key performance metrics (DSRN, DBRN, DURN) at various granularities.
  - Booking patterns by platforms and day types.
  - Filters for:
    - Week Number
    - Month
    - Property
    - City
    - Room Class
    - Booking Platform

---

### **3. Insight Generation**
- **Financial Insights:**
  - Revenue, RevPAR, and ADR comparison across properties.
  - Financial performance breakdown by room categories and cities.
- **Performance Insights:**
  - Booking platform efficiency and cancellation trends.
  - Seasonal performance based on day type and week number.
- **Room Insights:**
  - Differences in performance metrics across room categories.

---

## Key Features of the Dashboard

### **1. Financial View**
- Focuses on financial metrics like revenue, ADR, and RevPAR.
- Provides insights into revenue generation by property, city, and room class.

### **2. Performance View**
- Includes metrics such as DSRN, DBRN, DURN, and cancellation rates.
- Analyzes performance based on booking platforms and customer ratings.

---

## Tools and Technologies
- **Power BI:** For dashboard creation and visualization.
- **Data Modeling:** DAX formulas for metric calculations.
- **Data Sources:** CSV, Excel, and relational database tables.

---

## Key Insights
1. **By Hotels:** Revenue, RevPAR, and ADR vary significantly across properties.
2. **By Room Categories:** Elite and Presidential rooms consistently outperform Standard and Premium rooms in revenue.
3. **By Cities:** Some cities generate significantly higher revenue, highlighting regional preferences.
4. **By Platforms:** Certain booking platforms contribute more revenue and customer retention.

---

## Prerequisites
- **Power BI Desktop** installed on your machine.
- Access to data files in compatible formats (CSV, Excel, or database connections).

---
