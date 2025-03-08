# **Hotel Bookings Analysis**

## **Project Overview**
This repository contains an analysis of **hotel booking trends** for a **City Hotel and a Resort Hotel** between **July 2015 and August 2017**. The dataset includes **booking details, cancellation rates, revenue, and guest demographics**. The goal of this project is to analyze customer behaviors, optimize hotel booking strategies, and understand market demand.

## **Objectives**
- Identify **top countries** where most travelers come from
- Analyze **Average Daily Rate (ADR) trends**
- Determine **booking cancellation rates**
- Examine **average number of nights spent** at hotels
- Provide an interactive **Power BI dashboard** showcasing key insights

## **Data Sources and Tools Used**
- **Dataset**: Hotel Booking Dataset (sourced from **Hotel Booking Demand Datasets**)
- **Tools Used**:
  - **Microsoft Excel**: Data cleaning and preprocessing
  - **Power BI Desktop**: Data visualization and dashboard creation

## **Exploratory Data Analysis (EDA)**
### **Data Description**
The dataset contains **119,390 hotel bookings**, with key columns including:
- **hotel** – Type of hotel (**City Hotel or Resort Hotel**)
- **country** – Origin of the traveler
- **adr** – Average Daily Rate (ADR) per room
- **arrival_date** – Booking arrival date
- **stays_in_weekend_nights** – Number of weekend nights stayed
- **stays_in_week_nights** – Number of weekday nights stayed
- **adults, children, babies** – Number of guests in the booking
- **booking_changes** – Number of modifications made to the booking
- **is_canceled** – Whether the booking was canceled or not
- **market_segment** – How the booking was made (**corporate, online travel agency, direct, etc.**)

## **Methodology**
### **Data Cleaning & Preparation**
- Handled missing values and standardized data formats
- Created calculated columns for **total nights stayed** and **cancellation rates**
- Categorized booking types based on market segment and revenue contribution

### **Data Analysis in Excel**
- Used Pivot Tables to analyze **hotel booking frequency by country**
- Evaluated **cancellation trends and revenue generation by hotel type**
- Calculated **ADR variations across different market segments**

### **Visualization & Insights in Power BI**
- Built an interactive dashboard summarizing key findings
- Created bar charts to compare **top 5 countries with the most travelers**
- Analyzed **monthly trends in bookings**
- Identified **room type booking frequency**
- Examined **market segment ADR distribution**

## **Key Insights & Interpretation**
### **1. Top 5 Countries with the Most Travelers**
- **Portugal (PRT), Austria (AUT), France (FRA), UK (GBR), and Germany (DEU)** had the highest number of hotel guests.

### **2. Average Daily Rate (ADR) Trends**
- **Highest ADR recorded: $5.19K (Portugal)**
- **Overall Average ADR: $63.79**
- Market segments like **Corporate and Online Travel Agencies (OTA)** had the highest ADR distribution.

### **3. Booking Cancellations and Revenue Impact**
- **City Hotels had a 100% cancellation rate, while Resort Hotels had a 90.48% cancellation rate**.
- High cancellations impacted revenue forecasting and hotel occupancy planning.

### **4. Guest Stay Duration Analysis**
- **Average nights spent: 6.20 nights**
- Guests booking **Resort Hotels with children and babies stayed longer.**

### **5. Room Type and Market Segment Insights**
- **Room Type A had the highest booking frequency (841 bookings)**
- **Corporate and Direct bookings contributed the most to ADR revenue.**

## **Data Visuals**
The Power BI dashboard includes:
- **Top 5 countries with the most travelers**
- **ADR distribution across different market segments**
- **Booking cancellation rates by hotel type**
- **Room type booking frequency**
- **Monthly trend analysis of hotel bookings**

### **Dashboard Preview**
![image](https://github.com/user-attachments/assets/9bfbacbb-ff60-4d0a-99c4-802b91e3d592)

## **Data Story**
This dashboard was created to analyze **global hotel booking trends** and their impact on **revenue, customer behavior, and market demand**. The goal is to provide insights for **hoteliers, travel agencies, and tourism management professionals** to optimize hotel operations and booking strategies.

### **Key Findings**
- **Portugal had the highest number of bookings, contributing the most to ADR.**
- **High cancellation rates pose challenges for revenue planning and inventory management.**
- **Resort Hotels attracted longer stays, especially for families with children.**
- **Corporate and OTA bookings generated the highest revenue.**

### **Conclusion**
To improve hotel revenue and guest experience:
- **Develop targeted pricing strategies for high-ADR market segments.**
- **Reduce cancellations through better booking policies and incentives.**
- **Enhance customer experience for long-stay guests, especially families in Resort Hotels.**
