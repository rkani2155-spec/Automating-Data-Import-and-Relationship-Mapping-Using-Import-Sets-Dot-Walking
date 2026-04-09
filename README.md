Automating Data Import and Relationship Mapping Using Import Sets & Dot Walking

📌 Project Overview

This project focuses on automating data import in ServiceNow using Import Sets and Transform Maps, and then building relationship mapping between tables using Reference Fields and Dot Walking.
The main goal is to reduce manual data entry, improve accuracy, and enable easy access to related information across multiple tables.

🎯 Objectives

Import external data (Excel/CSV) into ServiceNow using Import Sets.
Transform imported data into target tables automatically.
Create relationships between tables using reference fields.
Use dot walking to retrieve related table data easily.
Ensure proper data validation and error handling.

🛠️ Tools & Technologies Used

ServiceNow Platform
Import Sets
Transform Maps
Data Sources (CSV/Excel)
Reference Fields
Dot Walking
Business Rules (optional)
Script Includes (optional)

📂 Modules Covered

1. Data Source Creation
Create a Data Source in ServiceNow.
Upload CSV/Excel file.
Define format and delimiter settings.
2. Import Set Table
ServiceNow automatically creates an Import Set Table.
Imported data is stored temporarily for transformation.
3. Transform Map
Create a Transform Map to map Import Set fields to target table fields.
Perform field mapping and data conversion.
Use scripts for advanced transformation if required.
4. Relationship Mapping
Reference fields are used to connect tables.
Example: Linking an Employee table to Department table.
5. Dot Walking
Used to fetch values from referenced tables.

Example:

JavaScript
employee.department.manager_name

🔄 Workflow of the Project

Upload CSV/Excel file into ServiceNow.
Data gets stored in an Import Set Table.
Transform Map transfers data into the Target Table.
Reference fields create relationships between records.
Dot walking retrieves related information easily.

🧾 Example Scenario

Tables Used:
Employee Table
Department Table
Relationship:
Employee table contains a reference field to Department table.
Dot Walking Example:
To get department name from Employee record:
JavaScript
current.department.name

⚙️ Features

✅ Automated import of large datasets
✅ Accurate field mapping using Transform Maps
✅ Relationship creation using reference fields
✅ Easy access to related fields using dot walking
✅ Reduced manual work and errors

🧪 Testing

Test Cases:
Verify file upload and import process.
Check Import Set data accuracy.
Validate transformation into target tables.
Confirm relationships are properly created.
Test dot walking functionality in forms and reports.

📊 Expected Output

Imported data successfully available in target tables.
Proper relationships between records (Employee ↔ Department).
Dot walking displays related data correctly in forms/reports.

🚀 Future Enhancements

Add automated scheduled imports.
Add data validation using Business Rules.
Create dashboards for imported data monitoring.
Implement error logging and rollback mechanism.

👥 Team Details

Project Name: Automating Data Import and Relationship Mapping Using Import Sets & Dot Walking
Team ID: SWTID-2026-3651

📌 Conclusion

This project demonstrates an efficient way to import and manage large datasets in ServiceNow. By using Import Sets, Transform Maps, Reference Fields, and Dot Walking, the system ensures automation, relationship mapping, and fast access to linked data.

Project Demonstration video 

https://drive.google.com/file/d/1QFK1mfEplWq1pQlGauYyO-hA7qtK7pUx/view?usp=drivesdk
