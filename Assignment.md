PYTHON ASSIGNMENT

PART A

1. Create an empty list and add elements to it using different methods.


```python
languages = []
print(languages)
print()

languages.append("javaScript")
languages.append("Python")
languages.append("C")
languages.append("C++")
languages.insert(1, "Java")
print(languages)
print()

langu_ages = ["MySQL" , "PHP" , "C#" , "JQuery"]
print(langu_ages)
print()

languages.extend(langu_ages)
print(languages)
print()
```

    []
    
    ['javaScript', 'Java', 'Python', 'C', 'C++']
    
    ['MySQL', 'PHP', 'C#', 'JQuery']
    
    ['javaScript', 'Java', 'Python', 'C', 'C++', 'MySQL', 'PHP', 'C#', 'JQuery']
    
    

2. Initialize a list with a sequence of numbers from 1 to 10.


```python
numbers = []
for x in range(1, 11):
    numbers.append(x)
print(numbers)
print()

```

    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    
    

3. Initialize a list with a sequence of even numbers from 2 to 20.


```python
even_numbers = []
for y in range(2 , 21, 2):
    even_numbers.append(y)
    
print(even_numbers)
print()
```

    [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
    
    

4. Create a list containing the names of your favorite fruits.


```python
fruits = ["Mango" , "Apple" , "Passion" , "Bananas" , "Avocado"]
print(fruits)
print()
```

    ['Mango', 'Apple', 'Passion', 'Bananas', 'Avocado']
    
    

5. Access and print the first element of the list.


```python
print(fruits[0])
print()
```

    Mango
    
    

6. Access and print the last element of the list.


```python
print(fruits[4])
print()
```

    Avocado
    
    

7. Access and print a slice of the list containing the first three elements.


```python
print(fruits[0:3])
print()
```

    ['Mango', 'Apple', 'Passion']
    
    

8. Access and print a slice of the list containing the last three elements.


```python
print(fruits[2:5])
print()
```

    ['Passion', 'Bananas', 'Avocado']
    
    

9. Add a new fruit to the list using the `append()` method.


```python
fruits.append("Grapes")
print(fruits)
print()
```

    ['Mango', 'Apple', 'Passion', 'Bananas', 'Avocado', 'Grapes']
    
    

10. Add multiple fruits to the list using the `extend()` method.


```python
fruits_1 = ["Carrots" , "Pineapple" , "Guavas" , "Lemons"]
fruits.extend(fruits_1)
print(fruits)
print()
```

    ['Mango', 'Apple', 'Passion', 'Bananas', 'Avocado', 'Grapes', 'Carrots', 'Pineapple', 'Guavas', 'Lemons']
    
    

11. Insert a fruit at a specific position in the list using the `insert()` method.


```python
fruits.insert(3 , "Cherry")
print(fruits)
print()
```

    ['Mango', 'Apple', 'Passion', 'Cherry', 'Bananas', 'Avocado', 'Grapes', 'Carrots', 'Pineapple', 'Guavas', 'Lemons']
    
    

12. Remove a fruit from the list using the `remove()` method.


```python
fruits.remove("Lemons")
print(fruits)
print()
```

    ['Mango', 'Apple', 'Passion', 'Cherry', 'Bananas', 'Avocado', 'Grapes', 'Carrots', 'Pineapple', 'Guavas']
    
    

13. Remove the last fruit from the list using the `pop()` method.


```python
fruits.pop()
print(fruits)
print()
```

    ['Mango', 'Apple', 'Passion', 'Cherry', 'Bananas', 'Avocado', 'Grapes', 'Carrots', 'Pineapple']
    
    

14. Check if a specific fruit is present in the list using the `in` operator.


```python
if "Cherry" in fruits:
    print("YES, Cherry in fruits.")
    
print()

if "Lemon" not in fruits:
    print("NO, Lemon not in fruits.")
```

    YES, Cherry in fruits.
    
    NO, Lemon not in fruits.
    

15. Find the index of a specific fruit in the list using the `index()` method.


```python
index_of_bananas = fruits.index("Bananas")
print("Index of bananas is: ",index_of_bananas)
print()
```

    Index of bananas is:  4
    
    

16. Sort the list of fruits in alphabetical order using the `sort()` method.


```python
fruits.sort()
print(fruits)
print()
```

    ['Apple', 'Avocado', 'Bananas', 'Carrots', 'Cherry', 'Grapes', 'Mango', 'Passion', 'Pineapple']
    
    

17. Reverse the order of elements in the list using the `reverse()` method.


```python
fruits.sort(reverse=True)
print(fruits)
print()
```

    ['Pineapple', 'Passion', 'Mango', 'Grapes', 'Cherry', 'Carrots', 'Bananas', 'Avocado', 'Apple']
    
    

18. Create a copy of the list using the `copy()` method.


```python
fruits_copy = fruits.copy()
print(fruits_copy)
print()
```

    ['Pineapple', 'Passion', 'Mango', 'Grapes', 'Cherry', 'Carrots', 'Bananas', 'Avocado', 'Apple']
    
    

19. Count the occurrence of a specific fruit in the list using the `count()` method.


```python
fruits_count = ["Mango" , "Apple" , "Passion" , "Mango" , "Bananas" , "Avocado" , "Mango"]
mango_count = fruits_count.count("Mango")
print("Mango occurs ", mango_count ," times." )
```

    Mango occurs  3  times.
    

20. Clear all elements from the list using the `clear()` method.


```python
fruits_count = ["Mango" , "Apple" , "Passion" , "Mango" , "Bananas" , "Avocado" , "Mango"]
print(fruits_count)

fruits_count.clear()
print(fruits_count)
```

    ['Mango', 'Apple', 'Passion', 'Mango', 'Bananas', 'Avocado', 'Mango']
    []
    

# Mathematics Questions(PART B)

1. Write a Python program to calculate the sum of two numbers.


```python
a = 10
b = 5
print(a+b)

print(12+6)
```

    15
    18
    

2. Write a program to subtract two numbers and print the result.


```python
c = 24
d = 8
print(c-d)

print(20-6)
```

    16
    14
    

3. Calculate the product of two numbers and display the output.


```python
e = 8
f = 5
print(e*f)

print(4*6)
```

    40
    24
    

4. Compute the quotient of two numbers using Python.


```python
g = 12
h = 3
i = 10
j = 4

Q = g/h
R = i/j
print(Q)
print(R)
```

    4.0
    2.5
    

5. Write a program to calculate the square of a given number.

# Functions.

# In Python, we define a function using the def keyword followed by the function name and the parentheses containing any parameters the function takes.

def function_name(parameters):
    #Function body
    #Perform actions
    #Return value (optional)
 
Lets break down each part:

     - def: This is the keyword used to define a function in Python.
     -function_name: This is the name of the function. Choose a descriptive name that reflects what the function does.
     -Parameters: These are the inputs that the functions accepts (optional). If the function does not take any parameters, we will need to include empty parentheses ().
     -: :This colon indicates the start of the function body.
     -Function body: This is where you write the code that the function executes. It can contain any valid python code.
     -return Statement (optional): If the function produces a result, we can use the return statementnto send the result back to the code that called the function.
     
     
       


```python
def sum_of_numbers(a,b):
    return a+b

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
print("sum:" , sum_of_numbers(num1, num2))
```


```python
def sub_of_numbers(a,b):
    return a-b

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
print("subtraction:" , sub_of_numbers(num1, num2))
```


```python
def product_of_numbers(a,b):
    return a*b

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
print("product:" , product_of_numbers(num1, num2))
```


```python
def division_of_numbers(a,b):
    return a/b

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
print("divide:" , division_of_numbers(num1, num2))
```


```python
def square_number(x):
    return x * x

num = float(input("Enter a number: "))
print("square:", square_number(num))
```


```python
import math

def square_root(x):
    return math.sqrt(x)

num = float(input("Enter a number: "))
print("Square root:", square_root(num))
```


```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
    
num = int(input("Enter a number: "))
print("Factorial:", factorial(num))
```

    Enter a number: 5
    Factorial: 120
    

# Working with Dictionary.

1. Average of Values: Given a dictionary where the keys are student names and the values
are their exam scores, write a Python function to calculate the average score of all students.


```python
students = {
    "John" : 86,
    "Naomi" : 72,
    "Deborah" : 80,
    "Ayub" : 68,
    "Jonah" : 74
}
no_of_students = len(students.keys())
sum_of_values = sum(students.values())
average_value = (sum_of_values/no_of_students)
print("Average value: ", average_value)
```

2. Maximum Value: Write a Python function to find the student with the highest score in a
dictionary where keys are student names and values are exam scores.


```python
student_with_high_score = max(students, key=students.get)
print("High score:", student_with_high_score , students[student_with_high_score])
```

3. Sum of Values Based on Condition: Write a Python function to calculate the total score
of students who scored above a certain threshold.


```python
threshold = 75
students_above_threshold = {name: score for name, score in students.items() if score > threshold}
for name, score in students_above_threshold.items():
    
    print(name, score)
print()
#Students below threshold.
students_below_threshold = {name: score for name, score in students.items() if score < threshold}
for name, score in students_below_threshold.items():
    
    print(name, score)

```

4. Updating Values: Given a dictionary representing the inventory of items in a store
(where keys are item names and values are quantities), write a Python function to update
the inventory based on a purchase (another dictionary where keys are item names and
values are quantities bought).


```python
inventory_in_store = {
    "Suits" : 23,
    "Shirts" : 15,
    "T-Shirts" : 7,
    "Bow-Tie" : 10,
    "Socks" : 22
}

purchased_inventory = {
    "Suits" : 4,
    "Shirts" : 8,
    "T-Shirts" : 2,
    "Bow-Tie" : 7,
    "Socks" : 22
}

updated_inventory = {}

for item in inventory_in_store:
    if item in purchased_inventory:
        updated_inventory[item] = inventory_in_store[item] - purchased_inventory[item]
    else:
        updated_inventory[item] = inventory_in_store[item]
            
print(updated_inventory)
        
```

# Assignment

1. **Countdown**: Write a Python program that prompts the user to enter a number and then counts down to zero from that number using a `while` loop. For example, if the user enters 5, the program should output: 5, 4, 3, 2, 1, 0.


```python
num = int(input("Enter a number: "))

while num > -1:
    print(num)
    num -= 1
```

    Enter a number: 10
    10
    9
    8
    7
    6
    5
    4
    3
    2
    1
    0
    

2. **Sum of Even Numbers**: Create a Python program that asks the user to input a number and then calculates the sum of all even numbers between 1 and the given number using a `while` loop. For instance, if the user enters 10, the program should compute the sum of 2, 4, 6, 8, and 10, which is 30.



```python
number = int(input("Enter a number: "))

sum_of_even = 0

current_num = 2

while current_num <= number:
    
    sum_of_even += current_num
    current_num += 2

print("The sum of Even Numbers between 1 and", number ,"is: ", sum_of_even)
```

    Enter a number: 20
    The sum of Even Numbers between 1 and 20 is:  110
    

3. **Password Checker**: Develop a Python program that simulates a password checker. The program should prompt the user to enter a password, and it should keep prompting until the correct password is entered. Once the correct password is entered, the program should print a success message.



```python
name = input("Enter Name: ")

password = input("Enter Password: ")

correct_password = "Nairobi123"

while password != correct_password:
    
    print("Access Denied. Try again!")
    password = input("Enter password: ")
    
print("Access Granted")
```

    Enter Name: meshack
    Enter Password: munyalo
    Access Denied. Try again!
    Enter password: Nairobi123
    Access Granted
    

4. **Guessing Game**: Write a Python program that implements a simple number guessing game. The program should generate a random number between 1 and 100, and then prompt the user to guess the number. Provide feedback to the user if their guess is too high or too low, and continue prompting until the correct number is guessed. Once the correct number is guessed, print a congratulatory message along with the number of attempts it took to guess the number.


```python
import random

# Generate a random number between 1 and 100
guess_number = random.randint(1, 100)

# Initialize a variable to count the number of attempts
attempts = 0

# Start the guessing game
print("Welcome to my Number Guessing Game!")
print("I've picked a random number between 1 and 100. Can you guess it?")

while True:
    # Prompt the user to guess the number
    guess = int(input("Enter your guess: "))
    
    # Increment the number of attempts
    attempts += 1
    
    # Check if the guess is correct
    if guess == guess_number:
        print("Congratulations! You've guessed the number", guess_number , "correctly!")
        print("It took you", attempts, "attempts to guess the number.")
        break
    elif guess < guess_number:
        print("Too low! Try again.")
    else:
        print("Too high! Try again.")

```

    Welcome to my Number Guessing Game!
    I've picked a random number between 1 and 100. Can you guess it?
    Enter your guess: 100
    Too high! Try again.
    Enter your guess: 50
    Too low! Try again.
    Enter your guess: 75
    Too high! Try again.
    Enter your guess: 60
    Too high! Try again.
    Enter your guess: 55
    Too low! Try again.
    Enter your guess: 57
    Too high! Try again.
    Enter your guess: 56
    Congratulations! You've guessed the number 56 correctly!
    It took you 7 attempts to guess the number.
    

**Explanation:**

1. Import the `random` module to generate random numbers.

2. Use `random.randint(1, 100`) to generate a random number between 1 and 100 and assign it to `guess_number`.

3. Start a `while` loop that continues indefinitely `(while True)`.

4. Inside the loop:

- Prompt the user to guess the number using `input()`.

- Convert the user's input to an integer using `int()`.

- Increment the `attempts` variable to count the number of attempts.

- Check if the user's guess is correct:

  - If the guess matches the `guess_number`, print a congratulatory message along with the number of attempts and break out of the loop.
  
  - If the guess is too low, print a message informing the user and prompt them to try again.
  
  - If the guess is too high, print a message informing the user and prompt them to try again.

5. **Factorial Calculator**: Develop a Python program that calculates the factorial of a given number using a `while` loop. The program should prompt the user to enter a non-negative integer, and then compute its factorial. The factorial of a number \( n \) is the product of all positive integers less than or equal to \( n \). For example, the factorial of 5 (\( 5! \)) is \( 5 \times 4 \times 3 \times 2 \times 1 = 120 \).


```python
def factorial(n):
    
    while n == 0:
        return 1    # Base case: factorial of 0 is 1
    n > 0
    return n * factorial(n-1)     # Recursive call to calculate factorial

number = int(input("Enter a number: "))

print("Factorial: ", factorial(number))

```

    Enter a number: 6
    Factorial:  720
    


```python

```
