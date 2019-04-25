# New_Group_AD

The code provided was used in my Active Directory class.

This code allows a users to do bulk addition of security groups into a domain from a CSV file with powershell.

The script works by reading in the CSV file, creating variables based on the column names. 

From there the code loops testing to see if the group already exists. If it does, no change. 
If the group does NOT exist it will create the group based on the CSV values.

Code is documented in powershell, please let me know if it does not work or if you have additional questions.
