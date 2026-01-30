Description
-----------
A Python program that approves or rejects a student registration by validating Student ID, Email, Password, and Referral Code based on fixed university rules.

Rules Checked
-------------
Student ID: Starts with CSE, 4th character -, last 3 digits
Email: Contains @, not at start/end, ends with .edu
Password: Minimum 8 characters, starts with uppercase, contains a digit
Referral Code: Starts with REF, next two digits, ends with @

Approach
--------
Inputs are taken as strings
String indexing, slicing, and conditions are used
Each field is validated separately using Boolean variables
Approved only if all validations pass

Output
------
Prints APPROVED if all rules are satisfied
Otherwise prints REJECTED

Language
--------
Python
