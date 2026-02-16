# Experiment 7: Study of Loops in Python

 Introduction / Theory

Loops are fundamental control structures in Python that allow repeated execution of a block of code as long as a specified condition is true. They help automate repetitive tasks and make programs efficient and concise.

Python primarily provides two types of loops:

* **while loop** – Executes a block of code as long as a condition remains true.
* **for loop** – Iterates over a sequence (not used heavily in this experiment but conceptually related).

This experiment focuses mainly on the **while loop**, along with the use of:

* `break` statement
* `continue` statement
* Loop control variables
* Logical conditions

These programs demonstrate practical applications of loops such as factorial calculation, Fibonacci series generation, palindrome checking, digit counting, and searching elements in a list.

---

 List of Programs Performed

1. Print numbers from 1 to 5
2. Print numbers from 1 to N
3. Find factorial of a number
4. Generate Fibonacci series (two variations)
5. Reverse a number
6. Check palindrome (number)
7. Check palindrome (string – slicing method)
8. Check palindrome (string – two-pointer method)
9. Count number of digits in a number
10. Search an element in a list
11. Print odd numbers using `continue`

---

 1. Print Numbers from 1 to 5

 Algorithm

1. Initialize `i = 1`
2. While `i <= 5`:

   * Print `i`
   * Increment `i` by 1

---

 2. Print Numbers from 1 to N

 Algorithm

1. Input value of `N`
2. Initialize `i = 1`
3. While `i <= N`:

   * Print `i`
   * Increment `i`

---

 3. Factorial of a Number

 Algorithm

1. Input number `n`
2. Initialize `fact = 1`
3. While `n > 0`:

   * Multiply `fact` by `n`
   * Decrement `n`
4. Print factorial

---

 4. Fibonacci Series (First N Terms)

 Algorithm

1. Input number `n`
2. Initialize `a = 0`, `b = 1`
3. Repeat `n` times:

   * Print `a`
   * Compute next term `c = a + b`
   * Update `a = b`, `b = c`

---

 5. Fibonacci Series (Up to Limit)

 Algorithm

1. Input limit value
2. Initialize `a = 0`, `b = 1`
3. While `a <= limit`:

   * Print `a`
   * Update `a, b = b, a + b`

---

 6. Reverse a Number

 Algorithm

1. Input number `num`
2. Initialize `rev = 0`
3. While `num > 0`:

   * Extract last digit using `num % 10`
   * Append digit to `rev`
   * Remove last digit using integer division
4. Print reversed number

---

 7. Palindrome Check (Number)

 Algorithm

1. Store original number in `temp`
2. Reverse the number using loop
3. Compare reversed number with original
4. If equal → Palindrome
5. Else → Not palindrome

---

 8. Palindrome Check (String – Slicing Method)

 Algorithm

1. Input string
2. Reverse string using slicing `[::-1]`
3. Compare original and reversed strings
4. Print result

---

 9. Palindrome Check (Two-Pointer Method)

 Algorithm

1. Initialize two pointers: start and end
2. While start < end:

   * Compare characters
   * If mismatch → Not palindrome
   * Move pointers inward
3. If loop completes → Palindrome

---

 10. Count Number of Digits

 Algorithm

1. Input number
2. Initialize `count = 0`
3. While number > 0:

   * Increment count
   * Remove last digit
4. Print count

---

 11. Search an Element in a List

 Algorithm

1. Define list of numbers
2. Input element to search
3. Initialize index `i = 0`
4. While `i < length of list`:

   * If element found → Print index and break
   * Else increment `i`
5. If loop ends without break → Element not found

---

 12. Print Odd Numbers Using Continue

 Algorithm

1. Initialize `i = 0`
2. While `i < 10`:

   * Increment `i`
   * If `i` is even → continue
   * Else print `i`

---

 Conclusion

Through this experiment, we studied the working of **while loops in Python** and understood how repetition is controlled using conditions. We also explored practical applications such as factorial calculation, Fibonacci series generation, palindrome checking, digit counting, and searching techniques.

This experiment strengthens logical thinking and builds a solid foundation for advanced programming concepts like nested loops, recursion, and algorithm desi
