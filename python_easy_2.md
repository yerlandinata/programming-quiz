# Python: Easy#2

### Instruction
DO NOT:
1. Run the program
2. Google search
2. Using AI to help explaining

If you alredy spent too much time but still don't get it yet, then you can try (1) running the program. Google search is still okay, but don't use AI.

## for loops
### Code#3 
```python
for i in range(5):
    print(i)
```
Output:
```
0
1
2
3
4
```

### Code#4
```python
for i in range(2, 5):
    print(i)
```
Output:
```
2
3
4
```

### Code#5
```python
p = 10                  # Line 1
q = 20                  # Line 2
x = 0                   # Line 3
for i in range(p, q):   # Line 4
    x = i               # Line 5
    print(x)            # Line 6
```
6. What is the output of Code#5?
7. Change Line 3 and Line 5 of Code#5 so that the output becomes:
```
19
18
17
16
15
14
13
12
11
10
```

### Code#6
```python
c = 0
d = 0
for i in range(5, 10):
    c += 1
    for j in range(20, 30):
        d += 1
print(c, d)
```
8. What is the output of Code#6?