# primality-testing-algorithms
Apply Brute Force and Better Brute Force Algorithms to Primality Testing.

## What Is
Primality testing is the process of determining whether a number is prime or composite.

Small Factor Theorem:  
If N is a composite number, then N has a factor greater than 1 and at most sqrt(N)  

## Brute Force Pseudocode
Input: integer N > 1  
Output: Prime or factors  

For x = 2 through N - 1  
  * if N mod x == 0  
    * Return (x, N/x)  
return Prime  

## Better Brute Force Pseudocode
Input: integer N > 1  
Output: prime or factors  

For x = 2 through floor(sqrt(N))  
  * if N mod x == 0  
    * return (x, N/x)  
return Prime

