# Customer Purchase Data Analysis using Pandas

## Overview
This repository contains an in-depth analysis of customer purchase data using Python Pandas library. The analysis explores customer demographics, transaction details, and purchasing behaviors to derive meaningful insights. 

## Dataset Description
The dataset consists of **30,000 customer purchase records**, containing structured records detailing customer demographics, transaction amounts, and payment methods.

- 📊 **Total Entries**: 30,000  
- 🏷️ **Total Columns**: 20  
- 🔢 **Column Types**:  
  - Integer (`int64`): 2  
  - Float (`float64`): 1  
  - String (`object`): 17  
- 💾 **Memory Usage**: 4.6+ MB

### **Columns in the Dataset**

#### **Customer Information**
- **Personal Details**: `first`, `last`, `age`, `gender`, `profession`, `company`
- **Contact Information**: `phone`, `email`, `province`, `postal`

#### **Transaction Details**
- **Spending**: `price(CAD)`
- **Purchase Timing**: `weekday`
- **AM/PM**: `ampm`

#### **Payment Information**
- **Card Details**: `cc_no`, `cc_type`, `cc_exp`

#### **Additional Attributes**
- **Email Prefix**: `prefix`
- **Favorite Color**: `fav_color`
- **Internet Protocol Address**: `ip`


## Files in the Repository
- **`Customer_Purchase_Analysis.ipynb`** - Jupyter Notebook containing the full data analysis.
- **`Cust_Purch_FakeData.csv`** - The dataset used for the analysis.
- **`README.md`** - This file, providing an overview of the repository.



## Installation & Requirements
To run the analysis, ensure you have the following dependencies installed:

### **Required Libraries**
```bash
pip install pandas numpy
```

### **Running the Analysis**
1. Clone this repository:
   ```bash
   git clone https://github.com/arannoX/superstore_sales_data_analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd superstore_sales_data_analysis
   ```
3. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On macOS/Linux
   env\Scripts\activate     # On Windows
   pip install -r requirements.txt
   ```
4. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open `Customer_Purchase_Analysis.ipynb` and execute the cells.


## **Key Insights:**

1. **Customer Age Statistics**:
   - 📈 **Maximum Age**: 65 years  
   - 📉 **Minimum Age**: 18 years  
   - 📊 **Mean Age**: 41.55 years  
   - The dataset represents a diverse age group, with an average customer age of ~41.55 years.

2. **Most Common Names**:
   - The three most frequently occurring customer names in the dataset:
     - **Willie**: 130 occurrences
     - **Francis**: 124 occurrences
     - **Eula**: 86 occurrences
   - This insight helps businesses personalize marketing strategies and customer engagement.

3. **Duplicate Phone Numbers**:
   Duplicate phone numbers were found in the dataset, which may indicate shared accounts, data inconsistencies, or fraudulent activity. For instance, the phone number **(263) 382-8004** appears twice, associated with two different customers:
   - **Lilly Tyler** (Female, 38 years old, Structural Engineer at CSX Corp.)
   - **Peter Cain** (Male, 27 years old, Insurance Adjuster at Campbell Soup Co.)
   
   Investigating such anomalies can help improve data integrity and prevent potential fraud.

4. **Profession Distribution**:
   - Helps in understanding profession categories for targeted marketing.
   - **Total Structural Engineers**: 87 customers. 
   - This insight allows businesses to tailor advertisements and offers based on profession-specific behaviors.

5. **Total Male Structural Engineers**: 43 customers.

6. **Female Structural Engineers in Alberta (AB)**:
   - The dataset contains **4 female Structural Engineers** from Alberta.
  
7. **Spending Statistics**:
    - **Max. Spending**: 100.0 CAD
    - **Min. Spending**: 0.0 CAD
    - **Avg. Spending**: 49.99 CAD

8. **Customers Who Didn't Spend Anything - Special Deals Needed!**
   - **Dr. Bruce Bryan** (Male, 59, Engineer Technician at Wal-Mart Stores Inc.)
   - **Mrs. Flora Clark** (Female, 27, Cruise Director at MetLife Inc.)
   - **Company wants to send a deal to encourage the customer to buy stuff!**

9. **Customers Who Spent 100 CAD or More - Loyalty Reward Coupons!**
   - **Mrs. Gregory Brown** (Female, 31, Novelist at E*Trade Group, Inc.)
   - **Mrs. Cody Christensen** (Male, 28, Hospital Administrator at National City Corp.)
   - **Miss Lizzie Dixon** (Female, 38, Compensation Analyst at FleetBoston Financial Co.)
   - **Company wants to send a thanks coupon to those who spent 100 CAD or more, as a loyalty reward!**

10. **Email Accounts Associated with a Specific Credit Card**
   - **Credit Card Number:** `5020000000000230`
   - **Emails Associated:**
     - **sebvajom@kol.km**
     - **acu@jatsot.ug**

11. **Credit Cards Expiring in 2019 - Need Replacement Cards!**
    The company identified **2,684 credit cards** that are set to expire in 2019.
    
12. **How Many People Use Visa as Their Credit Card Provider?**
    - **Total Visa Credit Card Users**: 1,721 customers.

13. **Customers Who Spent 100 CAD Using Visa**:
    - **Customer Identified:** Mrs. Gregory Brown, 31, Novelist at E*Trade Group, Inc.

14. **Most Common Professions**:
    - **Preschool Teacher**: 112 occurrences.
    - **Distribution Manager**: 107 occurrences.

15. **Top 5 Most Popular Email Providers**:
    - **gmail.com**: 1,687 users.
    - **me.com**: 1,676 users.
    - **outlook.com**: 1,664 users.
    - **live.com**: 1,660 users.
    - **hotmail.com**: 1,659 users.

16. **Customers Using "am.edu" Email**: 1 customer found.
     - **Emails Associated:**
       - **barit@am.edu**

17. **Most Popular Shopping Day**: **Saturday** (4,376 customers).


## Conclusion
The analysis provides valuable insights into customer demographics, spending behaviors, and transaction patterns.
