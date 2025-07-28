## Problem

**What will be the output of the following pseudo code for `w = 40` and `x = 4`?**

```pseudo
void fun(Integer w, Integer x)
    Integer y
    Set y = 0
    if (x mod w EQUALS 0 || w mod x EQUALS 0)
        y = y + 1
    Else
        y = y + 10
    End if
    Print y
End function fun()
```

---

## Options

- A. 1  
- B. 11  
- C. 10  
- D. 2  

---

## Approach

Given w=40 and x=4
  - x % w => 40 % 4 == 0
  - if condition satisfied so y becomes 1.


## Correct Answer: **1**
