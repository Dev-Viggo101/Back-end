# Project Questions
### Student Discount Application (C# Application)
Belgium Campus Cafeteria needs an application that will help them determine the list ofstudents who
have qualified for high performing student discount. Each input record contains the student’s full
name, Residence Student or Not, years on campus, years at current residence, monthly
allowance/salary, average mark across all subjects.

**The functional requirements are given as follows:**

1. Create a method that will capture the student’s details and store them in an appropriate collection.
- Make sure the data has been formatted appropriately to be saved on the collection.
- Your method should return the collection.
- Allow users to input as many students’ data as they want until they press N for No or Y for
Yes if asked if “they still want to capture any more applicants”.

2. Create a method that uses the method you used to capture details (that returned a collection) for
each applicant and determine if they qualify for the discount or not.
*The cafeteria grants discount if the student:*
- Is a residence student and has stayed on campus for more than a year
- If the student has an overall average of over 85%
- However, the discount is denied if a student gets a monthly allowance of more than R1000.
  
- The applicants who qualify for the discount must be stored in a collection.
- Count the number of applicants that were granted the discount, also the number of those
whose discount was denied.

3. Create a method that will display the discount qualification stats as mentioned in the above scenario.
   
4. Create an Enum(Menu) to allow the user to choose what they want to do given the following
options:
- Capture Details
- Check discount qualification
- Show qualification stats
- Exit the program

---
### Meal Planning and Ordering (C# OOP Application)
As the Belgium Campus expands, many of its functions are being outsourced to independent
organizations. One such area is the campus kitchen, which is partly managed by the Belgium Campus
and partly by an independent entity named BC-Eats. As an intern, you have been tasked with
developing an OOP application to manage meal planning and ordering for students and lecturers

**Application Requirements**

Create a menu using ENUM for the following options: 

1. Register
2. View registered members
3. Place an order
4. View placed orders
5. Exit

Description of Menu Options:

- Register: Users can register members by providing relevant details. Both lecturers and
students should be registered in the system.
- View registered members: Users can view all registered members.
- Place an order: Users can place orders for registered members, specifying whether the order
is for a student or a lecturer.
- View placed orders: Users can view all placed orders.
- Exit: Allows the user to exit the application.

---
### Library Management System (Java Application (MVC Architecture))
Create a Java application using the Model-View-Controller (MVC) design pattern by
organizing your code into three main components.

**The Library Management System using MVC architecture should have the following package
structure:**

- librarysystem.model - Contains data models.
- librarysystem.view - Contains view classes for the user interface.
- librarysystem.controller - Contains controller classes for business logic and interaction
between the model and view.

---
### ATM Simulator (C# Application)
You are building a console-based ATM system where a user can log in with basic credentials (like account number + PIN), then perform actions like:

- Check balance

- Deposit money

- Withdraw money

All account information (account number, name, PIN, balance) will be stored in a text file so that the data persists after the program closes.

**Features To Implement:**

1. Login System

- Prompt the user for account number + PIN.

- Verify against stored accounts in the text file.

- If correct → allow access, else deny.

2. Main Menu (once logged in)

- 1️⃣ Check Balance

- 2️⃣ Deposit

- 3️⃣ Withdraw

- 4️⃣ Exit

3. Check Balance

- Display current balance of logged-in user.

4. Deposit

- Ask user for deposit amount.

- Add it to balance.

- Update text file.

5. Withdraw

- Ask user for withdrawal amount.

- Check if balance is sufficient.

- Deduct if valid, else show error.

- Update text file.

6. Exit

- Save any changes back to the text file.

- Log out user safely.

**A simple text file (accounts.txt) could store accounts like this:**

- 1001,John Doe,1234,5000
- 1002,Jane Smith,5678,3000
- 1003,Bob Lee,4321,10000
  
Account Number, Name, Pin, Balance

You’ll need to:
- Read from the file at the start (load into memory).
- Write back updates (like balance changes) after transactions.

---
### Student's Grade Manager (C# Application)
A console app where you can add students with their grades, save them to a text file, and later read and display them.

**Features:**

- Add Student: Enter student name + grade → save to file.
- List Students: Read file → show all students + grades.
- Search Student: Enter a name → find and show grade (if exists).
- Exit.

**A simple text file (students.txt) could store data like this:**

- John Doe,85
- Jane Smith,90
- Michael Johnson,75

---

