# 📊 Sales Performance Dashboard

[![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?logo=vsc&logoColor=white)](#)
[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=fff)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)

![Screenshot 2025-03-21 at 11 39 40](https://github.com/user-attachments/assets/50c98d00-6004-4cef-b54c-e699560185e5)

## Overview

This Sales Performance Dashboard is a web-based visualization designed to provide in-depth insights into sales data. Built with modern web technologies, the dashboard offers a dynamic and interactive way to analyze sales performance across various dimensions.

## 🌟 Features

### Interactive Dashboard Elements
- **Responsive Design**: Adapts to different screen sizes and devices
- **Year and Product Filters**: Easily filter data by year and product type
- **Reset Filters**: Quick way to return to full dataset view

### Key Visualizations
1. **Summary Cards**
   - Total Revenue
   - Number of Sales
   - Average Order Value
   - Total Tax Collected

2. **Charts**
   - Sales by Product Type (Bar Chart)
   - Customer Gender Distribution (Donut Chart)
   - Sales Trend by Month (Line Chart)
   - Tax Rate Distribution (Pie Chart)

3. **Top Customers Table**
   - Displays top 10 customers by revenue
   - Includes customer details and purchase information

## 🛠 Technologies Used

- **Frontend**: HTML5, CSS3
- **JavaScript Libraries**:
  - Chart.js (Data Visualization)
  - XLSX.js (Excel File Parsing)
  - PapaParse (CSV Parsing)
  - D3.js (Data Manipulation)

## 🚀 How to Use

1. Clone the repository
2. Open the HTML file in a modern web browser
3. Interact with filters and explore the dashboard

### Filter Options
- **Year Filter**: Select specific birth year cohorts
- **Product Filter**: Filter by specific product types
- **Reset Button**: Clear all applied filters

## 📦 Data Requirements

The dashboard expects an Excel file (`random_data_100.xlsx`) with the following columns:
- Birthday
- Salutation
- PurchaseType
- TotalAmount
- TaxAmount
- FirstName
- LastName
- Email
- AddressZipCity

## 🎨 Design Principles

- **Responsive Design**: Mobile and desktop-friendly
- **Color Coded Insights**: 
  - Green for positive changes
  - Red for negative trends
- **Clear Typography**: Easy-to-read font styles
- **Interactive Elements**: Hover effects and tooltips

## 🔧 Customization

You can easily customize the dashboard by:
- Modifying CSS variables in the `:root` selector
- Adjusting chart configurations
- Adding more data processing logic

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📝 Credits

- Sample data from my Geo Profile Generator Project is used for demonstration
- You can replace `random_data_100.xlsx` with your actual sales data

## 📄 License

Distributed under the GNU Affero General Public License v3.0 License. See `LICENSE` for more information.
