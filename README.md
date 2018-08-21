# Budget Tracker Redux Middleware lab 33

PR: 
---
   This Budget app was created using React and Redux with Redux middleware.  You can set a budget category and add expenses to that category.  Each form takes a name and number input.  
   
   Validation was added to the inputs. If an input is left blank, an alert will display reminding you to add content.  
   
   On submit, it will display the category and budget, or expense and price.  On double clicking the text an update option will display.  You can also delete the entry entirely.  There is no built in persistance so if you refresh the page, its gone.

   Additionally, a `logger` middleware, from the Redux docs, is added to view state changes in the console.