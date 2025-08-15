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
