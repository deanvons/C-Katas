# Prime Numbers Further Improved

Prime number: integer number greater than 1, only divisible by 1 and itself

**Goals:**
 - Find all prime numbers below a given upper limit given by the user
 - Check that 2 < upper limit <= 1 million
 - Store prime numbers in an array of 100k integers
 - Optimize the program by using stored prime numbers
 - Compare the execution time of the simple version with the optimized one
 - Implement printing of primes found separately from the algorithm
 - Print up to 50 prime numbers found

**Simple version:**
 - given an input number, n, check whether it is evenly divisible by ANY NUMBER
   between 2 and sqrt(n) (i.e. that the division leaves no remainder)

**Optimized version:**
 - given an input number, n, check whether it is evenly divisible by ANY PRIME NUMBER
   between 2 and sqrt(n) (i.e. that the division leaves no remainder)
