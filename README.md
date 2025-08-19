# LEET-CODES-ODD25
Bagupadipondi.....Enjoyy Fandagawww

# LEET-CODE-SOLS:
*EASY & Med QUESTIONS*

### 1st  two lines (Predefined Function) avasaram ledu chadivi waste eh... 

## WEEK 1:  Pascal's Triangle (Easy)
```
class Solution:
    def generate(self, numRows):
        triangle = [[1]]
        for _ in range(numRows - 1):
            triangle.append([x + y for x, y in zip([0] + triangle[-1], triangle[-1] + [0])])
        return triangle
```
## WEEK 1:   (Med)
```

```
### Ipoindi le ika lev
