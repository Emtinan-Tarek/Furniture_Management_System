# Furniture_Management_System

SRS Document Template
(2) – Furniture Store Management System
T.A: Dr. Nagwa Moustafa
Group Members and sections:
1.	SWE Sec 3: Emtinan Tarek Ahmed
2.	SWE Sec 3: Heba Magdy Mostafa
3.	SWE Sec 3: Nada Yosri Ramadan
4.	SWE Sec 3: Mayada Mohamed Zain
5.	SWE Sec 3: Yara Ahmed Mohamed
6.	AI Sec 1: Abdelrahman Maged Zaki
7.	AI Sec 1: Adham Khaled Ali
 
# 1. Introduction

This section should describe the need for the system. It should briefly describe the system’s functions
and explain how it will work with other systems. It should also describe how the system fits into the
overall business or strategic objectives of the organization commissioning the software.
# 2. Context Diagram

This section presents the context diagram for the system that identifies the flows of information between
# 3. User Requirements

5)	The FMS (Furniture Management System) shall generate reports showing the number of sold items, the type of sold items and the profit as well as a report showing products less than certain quantities weekly.
6)	The Admin shall be able to delete products, check reports, approve of new suppliers. 
7)	The Client shall be able to search and select products as many as they want to buy and be able to pay in either cash or visa.
8)	The Client shall be able to send complaints and inquiries.
9)	The Supplier and the Client both shall be able to create accounts.
10)	The Supplier shall be able to Deliver customized and non-customized products to the suppliers’ manager.
11)	The Admin and Customer Support shall be able to manage the Customers’ complaints and inquiries.
12)	The Custom Orders Manager shall be able to receive custom orders from clients and send them to suppliers.
13)	The Suppliers’ Manager shall be able to track product’s quantity report, determine needed products and report them to the suppliers.
14)	The Suppliers’ Manger shall be able to manage The Suppliers delivery times and receive the products.
# 4. Functional Requirements

1)	Name: Client Account Registration.
Description: This function creates accounts for clients.
Inputs: - Name
-	Password
-	Email
-	Phone Number
-	Address
Source: The Client
Pre: All constraints are satisfied.
Post: An account for the client will be created and recorded in the system database.
Output: A massage saying the account has been successfully created and logs the client into the system.
2)	 Name: Product searching
Description: This function helps the user search for specific items on the system
Inputs: Searching criteria.
Source: The Client.
Pre: User enters searching criteria.
Post: Finds the items entered by the user in the database.
Output: Display the items searched for or “item is not found”.
3)	Name: Filing Complaints
Description: This function helps the user contact support for any issue.
Inputs: Support ticket.
Source: The client.
Pre: Client not satisfied.
Post: Sends the complaints information to the Customer Support.
Output: Displays a massage confirming the arrival of such complaint with an expected reply date.

4)	Name: Custom Product Request
Description: This function allows the client to send custom orders to the Custom Order Manager to send them to the Suppliers.
Inputs: The clients custom order preferences?
Source: The client
Pre: Client uses Select Product function
Post: Sends custom order request to the Custom Order Manager
Output: Display a massage stating that the order has been successfully received
5)	Name: Select Product
Description:  This Function allows the client to choose products or custom products.
Inputs: Items the client willing to purchase
Source: The Client 
Pre:  
Post: Calculates expenses
Output: Displays items selected and total price.
# 5. Non-Functional Requirements

1)	Acceptability: The system should be easy to use by the suppliers and clients without any previous knowledge. The system should be easy to use by Managers, Admins, and Employees after a 2-hour training session.
2)	 Usability: The screens prompting the user for different input should clearly state what the user should input.
3)	 Security: The system shall protect the customer's privacy by preventing any private info leakage.
4)	 Reliability: The system should be capable to handle many users without affecting its performance.
5)	Efficiency: Response time of events promoted by user should be less than 0.5 seconds. The system shall not exceed a storage of 2GB.

