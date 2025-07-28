## Problem

**What will be the output of the following pseudocode for `a=8` and `b=8`?**

```pseudo
Integer funn(Integer a, Integer b)
    if(a && b && a+b >0)
      return a+funn(a-2, b-2) + b
    End if
    return a^b
  End function funn()
```

---

## Options

- A. 39  
- B. 46
- C. 48 
- D. 40

---

## Approach

- a=8, b=8, a+b=16 => it will return 8 + funn(6,6) + 8
- a=6, b=6, a+b=12 => it will return 6 + funn(4,4) + 6
- a=4, b=4, a+b=8 => it will return 4 + funn(2,2) + 4
- a=2, b=2, a+b=4 => it will return 2 + funn(0,0) + 2
- Total sum = 16 + 12 + 8 + 4 = 40

## Correct Answer: **40**
