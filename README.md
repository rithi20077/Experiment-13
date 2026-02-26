# Experiment-13
## Pytest Python program for Sum of Digits 
# Aim: 
Step 1: Write the python program for sum of digits of a number. Step 2: Make sure that function name should be “def test_*():” and the line to be tested should have assert keyword at the beginning. Step 3: Write some test cases for to be tested and save it as “test_sumofdig.py”. Step 4: Open command prompt and change the directory to where pytest and program is saved and type “pytest test_sumofdig.py” and run it. Step 5: Stop the program.


# Algorithm
Step 1: Write the python program for sum of digits of a number.
Step 2: Make sure that function name should be “def test_*():” and the line to be tested
should have assert keyword at the beginning.
Step 3: Write some test cases for to be tested and save it as “test_sumofdig.py”.
Step 4: Open command prompt and change the directory to where pytest and program is
saved and type “pytest test_sumofdig.py” and run it.
Step 5: Stop the program. 
# Program: 
```
def sumOfDigits(n): 
    sum = 0 
    while (n != 0): 
        sum = sum + int(n % 10) 
        n = int(n/10) 
    return sum 
def test_1(): 
    assert sumOfDigits(123) == 6 
def test_2(): 
    assert sumOfDigits(256) == 2
```
# Output

<img width="1545" height="596" alt="image" src="https://github.com/user-attachments/assets/316cd5f9-d27a-490b-ab11-fcf2412561c8" />

# Result

Thus, the python program for sum of digits is tested using pytest and executed and output is verified successfully.
