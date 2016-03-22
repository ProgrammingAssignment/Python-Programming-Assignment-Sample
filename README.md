# Problem 3: Triangular numbers

Use a for loop to compute the 10th triangular number. The nth triangular number is defined as 1+2+3+...+n. (You can also compute the nth triangular number as n*(n+1)/2. Use this formula to double-check that your loop is correct.)

**Hint**: This outline is an almost-complete solution. You only have to replace each ellipsis by an expression.

```python
n = 10
triangular = 0
for i in ...:
    triangular = ...
print "Triangular number", n, "via loop:", triangular
print "Triangular number", n, "via formula:", n*(n+1)/2
```

Your code should correctly calculate the 11th, 12th, or any other triangular number just by changing the first line to set n to 11, 12, or any other number. Using the range function should help you accomplish this.
