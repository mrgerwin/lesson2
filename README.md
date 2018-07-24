# lesson2
#Python Data Types

* Clone this repository
* Use the template file coffee.py

* The coffee file contains a function called print receipt that will print a receipt on the screen whenever the function is called.

* It is your job to write the functions that will pass information to print receipt.  And also to call the print receipt function.

* Write a function called customerInput that will ask a customer for her name, the number of coffees wanted, and the number of hot chocolates wanted.  Store the information into Global variables.

* Write a function that will calculate the total cost if the coffee costs $0.25 and the Hot Chocolate costs $0.50.  Add a 18% gratuity.

* Print a receipt on screen for the customer

* Make the program work 3 times for 3 different customers without having the restart the program.

* ________________________________________________
### Discussion Questions
1. What is one reason for using functions?
2. True or False, all function must return a value? Explain.
3. What word must be used so that the function can use and change a variable outside of the function’s scope?
4. What is the result of the code below?

* ________________________________________________

```python  
def printHeader(c):	
	print(c+c+c+c+c+c+c+c+c+c+c+c+c+c+c+c+c+c+c)
	c =input(“What Character for your header?”)
printHeader(c)
printHeader(“*”)
printHeader(‘2’)
```
