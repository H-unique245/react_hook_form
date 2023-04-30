Task

1) Using ReactJS, create a form using React Hook Form for a User Registration Form with
the above fields.
2) Using Yup library, the form should perform the following validations before submission:
   - a) Name, Age, and Sex are required fields. All other fields are optional.
   - b) Mobile & Emergency Contact Number should be a valid Indian mobile number.
   - c) Govt Issued ID:
        - If “ID Type” is Aadhar, then Govt Id should be a valid 12-digit numeric string
        - If “ID Type” is PAN, then Govt Id should be a valid 10-digit alpha-numeric string
3) Make a small backend server with a database. (You can choose any backend &
database technology of your choice)
When you click on SUBMIT, send a POST request to the backend which saves the user details in the database.

4) Create another route page where you fetch and display the list of saved users.
Using Datatables library, show the list of registered users as a datatables table with the
following columns
Name, Age/Sex, Mobile, Address, Govt ID, Guardian Details, Nationality