# fizzBuzz
To implement the Fizz Buzz problem in JavaScript, we can use a loop to iterate from 1 to N and apply the specified conditions to determine what to print for each number.
Thought Process:

    The function fizzBuzz takes a number N as input and prints the Fizz Buzz pattern for numbers from 1 to N.
    We use a for loop to iterate from 1 to N, inclusive.
    For each number in the loop, we check the following conditions using the % (modulus) operator to determine whether it's a multiple of 3, 5, or both:
        If the number is a multiple of both 3 and 5, we print "Fizz Buzz".
        If the number is a multiple of 3, we print "Fizz".
        If the number is a multiple of 5, we print "Buzz".
        If none of the above conditions are met, we simply print the number.
    The loop continues until it reaches N, printing the appropriate output for each number.

Edge Cases to Consider:

    Non-Positive N: If the input number N is non-positive (less than or equal to 0), the loop won't execute, and nothing will be printed.
    Large N: For very large values of N, the function should execute efficiently and avoid any performance issues.
    In this example, the fizzBuzz function prints the Fizz Buzz pattern for numbers from 1 to 15, according to the specified conditions.
