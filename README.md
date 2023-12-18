# customer_banking
Customer Banking System - Module 3 Challenge: Columbia University AL/ML Bootcamp
## Overview
This is a customer banking system allowing user to input current balance, interest rate and months to determine new balance and interest earned on Savings Account or Certificate of Deposit (CD). This is the third challenge for Columbia University AL/ML Bootcamp.
### System Features
**Input**
  - Balance: Customer's current balance
  - Interest Rate: Interest Rate offered by the banking institution
  - Maturity: Number of months the balance will be deposited with the bank

**Process**
  - Calculate interest earned for entered months and balance
  - Calculate new balance based on interest earned and starting balance

**Output**
  - New balance
  - Intrest earned for entered months
### Syntax
The program uses the Object Oriented Programming (OOP) concept to develop the solution. 
  - Class Account is created to:
      1. set balance
      2. set interest
  - Function create_savings_account is created to:
      1. Import Account class (and create an instance)
      2. Calculate interest eraned
      3. Update the savings account balance by adding the interest earned
      4. Pass the updated balance to the set balance method
      5. Pass the interest earned to the set interest method
      6. Return balance and interest earned
  - Funtion create_cd_account is created to:
      1. Import Account class (and create an instance)
      2. Calculate interest eraned
      3. Update the CD account balance by adding the interest earned
      4. Pass the updated balance to the set balance method
      5. Pass the interest earned to the set interest method
      6. Return balance and interest earned
  - A main function is created to:
      1. Import create_savings_account
      2. Import create_cd_account
      3. Prompt the user to set the savings balance, interest rate, and months for the savings account
      4. Call the create_savings_account function and pass the variables from the user
      5. Print the interest earned and updated savings account balance with interest earned for the given months
      6. Prompt the user to set the CD balance, interest rate, and months for the CD account
      7. Call the create_cd_account function and pass the variables from the user
      8. Print out the interest earned and updated CD account balance with interest earned for the given months
