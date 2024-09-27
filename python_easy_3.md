# Python: Easy#3

### Instruction
DO NOT:
1. Run the program
2. Google search
2. Using AI to help explaining

If you alredy spent too much time but still don't get it yet, then you can try (1) running the program. Google search is still okay, but don't use AI.

### Odd vs Even
`A % B`, reads as `A modulo B`.
```python
print(0 % 2) # output: 0
print(1 % 2) # output: 1
print(2 % 2) # output: 0
print(3 % 2) # output: 1
print(4 % 2) # output: 0
print(5 % 2) # output: 1
print(6 % 2) # output: 0
```
- `N % 2` is equal to `0` if `N` is an `even number`.
- `N % 2` is equal to `1` if `N` is an `odd number`.

### Code#7: Collatz conjecture
```python
N = ...
i = 0
while N != 1:
    print(N)
    if N % 2 == 0:      # even
        N = N // 2
    else:
        N = (3 * N) + 1 # odd
    i += 1

print('N = {}'.format(N))
print('i = {}'.format(i))
```

9. What is the output of the program if:  
   - N = 3
   - N = 10
   - N = 64
   - N = 200
   - N = 10000  
   
10. Give 3 example of N so that i will be equal to 5 at the end of the program.
