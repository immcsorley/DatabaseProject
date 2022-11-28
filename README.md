## Microsoft Access Database Project for the University of Iowa College of Nursing

## Overview
This is an overview of the Microsoft Access database I built for the University of Iowa's Nursing Residency Program. I was challenged with creating a relational database that made it easier to track customers, sales information, contact information, and be able to easily gain insights for the organization. Over the spring semester in 2022 I learned how to create this database and implement their current data into the database in order to help them analyze and use their data more efficiently. In the end, I was able to cut down over 50% of manual labor hours that were required when doing tasks such as invoicing, reporting, and data collection/entry. 

### Problem Statement
Before the use of Access to store the data for the company, they had numerous microsoft excel sheets that they used to store data. These sheets did not interact with eachother and it was hard and time consuming to update all of them at one time. It was also a very hard and manual process to report on sales numbers, customers, etc. because it took many complicated formulas in different sheets to come out with an end number. 
### Building the database
I first cleaned the data and preprocessed it so that it was ready to be stored in the database. I made sure all customers and invoices were tied together correctly and that each table had a unique identifier. We had a table for customers, site coordinators, invoices, and residents. I then created the database and tables accordingly and made sure the realationship was correct between the tables. Next I build custom forms to be able to add/edit the tables easier without having to find every correct row. I made it easy to create a new invoice for a customer and add new customers to the database.

### Insights for the Company
After the database was completley set up and running, I was able to use the data to create insights for the company. This new database allows to better track the data that they already had. Before, it was a very manual process to look through excel in order to gain insights and change data, now, I have automated many reports and it takes just the click of a button to generate reports for the business.<br/>
These automated reports are built from queries. A few of the reports include: 
- Fiscal Sales Report
- Outstanding Invoices and Amount Outstanding
- Monthly Sales Reports
- Sales and number of residents by organization (customer)
- Organization reports such as completion percentage and how much money recieved from each customer 
- Product reports such as how much money recieved for one product vs another
- Revenue recieved by state
- New Organizations added in the current year

View in [Screenshots](#Screenshots)

### Tracking Customers <br/>
The database also allows for the company to easily search and find customers, view or change data such as contact information, etc. The database also tracks each organization and is linked to other tables such as Invoices, Site Coordinators, and Residents for each customer.<br/>
### Invoicing
I built a form where the user can choose the customer they would like to invoice and input the amount requested along with other details of the sale, and Access will automatically create an invoice by using a template that I made and be ready to email it out to the customer. This is a far quicker process than what the company had been doing in the past. I also created reports that show outstanding invoices information so it is very easy to see who has not paid their invoices yet. 


### Screenshots 
Main Menu Screen (All of the buttons lead to be able to edit/create/delete/add data into whatever table needs it <br/>
![image](https://user-images.githubusercontent.com/90923213/192850991-c051964e-81fa-4d3d-b1f4-8df03762164a.png)

Reports Screen (Consumer can click on any button and instantly view the report) <br/>
![Screenshot 2022-05-05 134740](https://user-images.githubusercontent.com/90923213/167003776-d56b95ec-1e36-4957-a043-fb6f34eebe46.png) <br/>
Example Report (Whiting out $ amount) <br/>

![image](https://user-images.githubusercontent.com/90923213/192851681-26ba92a9-bead-4b45-9e96-3be06be5f8d7.png) <br/>

Example Customer Form (can click on Invoice, Coordinator, Residents to view for that customer) <br/>
![Screenshot 2022-05-05 141550](https://user-images.githubusercontent.com/90923213/167009295-322de63c-1111-4c51-accb-2c2ca00e9e5f.png)<br/>

Example Creating an invoice <br/>
![Screenshot 2022-05-05 141803](https://user-images.githubusercontent.com/90923213/167009590-a0e5549e-4386-4684-9b58-19bc9bf9a9cd.png)<br/>

Example Blank Invoice <br/>
![Screenshot 2022-05-05 141942](https://user-images.githubusercontent.com/90923213/167009842-b922e75e-bff7-486d-b865-e06a531fc09d.png)







