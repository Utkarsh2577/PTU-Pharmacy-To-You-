# PTU Pharmacy Business Intelligence & CRM Integration

## Project Overview

This project presents an end-to-end **Business Intelligence (BI) and Customer Relationship Management (CRM)** solution for **PTU Pharmacy**, a hospital-based in-house pharmacy facing operational and customer engagement challenges.

PTU Pharmacy was struggling with declining sales, weak customer engagement, inefficient supplier coordination, limited data visibility, frequent stock shortages, limited operating hours, no structured loyalty programme, and low conversion of hospital visitors into pharmacy customers.

To solve these problems, this project combined:

- Power BI dashboards for real-time business insights
- Salesforce CRM for customer, order, supplier, and medicine management
- Mock operational datasets to simulate real-world pharmacy scenarios
- Data modelling using ERD and data dictionary
- Business analysis using GAP analysis and SWOT analysis
- Dashboard-driven recommendations for sales, suppliers, stock, and customer retention

The goal of the project was to transform PTU Pharmacy into a more **data-driven, customer-focused, and operationally efficient pharmacy business**.

---

## Business Problem

PTU Pharmacy operates inside a hospital, giving it direct access to patients, hospital staff, and visitors. However, despite this strong location advantage, the pharmacy was losing customers to external competitors such as **Best Pharma**.

The main business problems identified were:

- Lower sales compared to competitors
- Higher medicine prices
- Limited operating hours
- No home delivery service
- Weak customer engagement
- No loyalty or reward programme
- Frequent stock shortages
- Poor supplier performance tracking
- Lack of CRM system
- Manual customer and order handling
- Low conversion of hospital visitors into PTU customers

The project was designed to identify these gaps clearly and provide a BI and CRM-based solution.

---

## Project Objectives

The main objectives of this project were:

- Build interactive Power BI dashboards to monitor pharmacy performance
- Compare PTU Pharmacy with its competitor Best Pharma
- Track sales trends, pricing patterns, and stock issues
- Analyse supplier performance and delivery efficiency
- Understand hospital visitor conversion into pharmacy customers
- Implement Salesforce CRM for customer, order, supplier, and medicine management
- Improve customer engagement through loyalty points and structured customer records
- Support future automation such as email reminders, loyalty tracking, and online ordering

---

## Proposed Solution

The proposed solution combines **Power BI** and **Salesforce CRM**.

Power BI was used to create interactive dashboards that help pharmacy management analyse:

- Sales performance
- Product-wise revenue
- Pricing differences
- Supplier performance
- Stock availability
- Competitor comparison
- Hospital visitor conversion

Salesforce CRM was used to manage:

- Customer profiles
- Orders
- Medicines
- Suppliers
- Drivers
- Loyalty points
- Customer queries and complaints

Together, these tools create a complete business solution that supports better decision-making, improved customer engagement, and more efficient pharmacy operations.

---

## Tools and Technologies Used

This project used the following tools and technologies:

- Power BI
- Salesforce CRM
- Microsoft Excel / CSV datasets
- Mockaroo
- Data Import Wizard
- SOQL
- ER Diagram
- Data Dictionary
- Trello
- Miro
- Business Intelligence
- CRM Design
- Dashboard Reporting
- Data Modelling
- Data Cleaning
- KPI Analysis

---

## Dataset and Data Design

Since real pharmacy operational data was not available, mock datasets were created to simulate realistic pharmacy operations.

The datasets were designed to represent:

- PTU sales data
- Best Pharma sales data
- Medicine inventory data
- Supplier data
- Customer data
- CRM interaction data
- Driver availability data
- Hospital visit data

Mockaroo was used to generate realistic data for the project.

The dataset design supported analysis across:

- Sales transactions
- Inventory availability
- Supplier delivery performance
- Customer purchase behaviour
- Loyalty engagement
- Hospital patient conversion
- Delivery operations

---

## Database Design

A structured database design was created to support the BI and CRM solution.

The main entities included:

- Sales
- Inventory
- Supplier
- Customer
- CRM Interaction
- Orders
- Drivers
- Hospital Visits
- Medicines

An **Entity Relationship Diagram (ERD)** was created to show how these entities are connected.

For example:

- Sales records are linked to customers and medicines
- Medicines are linked to suppliers
- Orders are linked to customers and medicine purchases
- CRM interactions are linked to customer queries, complaints, and loyalty activity

This design helped ensure that the Power BI dashboards and Salesforce CRM system were built on a clear data structure.

---

## Solution Architecture

The project follows a complete BI and CRM architecture.

Data is captured from pharmacy operations such as sales, inventory, suppliers, customers, hospital visits, orders, drivers, and CRM interactions. This data is then prepared and used in Power BI dashboards and Salesforce CRM.

The architecture supports:

- Data capture
- Data cleaning
- Data modelling
- Dashboard reporting
- CRM implementation
- Business insight generation
- Decision-making support

### Data Flow Diagram

![image alt](https://github.com/Utkarsh2577/PTU-Pharmacy-To-You-/blob/main/Data%20flow%20diagram.png?raw=true)

---

## Power BI Dashboard Implementation

Four Power BI dashboards were created for this project.

Each dashboard focuses on a different business problem.

---

## 1. PTU Sales Dashboard

The PTU Sales Dashboard focuses on the internal performance of PTU Pharmacy.

It helps analyse:

- Product-wise sales
- Monthly sales trends
- Medicine pricing patterns
- Total stock
- Units sold
- Brand-level performance
- Seasonal sales behaviour
- Stock-out issues
- Impact of shorter working hours

The dashboard revealed that PTU had higher prices compared to competitors, limited discounts, and sales drops during evening hours due to shorter operating times.

### PTU Sales Dashboard

![image alt ](https://github.com/Utkarsh2577/PTU-Pharmacy-To-You-/blob/main/PTU%20Sales%20Dashboard.png?raw=true)

---

## 2. Best Pharma Dashboard

The Best Pharma Dashboard analyses competitor performance.

It helps understand:

- Competitor sales trends
- Pricing strategy
- Discount patterns
- Loyalty point usage
- Product availability
- Customer retention strategy
- Best-selling medicines

This dashboard showed that Best Pharma performed better because of competitive pricing, structured discounts, better product availability, and stronger customer engagement.

### Best Pharma Dashboard

![image alt](https://github.com/Utkarsh2577/PTU-Pharmacy-To-You-/blob/main/BestPharma%20Dashboard.png?raw=true)

---

## 3. Supplier Comparison Dashboard

The Supplier Comparison Dashboard compares vendor performance between PTU Pharmacy and Best Pharma.

It helps analyse:

- Supplier availability
- Supplier count
- Order volume
- Delivery timelines
- Medicine supply consistency
- Brand availability
- Home delivery service availability

The analysis showed that PTU relied on fewer suppliers and had weaker supplier efficiency, while Best Pharma had stronger supplier coverage and home delivery service.

### Supplier Comparison Dashboard

![Supplier Comparison Dashboard](images/supplier_comparison_dashboard.png)

---

## 4. Hospital Conversion Dashboard

The Hospital Dashboard analyses the relationship between hospital visits and PTU Pharmacy customers.

It helps understand:

- Hospital patient visits
- Patients who purchased medicine from PTU
- Patients who did not purchase from PTU
- Department-wise patient visits
- Gender-wise conversion
- Monthly medicine purchase trends
- Patient location mapping

The dashboard revealed that around **70% of hospital visitors were not converting into PTU Pharmacy customers**.

This insight is important because PTU is located inside the hospital but still loses a large number of potential customers to outside pharmacies.

### Hospital Dashboard

![image alt](https://github.com/Utkarsh2577/PTU-Pharmacy-To-You-/blob/main/Hospital%20dashboard.png?raw=true)

---

## Salesforce CRM Implementation

Salesforce CRM was implemented to manage pharmacy operations and customer relationships in a structured way.

The CRM system included custom objects for:

- Customers
- Orders
- Medicines
- Suppliers
- Drivers
- CRM queries
- Loyalty points

The CRM helped PTU Pharmacy move away from manual processes and create a more organized system for customer and operational data.

---

## Medicine Object

A Medicine object was created in Salesforce to store medicine-related information.

It captured:

- Medicine name
- Generic composition
- Usage
- Manufacturer
- Price
- Supplier details

This helped PTU maintain structured medicine inventory records.

![Salesforce Medicine Object](images/salesforce_medicine_object.png)

---

## Supplier Object

A Supplier object was created to manage supplier information.

It captured:

- Supplier name
- Supplier location
- Supplier contact information
- Related medicines

A lookup relationship was created between Medicine and Supplier objects so PTU could track which supplier provides each medicine.

![Salesforce Supplier Object](images/salesforce_supplier_object.png)

---

## Order Object

An Order object was created to manage sales transactions.

It captured:

- Order name
- Order date
- Customer name
- Medicine purchased
- Total price
- Units sold

This allowed PTU to track customer purchase history and sales transactions.

![Salesforce Order Object](images/salesforce_order_object.png)

---

## Customer and Loyalty Management

A Customer object was created to manage customer profiles.

It captured:

- Customer name
- Email
- Phone number
- Address
- Loyalty points

Validation rules were applied to improve data quality for email and phone number fields.

The loyalty points field was added to support future customer retention strategies.

---

## Salesforce Reports and Dashboard

Salesforce reports were created to analyse:

- Medicine sales
- Customer transactions
- Total sales revenue
- Top-selling medicines
- Order records

A Salesforce dashboard was also created to summarize order and sales performance.

![image alt ](images/salesforce_order_report_dashboard.png)

---

## Data Validation and Access Control

To improve CRM data quality, validation and control rules were applied.

Examples include:

- Mandatory fields for order price, medicine name, and customer details
- Supplier information modification restricted to admin users
- SOQL queries used to validate uploaded data
- Data Import Wizard used to upload records into Salesforce

These controls helped maintain clean and reliable CRM data.

---

## Key Business Insights

The project identified several important business insights.

### 1. PTU had weaker sales performance than Best Pharma

Power BI analysis showed that PTU sales were lower compared to Best Pharma due to pricing, limited operating hours, lack of discounts, and weak customer engagement.

### 2. PTU had pricing gaps

The dashboards showed that PTU medicines were priced higher than competitor medicines in several cases.

### 3. Best Pharma had stronger customer retention

Best Pharma used discounts and loyalty points, while PTU did not have a structured loyalty programme.

### 4. PTU had supplier inefficiency

Supplier comparison showed that PTU had fewer suppliers and weaker delivery service compared to Best Pharma.

### 5. PTU had stock availability issues

Seasonal demand patterns showed stock shortages for high-demand medicines such as flu and allergy treatments.

### 6. Hospital visitor conversion was low

The hospital dashboard showed that around **70% of hospital visitors were not PTU customers**, despite the pharmacy being located inside the hospital.

### 7. CRM can improve customer engagement

Salesforce CRM provided a structured way to manage customer records, loyalty points, orders, complaints, and future automated reminders.

---

## Business Impact

This project provides a practical BI and CRM solution that can help PTU Pharmacy:

- Improve sales visibility
- Track stock shortages early
- Compare pricing with competitors
- Improve supplier performance monitoring
- Increase customer retention
- Introduce loyalty programmes
- Improve hospital-to-pharmacy customer conversion
- Manage customer complaints and queries
- Support data-driven decision-making
- Build a foundation for future automation

The project demonstrates how data analytics, BI dashboards, and CRM systems can work together to solve real business problems.

---

## Project Files and Folder Structure

This repository is organized to make the project easy to understand and review.

```text
PTU-Pharmacy-BI-CRM-Integration/
│
├── README.md
│
├── reports/
│   └── Business Intelligence & CRM Integration for PTU Pharmacy.pdf
│
├── powerbi/
│   ├── Final_PTU_sales_Data.pbix
│   ├── Final_BestPHARMADONE.pbix
│   ├── BestPharma Vs PTU Supplier.pbix
│   └── Hospital dashboard.pbix
│
├── images/
│   ├── data_flow_diagram.png
│   ├── er_diagram.png
│   ├── ptu_sales_dashboard.png
│   ├── best_pharma_dashboard.png
│   ├── supplier_comparison_dashboard.png
│   ├── hospital_dashboard.png
│   ├── salesforce_medicine_object.png
│   ├── salesforce_supplier_object.png
│   ├── salesforce_order_object.png
│   └── salesforce_order_report_dashboard.png
│
├── data/
│   ├── ptu_sales_data.csv
│   ├── best_pharma_sales_data.csv
│   ├── supplier_data.csv
│   ├── hospital_visit_data.csv
│   ├── driver_availability_data.csv
│   └── medicine_inventory_data.csv
│
├── salesforce/
│   ├── crm_objects_documentation.md
│   └── validation_rules_and_relationships.md
│
└── docs/
    ├── project_architecture.md
    ├── dashboard_insights.md
    └── future_improvements.md
