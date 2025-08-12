# Project Questions
### Student Discount Application
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

