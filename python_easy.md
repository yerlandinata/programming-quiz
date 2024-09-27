# Python: easy

### Instruction
First, try not to:
1. Run the program
2. Google search
2. Using AI to help explaining

When you think you've already spent so much time but still don't get it yet, try (1) first, and then if still not enough try (2), and then (3).

### Code#1
```python
array = [1, 2, 3, 4] # line 1
                     # line 2
if len(array) < 4:   # line 3
    print("ok")      # line 4
else:                # line 5
    print("not ok")  # line 6
```

1. What is the output of Code#1
2. Change line 1 so that the output of Code#1 becomes different.
3. Write one line of code in line 2 so that the output of the code becomes different. Revert the previous change you've made.

### Code#2
```python
x = 100                             # Line 1
y = 2000                            # Line 2
                                    # Line 3
is_near_mountain_peak = False       # Line 4
                                    # Line 5
mountain_peak_x = 200               # Line 6
mountain_peak_y = 1500              # Line 7
                                    # Line 8
# Note: abs(1) = 1, abs(-1) = 1     # Line 9
dist_x = abs(x - mountain_peak_x)   # Line 10
dist_y = abs(y - mountain_peak_y)   # Line 11
                                    # Line 12
naive_dist = dist_x + dist_y        # Line 13
                                    # Line 14
if dist < 1000:                     # Line 15
    is_near_mountain_peak = True    # Line 16
                                    # Line 17
print(is_near_mountain_peak)        # Line 18
```

4. Output of Code#2?
5. Modify Line 1 to change the output of the program.