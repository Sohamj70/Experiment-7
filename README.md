### **Experiment 7**
### _**AIM**_
To study and implement the while loop in Python by solving different problems such as printing numbers, factorial calculation, Fibonacci series generation, reversing numbers, checking palindrome, counting digits, searching elements, and printing odd numbers.

### **_THEORY_**
- A while loop in Python is a control structure used to execute a block of statements repeatedly as long as a given condition is true.
- The condition is evaluated before each iteration of the loop.
- If the condition is true, the loop body is executed; if false, the loop terminates.
- Initialization of loop variables is required before entering the loop.
- The loop variable must be updated inside the loop to avoid infinite looping.
- The while loop is used when the number of iterations is not known in advance.
- Conditional statements can be used inside the while loop for decision making.
- Control statements like break and continue can be used to control loop execution.
### **_ALGORITHM_**
Algorithm 1: Print Numbers Using While Loop
1. Start
2. Initialize a variable i = 1
3. Use while i <= n:
4. Print the value of i
5. Increment i using i = i + 1
6. Stop

Algorithm 2: Factorial of a Number
1. Start
2. Read the number n
3. Initialize fact = 1
4. Use while n > 0:
5. Multiply fact = fact * n
6. Decrement n = n - 1
7. Display factorial
8. Stop

Algorithm 3: Fibonacci Series

1. Start
2. Initialize a = 0, b = 1, and counter i = 1
3. Use while i <= n:
4. Print a
5. Compute next term c = a + b
6. Update a = b, b = c
7. Increment counter
8. Stop

Algorithm 4: Reverse of a Number
1. Start
2. Read number n
3. Initialize rev = 0
4. Use while n > 0:
5. Get last digit using n % 10
6. Update rev = rev * 10 + digit
7. Reduce number using n = n // 10
8. Display reversed number
9. Stop

Algorithm 5: Palindrome Check
1. Start
2. Read number n and store copy temp = n
3. Reverse the number using while loop
4. Compare rev with temp
5. Display whether palindrome or not
6. Stop

Algorithm 6: Count Number of Digits
1. Start
2. Read number n
3. Initialize count = 0
4. Use while n > 0:
5. Increment count
6. Divide number using n = n // 10
7. Display count
8. Stop

Algorithm 7: Search an Element

1. Start
2. Read list and element to search
3. Initialize index i = 0
4. Use while i < length:
5. Compare element with list item
6. If found, display position and exit loop
7. Increment index
8. Stop

Algorithm 8: Print Odd Numbers
1. Start
2. Initialize variable i = 1
3. Use while i <= n:
4. Print i if i % 2 != 0
5. Increment i
6. Stop

### _**CONCLUSION**_
Thus, the experiment was successfully performed and the concept of the while loop in Python was understood. Different problems were solved using the while loop, which helped in understanding looping, condition checking, and variable updating.
