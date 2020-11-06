# simple-spring-boot-api-expensetracker

This simple restAPI is organized that follows:
- controller
  - ExpenseControler
- model
  - Expense
- repository
  - ExpenseRepository
- service
  - ExpenseService
  - ExpenseServiceImpl  
  

The requests you can make are the follow:
 - *Get* - localhost:8080/api/v1/expenses/
 
 - *Post* - localhost:8080/api/v1/expenses/
   Ex json:
     {
      "expense": "Now Dell Experience",
      "amoung": 5000.00,
      "description": "A new dell experience"
    }
 
 - *Get* - localhost:8080/api/v1/expenses/{id}
 
 - *Delete* - localhost:8080/api/v1/expenses/{id}
