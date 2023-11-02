# Crowdfunding_ETL
I followed the following step in jupyter notebook:

# Converted the data into a DataFrame

# Created the Category and Subcategory DataFrames
A "category_id" column that is numbered sequential form 1 to the length of the number of unique categories.
A "category" column that has only the categories.

1. Extracted and transformed the crowdfunding.xlsx Excel data to create a category and sub category DataFrame
2. Exported the category DataFrame and sub category DataFrame as category.csv and subcategory.csv and then saved it to my GitHub repository.
3. A "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories

4. A "subcategory" column that contains only the subcategory titles

# Category  
<img width="191" alt="Screenshot 2023-11-01 at 8 36 36 PM" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/7634e97b-d366-4a9c-aea9-c129e873d85e">

# Subcategory
<img width="309" alt="Screenshot 2023-11-01 at 8 36 56 PM" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/15a95e75-fd1a-4255-b0b6-a1c2da278378">

# Created the Campaign DataFrame

1. Extracted and transformed the crowdfunding.xlsx Excel data to create a campaign DataFrame
2. Exported the ca	mpaign DataFrame  as campaign.csv and then saved it to my GitHub repository.
   The "cf_id" column

. The "contact_id" column

. The "company_name" column

. The "blurb" column, renamed to "description"

. The "goal" column, converted to the float data type

. The "pledged" column, converted to the float data type

. The "outcome" column

. The "backers_count" column

. The "country" column

. The "currency" column

. The "launched_at" column, renamed to "launch_date" and with the UTC times converted to the datetime format

. The "deadline" column, renamed to "end_date" and with the UTC times converted to the datetime format

. The "category_id" column, with unique identification numbers matching those in the "category_id" column of the category DataFrame

. The "subcategory_id" column, with the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame

. The following image shows this campaign.csv exported

<img width="999" alt="Screenshot 2023-10-31 at 2 18 59 PM" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/c0b5cc17-1241-4724-8d0d-1af75e9f25f6">

Created the Contacts DataFrame

1. Extracted and transformed the crowdfunding.xlsx Excel data to create a contacts DataFrame
2. Exported the contacts DataFrame  as contacts.csv and then saved it to my GitHub repository. I have tried both the following options and successfully exported csv file.
* Option 1: Use Python dictionary methods.
* Option 2: Use regular expressions.

<img width="730" alt="Screenshot 2023-10-31 at 2 18 28 PM" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/98a201ed-b4b0-4b60-8e14-800c2906514f">

# Create the Crowdfunding Database

1. Sketched an ERD of the tables by using QuickDBD
2. Saved the database schema as a Postgres file named crowdfunding_db_schema.sql, and save it to my GitHub repository.

<img width="639" alt="Screenshot 2023-11-01 at 8 18 58 PM" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/60e68ce5-afd2-47d0-8532-667889e1b2d1">

3. Created a new Postgres database, named crowdfunding_db. Imported csv files and verified that each table has correct data. Also provided the screenshoot of successful SQL imports in my repository for reference.

# Category 

<img width="416" alt="Screenshot category" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/05697867-177f-4b7e-853b-131bc3f94ee4">

# Subcategory
<img width="419" alt="Screenshot subcategory" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/4580b9d8-90e0-42e8-964e-26f1e3acac49">

# Contacts
<img width="676" alt="Screenshot contacts" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/4cfe051e-b28d-451d-89ee-b125cdbf03b3">

# Campaign
<img width="720" alt="Screenshot campaign" src="https://github.com/aamanhassan/Crowdfunding_ETL/assets/139508376/451885d1-08ce-4ae9-9ecb-3ce28dc5fedc">




