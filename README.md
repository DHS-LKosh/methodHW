# methodHW

## Question 1 - Print Times Table
Given an integer, n, **print** a formatted times table from 0 to 13.
```
3 x 0 = 3
3 x 1 = 3
3 x 2 = 6
...
3 x 13 = 39
```


## Question 2 - Calculate Factorial
Given an integer, n, **return** the factorial.
```
factorial(5) --> 120
```


## Question 3 - Max of Three
Write a method that will accept three integers, and return the largest.
```
max3(45, 100, -2) --> 100
```


## Question 4 - Max of Four
Write a method that will return the max of four integers.  Use the method you wrote in question 3 as part of the method body for this question.
```
max4(45, 100, -2, 144) --> 144
```


## Question 5 - Middle Letter
Write a method that will return a char with the middle letter of a String.  If the String has an even number of characters, return the letter to the right of the middle.  You can assume the String will be at least length 1.
```
middle("hello") --> 'l'
middle("five") --> 'v'
```


## Question 6 - Count Words
Write a method that will count the number of words in a String. 
```
countWords("") --> 0
countWords("apple") --> 1
countWords("hello world") --> 2
```


## Question 7 - Password Verifier
Write a method that will determine if a String parameter is a valid password or not.  The rules for passwords are:
  * Must contain a captial letter
  * Must contain a number
  * Must contain a special character (Tricky!)
  * Must contain at least 8 characters
```
isValid("hello") --> false
isValid("Hello123") --> true
isValid("123") --> false
isValid("Ab123") --> false
    
