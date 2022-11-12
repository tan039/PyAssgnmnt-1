## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans- python is general purpose and high level language because it is easily understood in human readable format and it is interpreted dynamic language that has to be run in the given system using another program instead of its local processor.

Q2. Why is Python called a dynamically typed language?
Ans- It is because the type of variable is determined during runtime. We dont need to define it earlier.

Q3. List some pros and cons of Python programming language?
Ans- PROS:
    1- It's code is easy to read and understand.
    2- It is beginner friendly unlike other languages.
    3- It has extensive support of libraries for data science like numpy, pandas, seaborn, etc.
    4- Python is scalable and portable which means we can write the code once and run it anywhere.
     CONS:
    1- Python is slower than other languages like JAVA, C++ 
    2- Python has high memory consumption and usage.
    3- Python is not so much good for front end and mobile development unlike JAVA,Javascript.
    

Q4. In what all domains can we use Python?
Ans- -> web development
     -> data analysis
     -> machine learning
     -> DevOps and system administration
     -> automated-testing
     -> software prototyping
    
Q5. What are variable and how can we declare them?
Ans- It is a type of container that stores values and here we do not need to declare them earlier it is created once we assign a value. 

Q6. How can we take an input from the user in Python?
Ans- We can do it using the input() function which is inbuilt in python.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans- It is a string type data always.

Q8. What is type casting?
Ans- In python, it is a method to convert the variable datatype in to certain datatype to do some operation.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans- 1) using split()
        Syntax:- input().split(separator, maxsplit)
     2) using List comprehension

Q10. What are keywords?
Ans- In Python, keywords are special reserved words that have specific meanings and can’t be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans- Keywords cannot be used as variable because they are used to define the syntax and structure of the Python language. It will throw an error when keyword and variable have same name.

Q12. What is indentation? What's the use of indentaion in Python?
Ans- Indentation is the spaces at the beginning of code. It is used in python to indicate block of code and if indentation is not done, then it will throw error.

Q13. How can we throw some output in Python?
Ans- It can be done using print().

Q14. What are operators in Python?
Ans- Operators are used to perform operations on variables and values. Various types of operators are,
    - Arithmetic operators
    - Assignment operators
    - Comparison operators
    - Logical operators
    - Identity operators
    - Membership operators
    - Bitwise operators
     
Q15. What is difference between / and // operators?
Ans- / is used for division.
     // the floor division rounds the result down to the nearest whole number 
     
Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans- print(iNeuroniNeuroniNeuroniNeuron)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans-  num = int(input("Enter a number:- "))
      if(num%2) == 0:
        print("num is even")
      else:
        print("num is odd")

Q18. What are boolean operator?
Ans:- Boolean operators are used to return boolean values(i.e., true or false) between two operands.  and, or and not are referred as boolean operators.

Q19. What will the output of the following?
```
1 or 0 = 1

0 and 0 = 0

True and False and True = False

1 or 0 or 0 = 1
```

Q20. What are conditional statements in Python?
Ans- Conditional statements are also known as decision-making statements that helps in controlling the flow of execution of program.
    if statements
    if-else statements
    elif statements
    Nested if and if-else statements
    elif ladder

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans- if- It checks for a given condition, if the condition is true, then the set of code present inside the ” if ” block will be executed otherwise    not.
     elif- It is used to check multiple conditions only if the given condition is false.
     else- The “else” block will execute only when the condition becomes false for if statement.
     
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans- age = int(input("Enter the Age:- "))
     if(age >= 18):
       print("I can vote")
     else:
       print("I can't vote")
       
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans- nos = [12, 75, 150, 180, 145, 525, 50]
     result = 0 
     for i in nos:  
     if not i % 2:  
       result += i
     print("The sum of the even nos is: ", result)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans- num1 = int(input("Enter first number: "))
     num2 = int(input("Enter second number: "))
     num3 = int(input("Enter third number: "))

    if (num1 >= num2) and (num1 >= num3):
       largest = num1
    elif (num2 >= num1) and (num2 >= num3):
       largest = num2
    else:
       largest = num3

   print("The largest number is", largest)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans-  numbers = [12, 75, 150, 180, 145, 525, 50]
    for item in numbers:
        if item > 500:
            break
        elif item > 150:
            continue
        elif item % 5 == 0:
            print(item)