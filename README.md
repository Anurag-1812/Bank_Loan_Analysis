# Bank Loan Analysis Project

A comprehensive data analytics project focused on analyzing bank loan performance, customer demographics, and loan portfolio insights using Power BI, SQL, and financial datasets.

## 📊 Project Overview
This project demonstrates an end-to-end Business Intelligence solution using **MS SQL Server, Power BI, and CSV data**.

The goal was to analyse bank loan applications and repayments to answer key business questions:
- How many loans are approved, funded, and paid? 
- What is the overall loan health (default vs. fully paid vs. current)? 
- Which customer and regional factors affect loan performance? 

The outcome is an interactive Power BI Dashboard that provides actionable insights for risk assessment, portfolio monitoring, and decision-making.

## 📌 Problem Statement  
Banks issue thousands of loans every year, but not all of them perform well. Some loans default, while others are repaid successfully.  

The objective of this project is to **analyze bank loan data** and build an **interactive Power BI dashboard** that provides insights into:  
- Loan approval, funding, and repayment trends  
- Borrower demographics & financial stability  
- Loan portfolio health (default vs. fully paid vs. current)  
- Factors influencing loan risk and profitability
## 🗂️ Project Structure

```
├── 📂 CSV File
│   └── financial_loan.csv              # Primary dataset containing loan records
├── 📂 Dashboard
│   ├── Bank loan.pbix                  # Power BI dashboard file
│   ├── Bank-Icon-PNG-HD.png           # Branding asset for dashboard
│   └── 📂 Dashboard SS                 # Dashboard screenshots
│       ├── Details.png                # Detailed analytics view
│       ├── Overview.png               # High-level overview dashboard
│       └── Summary.png                # Summary statistics view
├── 📂 Problem Statement PPT
│   └── Bank Loan Analysis PPT Power BI.pptx  # Project presentation
├── 📂 SQL Query
│   └── bank_loan_analysis_query.docx  # SQL queries for data analysis
└── README.md                          # Project documentation
```

## 🎯 Key Features

### Dashboard Components
- **Overview Dashboard**: High-level KPIs and performance metrics
- **Summary Dashboard**: Aggregated statistics and trends
- **Details Dashboard**: Granular loan-level analysis

### Analysis Areas
- Loan approval rates and patterns
- Risk assessment and default analysis
- Customer demographic insights
- Loan amount distribution and trends
- Geographic analysis of loan performance
- Time-series analysis of loan applications

## 📋 Prerequisites

### Software Requirements
- **Power BI Desktop** (latest version recommended)
- **Microsoft Excel** or compatible CSV reader
- **SQL Server** or compatible database (for SQL queries)
- **PowerPoint** (for presentation viewing)

### Technical Skills
- Basic understanding of Power BI
- SQL query knowledge
- Data analysis fundamentals
- Financial domain knowledge (recommended)

## 🚀 Getting Started

### 1. Data Setup
```bash
# Clone or download the project files
# Ensure all files maintain the directory structure shown above
```

### 2. Power BI Dashboard
1. Open `Dashboard/Bank loan.pbix` in Power BI Desktop
2. Refresh data connections if prompted
3. Verify that the CSV file path is correctly linked
4. Explore the three main dashboard views:
   - Overview
   - Summary  
   - Details

### 3. Data Analysis
1. Review the SQL queries in `SQL Query/bank_loan_analysis_query.docx`
2. Execute queries against your database for custom analysis
3. Use the CSV file for additional data exploration

## 📊 Dashboard Highlights  
✅ **Overview Page** – KPIs (Total Applications, Funded Amount, Received Amount, Avg. Interest Rate, DTI)  
✅ **Summary Page** – Loan status breakdown (Fully Paid, Current, Charged Off) with trends  
✅ **Details Page** – Borrower demographics (Employment length, Purpose, Grade, Home ownership, Income levels)  
✅ **Interactive Filters** – Year, Loan Status, State, Purpose, Grade, Sub-grade  

---

## 📷 Dashboard Preview  

### 🔹 Overview  
![Overview](https://github.com/Anurag-1812/Bank_Loan_Analysis/blob/main/Dashboard/Dashboard%20SS/Overview.png)  

### 🔹 Summary  
![Summary](https://github.com/Anurag-1812/Bank_Loan_Analysis/blob/main/Dashboard/Dashboard%20SS/Summary.png)  

### 🔹 Details  
![Details](https://github.com/Anurag-1812/Bank_Loan_Analysis/blob/main/Dashboard/Dashboard%20SS/Details.png)

## 🔍 Key Metrics Analyzed

- **Total Loan Applications**: Volume of loan requests
- **Total Funded Amount**: Amount successfully disbursed
- **Total Amount Received**: Payments collected
- **Average Interest Rate**: Portfolio interest rate trends
- **Average DTI (Debt-to-Income)**: Risk assessment metric
- **Good Loan vs Bad Loan Percentage**: Portfolio quality indicators

## 📈 Business Insights

This analysis helps answer critical business questions:
- Which loan purposes have the highest approval rates?
- What are the characteristics of high-risk borrowers?
- How do seasonal trends affect loan applications?
- Which geographic regions show the best performance?
- What factors contribute to loan defaults?

## 🛠️ Customization

### Adding New Metrics
1. Modify SQL queries in the query document
2. Update Power BI measures and calculated columns
3. Refresh dashboard visualizations

### Data Updates
1. Replace `financial_loan.csv` with updated data
2. Maintain the same column structure
3. Refresh Power BI data model

## 📁 File Descriptions

| File/Folder | Description |
|-------------|-------------|
| `financial_loan.csv` | Primary dataset with loan records |
| `Bank loan.pbix` | Interactive Power BI dashboard |
| `Bank-Icon-PNG-HD.png` | Logo/branding for dashboard |
| `Dashboard SS/` | Screenshots of dashboard views |
| `Bank Loan Analysis PPT Power BI.pptx` | Project presentation |
| `bank_loan_analysis_query.docx` | SQL queries for analysis |

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test dashboard functionality
5. Submit a pull request

## 📝 Notes

- Ensure data privacy compliance when working with financial data
- Regularly backup your Power BI file before making changes
- Validate data accuracy after any modifications
- Consider data refresh schedules for production use

## 📞 Support

For questions or issues:
1. Check the SQL query documentation
2. Review Power BI connection settings
3. Verify CSV data format and structure
4. Consult the presentation for business context

Feel free to connect with me:  

- 💼 [LinkedIn](https://www.linkedin.com/in/anurag-pandey-daofficial/)  
- 📧 imanurag1812@gmail.com  

## 📄 License

This project is for educational and analytical purposes. Ensure compliance with data governance policies when using with real financial data.

---

**Last Updated**: September 2025  
**Version**: 1.0  
**Power BI Version**: Compatible with Power BI Desktop latest version
