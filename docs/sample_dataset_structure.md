# Sample Dataset Structure

This document describes the **structure of the datasets** required for the Predictive Analytics project.  
Each dataset corresponds to a **category** (e.g., Retail, Healthcare, Manufacturing, Finance, Education, Marketing).

---

## 1. Retail
**Entities:** Customer, Transaction, Product  
**Attributes per Entity:**
- **Customer:** customer_id, name, age, gender, location, loyalty_score
- **Transaction:** transaction_id, customer_id, product_id, transaction_date, amount
- **Product:** product_id, category, price, stock_units

**Sample Data (CSV format):**
```csv
customer_id,name,age,gender,location,loyalty_score
C001,John Smith,35,M,New York,82
C002,Mary Jones,29,F,California,74

