The pharmacy database is designed to manage various aspects of a pharmacy's 
operations, including staff management, product inventory, customer 
information, supplier details, and transaction records. Here's a breakdown of each 
table:

1. Staff: Stores information about pharmacy staff including their ID, name, job 
title, salary, commission, hire date, address, and phone number.

2. Category: Contains categories for products available in the pharmacy, 
identified by a unique category ID. Each category has a name and an optional 
description.

3. Customer: Holds details about customers who visit the pharmacy, including 
their ID, name, and phone number.

4. Supplier: Stores information about suppliers who provide products to the 
pharmacy, including their ID, company name, supplier name, address, and phone 
number.

5. Product: Contains details about the products available in the pharmacy, such 
as their ID, name, supplier ID, category ID, quantity, and unit price. It includes 
foreign key constraints referencing the Category and Supplier tables.

6. Transaction: Records transactions made at the pharmacy, including the 
transaction ID, customer ID, staff ID, and transaction date. It includes foreign key 
constraints referencing the Customer and Staff tables.

7. TransactionDetails: Contains detailed information about each transaction, 
including the transaction ID, product ID, unit price, quantity, and discount. It 
includes foreign key constraints referencing the Transaction and Product tables.

Overall, the pharmacy database facilitates efficient management of staff, 
products, customers, suppliers, and transactions, providing a comprehensive 
system for running a pharmacy business effectively.
