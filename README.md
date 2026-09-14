# CSCI161-CH05-EXAMPLES
Examples from Data Structures and Algorithms in Java
### EX5_01 — Factorial.java

This example introduces recursion with the factorial function. It is a good first example because the pattern is simple: multiply a number by the factorial of the next smaller number until the program reaches the stopping case.

What to watch for:

- How the problem gets smaller at each step.
- Where the base case occurs.
- How recursive calls build the final answer.

### EX5_02 — Ruler.java

This example usually shows how recursion can create repeated visual patterns. Instead of solving only a numeric problem, it demonstrates that recursion is also useful for structured output.

What to watch for:

- How one larger pattern is made from smaller patterns.
- Why recursive drawing or printing often has a “middle” step between recursive calls.
- How a short method can produce surprisingly complex output.

### EX5_03 — BinarySearch.java

This example applies recursion to searching in a sorted collection. Binary search is important because it shows how recursion can make an algorithm much more efficient by cutting the problem in half each time.

What to watch for:

- Why the data must be sorted first.
- How the method decides whether to search the left half or the right half.
- How the stopping cases work when the item is found or not found.

### EX5_04 — DiskSpace.java

This example likely explores recursive traversal of a file structure to compute total disk usage. It is a practical example of recursion because folders can contain files and also other folders, which makes the problem naturally recursive.

What to watch for:

- How the program treats a file differently from a directory.
- How the total is built from smaller pieces.
- Why recursion is a natural fit for nested structures.

### EX5_06 — ArraySum.java

This example uses recursion to find the sum of values in an array. It helps connect recursion to arrays and shows how even familiar iterative tasks can be written recursively.

What to watch for:

- How the method reduces the array problem to a smaller subarray or smaller index range.
- What value should be returned in the base case.
- How the partial sums combine into the final result.

### EX5_07 — ArrayReverse.java

This example shows how recursion can reverse the contents of an array. It is useful for seeing how two positions can be handled at a time while the recursive call moves inward.

What to watch for:

- Which elements are swapped first.
- How the recursive call works on a smaller section of the array.
- When the program knows it is finished.

### EX5_08_09 — Power.java

This example works with exponentiation and may include more than one recursive strategy. It can help show the difference between a direct recursive solution and a more efficient one.

What to watch for:

- The basic recursive definition of powers.
- Whether the exponent decreases by 1 or is reduced more quickly.
- How recursive design can affect efficiency.

### EX5_12 — Unique3.java

This example likely checks whether three values are all different. In Chapter 5, this kind of example is often used to compare a straightforward solution with a recursive or algorithmic idea in a small, easy-to-test setting.

What to watch for:

- What “unique” means in the context of the method.
- How the logic compares the values.
- Whether the example is mainly about recursion or about problem decomposition.

### EX5_14 — Fibonacci.java

This example uses the Fibonacci sequence, one of the most common recursion examples. It is helpful for understanding recursion, but it also shows that a recursive solution is not always the most efficient choice.

What to watch for:

- The two base cases needed for Fibonacci.
- How one call can create multiple additional calls.
- Why this example is often used to discuss recursive inefficiency.