# Interest Calculator
This Python code calculates the total amount the user would end up with over a number of year at a specified rate.

## How it works
1. The script ask for 3 inputs from the user :
    * **Amount**: the initial amount of money (must be a positive number)
    * **Years**: number of years to invest (must be a positive integer)
    * **Rate**: annual interest rate in decimal (ex: 0.015 for 1.5% interest)

2. It validates the inputs to ensure that the user has respected the correct format (positive numbers,integer or float,...)
3. It will then calculate the total amount using the interest formula :
```python
amount = amount * (1 + rate) ** years
```
4. In the end it prints the final amount with all input taken in account

## How to use it
Run the script in Python in your cmd:

```
python 03b-OPTIONAL_Calculate_interests.ipynb
```