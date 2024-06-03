# Us-Mortgage-Title-Search
This is my first project using UiPath RPA
automated the process of searching users in excel sheet having information of three counties's users of Mortgage and verified if the users are present in the same county using their address and saved their property and tax details by creating the folders with their name.

1. developed a main workflow which loops on the excel containing 9 records as customer details 3 for each county.
2. Navigated through 3 counties which are publicly open.
3. Created folders dynamically with time stamp and customer name.
4. developed separate automation workflow for 3 counties.
5. break the address given in the excel file into House number, Street and other parts.
6. invoked county workflow file in the main workflow and connected excel and call particular county in the excel row
