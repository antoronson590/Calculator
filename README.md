# Calculator

- To develop a portable algorithm for arithematic calculation application.
- Inital applications are limited to Addition, Subtraction, Multiplication and Division.
- The expression (combination of numbers and symbols) is passed as string input to the program.
- The expression is broken successfully into numbers (double) and symbols( equivalent numbers) and they are stord in separate dynamic arrays. 
  - n- sized array for symbols and n+1 sized array for numbers. 
  - The numbers are initialized as double for ease of operation.
- Since the initial user algorithm failed, Shunting Yard algorithm is being developed to perform calculation. 
