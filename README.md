#  Ecommerce Customer Behavior Analysis

This project analyzes customer behavior on an e-commerce platform to help the marketing and product teams understand user patterns, improve engagement, and increase conversion rates.

The dataset includes customer visits, time spent on product pages, device types, new vs returning users, and purchase decisions.



# Dataset Description

The dataset ecommerce_customers.csv contains the following columns:

- *CustomerID* – Unique customer identifier  
- *VisitDate* – Date of the visit  
- *TimeOnPage* – Time spent on the product page (seconds)  
- *ProductViewed* – Product name  
- *DeviceType* – Device used (Mobile, Desktop, Tablet)  
- *isNewCustomer* – Whether the customer is new or returning  
- *MadePurchase* – Whether the customer made a purchase (1/0)



# Data Cleaning Steps

1. *Check for missing values*  
2. *Detect and remove duplicates*  
3. *Convert VisitDate to datetime*  
4. *Ensure correct data types for columns*



## 🧩 Feature Engineering

New columns were added to improve analysis:

# Day  
Extracted day name from VisitDate (e.g., Monday, Tuesday)

# DayType  
Classifies days into:
- Weekend
- Weekday

# Time of rest  
Based on time on page:
- Short (< 90 sec)  
- Medium (90–150 sec)  
- Long (> 150 sec)


# Key Analyses

# Conversion Rate  
Percentage of visitors who made a purchase.

# New vs Returning Customers  
Calculated percentage of new visitors vs returning visitors.

# Most Viewed Product  
Identified using value counts.

# Average Time Spent by Device Type  
Grouped by device (Mobile, Desktop, Tablet).

# Top Purchasing Days  
Total purchases grouped by day of the week.



# Visualizations

The following charts were created:

1. *Line Plot* — Number of visits by day  
2. *Bar Chart* — Most viewed products  
3. *Pie Chart* — New vs Returning customers  

These visualizations help the business understand trend patterns and user behavior.



# Insights Summary

- Certain days such as *Wednesday, Saturday, and Sunday* have the highest purchases.  
- Returning customers show higher engagement.  
- Desktop users tend to spend more time on pages.  
- A few products attract significantly more visits.



 # Technologies Used

- *Python*
- *Pandas*
- *Matplotlib*
- *Jupyter Notebook / VS Code*


 # Author

Project completed by: *Sbika Zakaria*
