## ODD TRIANGLE SUM

Given the triangle of consecutive odd numbers:

             1
          3     5
       7     9    11
   13    15    17    19
21    23    25    27    29
...

Calculate the row sums of this triangle from the row index (starting at index 1) e.g.:
```py
row_sum_odd_numbers(1); # 1
row_sum_odd_numbers(2); # 3 + 5 = 8
```

#### Most accepted solution
```py
def row_sum_odd_numbers(n):
    return n ** 3
```
that is clear smart move. Understand the property of the sum.

also have a look at this solution ,Findind a equation for the first element and
last element.
```py
def row_sum_odd_numbers(n):
    #your code here
    a,b = n*(n-1)+1,n*(n+1)
    return sum(range(a,b,2)) if a != 1 else 1
```
