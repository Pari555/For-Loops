## For-Loops

Repeat a set of statements for a __defined__ number of times.

## Formula

```python
for LCV in range():`
  #Body Statement
```

### Loop Control Variable (LCV)
An ordinary variable that is initialized, tested, and changed as the loop executes.

### range() function

1. arguement; range(#) ---> range(stop)
2. arguements; range(#, #) ---> range(start, stop)
3. arguements; range(#, #, #) ---> range(start, stop, step)

__Note__ stop number is exclusive

*Ex.*
range(4) ---> 0,1,2,3
range(3,8) ---> 3,4,5,6,7
range(1,13,3) ---> 1,4,7,10