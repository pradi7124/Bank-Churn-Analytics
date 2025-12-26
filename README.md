# **Customer Churn Dashboard Report**

\- Pradyumna Patil

## **1\. Introduction**

This report documents the design and development of an Excel-based Customer Churn Dashboard. The dashboard is created to organize and present customer churn data in a clear, structured, and interactive manner using pivot tables and visual elements. It serves as a reporting tool that allows users to view customer-related information across multiple dimensions within a single interface.

## **2\. Objective**

The objective of this dashboard is to provide a centralized and interactive view of customer churn data. It enables users to monitor key churn-related metrics and explore customer data dynamically through filters and visualizations without modifying the underlying dataset.

## **3\. Methodology**

### **3.1 Data Preparation**

The dataset is stored in a dedicated worksheet and formatted as an Excel Table to ensure consistency and scalability. Customer-level data includes demographic information, account details, activity status, credit card availability, satisfaction scores, and churn indicators.  
Helper columns such as age groups, balance categories, and churn flags are created to support grouped analysis and pivot-based reporting.

### **3.2 Dashboard Development**

Pivot tables are used as the primary analytical layer to aggregate customer data. Pivot charts are created from these pivot tables to visualize different customer attributes and churn-related metrics. All dashboard elements are linked dynamically to ensure real-time updates based on filter selections.

### **3.3 Key Performance Indicators (KPIs)**

The following KPIs are displayed at the top of the dashboard for quick reference:

* Total Customers  
* Churned Customers  
* Churn Rate (%)  
* Average Account Balance  
* Complaint Churn Percentage

Each KPI is calculated using pivot tables and updates automatically based on slicer selections.

### **3.4 Visual Components**

The dashboard includes the following visual representations:

* Number of customers by age group  
* Number of customers by bank balance category  
* Average salary by age group  
* Churned customers by credit card type  
* Churned customers by bank balance category  
* Churned customers by satisfaction score (1–5)

These visuals are arranged systematically to support clear and structured data presentation.

### **3.5 Interactivity and Filters**

Interactive slicers are implemented to allow users to filter dashboard data based on specific attributes. The slicers available in the dashboard include:

* Gender  
* Location  
* Credit card availability  
* Active member status

All slicers are connected to multiple pivot tables to ensure synchronized filtering across all dashboard elements.

### **3.6 Design and Usability**

The dashboard follows a minimal and professional design approach. Gridlines, pivot field buttons, and unnecessary chart elements are removed to enhance readability. Consistent fonts, spacing, and alignment are used to improve usability and ensure a clean presentation layout.

### **3.7 Tools and Techniques Used**

* Microsoft Excel  
* Excel Tables  
* Pivot Tables  
* Pivot Charts


* Slicers

