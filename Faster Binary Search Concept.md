Basically how it works is that it uses a function to approximate the curve of the data and then it will search biased by the function's curve and the difference between the value being compared

### examples:

0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10

find: 1

Binary Search:
```
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10
------------>  ^
      ^ <------o
   ^ <o
```
Naive Search:
```
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10
^  ^
```
Faster Binary Search:
```
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10
------------>  ^
   ^ <---------o
```

Since it's using a linear function. It's pretty straightforward to find 1. 