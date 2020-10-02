TO CHECK WHEATHER A NUMBER IS PRIME OR NOT
==========================================


Also, notice that the boolean variable `isPrime` is initialized to false at the beginning of the program.

Since 0 and 1 are not prime numbers, we first check if the input number is one of those numbers or not. 
If the input number is either 0 or 1, then the value of `isPrime` is set to false.

Else, the initial value of `isPrime` is left unchanged and the for loop is executed, which checks whether the number entered by the user is perfectly divisible by i or not.

The for loop initiates with an initial value of i equals to 2 and increases the value of i by 1 with each iteration.

If the number entered by the user is perfectly divisible by i, then `isPrime` is set to false and the number will not be a prime number.

But if the input number is not perfectly divisible by i throughout the entirety of the loop, then it means that the input number is only divisible by 1 and that number itself.

So, the given number is a prime number.
