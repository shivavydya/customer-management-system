Customer Management System (Java + CSV)
📌 Overview
This is a simple Customer Management System built in Java.
It demonstrates:
Reading customer details from a CSV file
Storing them in objects (Customer class)
Managing them using a service layer (CustomerService)
Searching for a customer by name
Displaying all customers
This project is beginner-friendly and helps understand Java OOP, File Handling, and Collections.
📂 Project Structure
CustomerManagement/
│
├── customers.csv         # Data file (customer records)
├── Customer.java         # Model class (represents a customer)
├── CustomerService.java  # Service class (logic to manage customers)
├── Main.java             # Entry point (runs the program)
└── README.md             # Project documentation
🛠 How to Run
1. Clone the Repository
git clone https://github.com/<your-username>/CustomerManagement.git
cd CustomerManagement
2. Compile the Java Files
javac *.java
3. Run the Program
java Main
📊 Sample customers.csv
ID,Name,PhoneNumber
C101,Arjun Sharma,9876543210
C102,Priya Singh,8765432109
C103,Rohan Mehta,7654321098
C104,Sonia Gupta,6543210987
C105,Anjali Verma,9876554321
🎯 Features
✔️ Load customers from a CSV file
✔️ Display all customers
✔️ Search for a customer by name
✔️ Clean OOP structure (Model, Service, Main)
📌 Example Output
Program Started: Customer Management System is running.

ACTION: Loading customers from file: customers.csv...
SUCCESS: Customer data loaded successfully.

--- All Customers in the System ---
Customer [ID=C101, Name=Arjun Sharma, Phone=9876543210]
Customer [ID=C102, Name=Priya Singh, Phone=8765432109]
Customer [ID=C103, Name=Rohan Mehta, Phone=7654321098]
Customer [ID=C104, Name=Sonia Gupta, Phone=6543210987]
Customer [ID=C105, Name=Anjali Verma, Phone=9876554321]
------------------------------------

ACTION: Searching for customer 'Priya Singh'...

SUCCESS: Found the customer!
Customer [ID=C102, Name=Priya Singh, Phone=8765432109]

Program Finished.
🚀 Future Improvements
Add update & delete functionality
Save updated data back to CSV
Add search by phone number or ID
Implement GUI for better interaction
