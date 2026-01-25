BankIQ_PL-SQL_Enterprise_Banking_Analysis

📌 Project Objective

The objective of this project is to design and analyze a Bank Management System using PL/SQL, focusing on secure data handling, validation, and controlled updates of customer information.
This system helps ensure data integrity, validation-based updates, and efficient account management within a banking database.

🗂️ Dataset Used

Unlike traditional analytical projects, this project does not rely on an external dataset.

✔️ The dataset is created internally within the database using:

Table creation (DDL)

Manual data insertion (DML)

All customer banking records such as Account Number, Name, Mobile Number, Aadhaar, PAN, and Address are stored and managed directly inside the database.

❓ Questions (KPIs)

Does the provided account number exist in the banking system?

Is the mobile number being updated valid (10 digits)?

Is the Aadhaar number valid (12 digits)?

Is the PAN number valid (10 characters)?

Does the address length comply with database constraints before updating?

⚙️ Process

Created the banking database structure using DDL commands.

Inserted customer data manually using DML operations.

Designed a PL/SQL stored procedure to:

Validate account existence

Validate input data length

Perform conditional updates based on user activity

Used DBMS_OUTPUT to display user-friendly messages for every operation.

Implemented exception handling to manage unexpected runtime errors.

🔍 Project Insights

Centralized stored procedures improve data consistency and security.

Input validation prevents incorrect or invalid banking data updates.

Conditional logic ensures only authorized and accurate updates are allowed.

Exception handling enhances system reliability during failures.

PL/SQL is effective for building business-rule-driven database logic.

✅ Final Conclusion

This project demonstrates how PL/SQL can be used to build a robust banking database system that enforces validation, accuracy, and security at the database level.
By using stored procedures and controlled updates, the system minimizes human errors and ensures reliable customer data management.
Such an approach is highly suitable for real-world banking and financial applications where data correctness and integrity are critical.

💡 Tech Stack

Oracle SQL
PL/SQL
