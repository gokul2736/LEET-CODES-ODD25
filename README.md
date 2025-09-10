# LEET-CODES-ODD25 SOLS:

*EASY & Med QUESTIONS*

### 1st  two lines (Predefined Function) 

## WEEK 1:  Pascal's Triangle (Easy)

```python
class Solution:
    def generate(self, numRows):
        triangle = [[1]]
        for _ in range(numRows - 1):
            triangle.append([x + y for x, y in zip([0] + triangle[-1], triangle[-1] + [0])])
        return triangle
```
## WEEK 1:   (Med) 

```python3
from typing import List

class Solution:
    def minMoves(self, nums: List[int]) -> int:
        return sum(nums) - min(nums) * len(nums)

```


## WEEK 2: Happy Number (Easy)

```python3
class Solution:
    def isHappy(self, n: int) -> bool:
        seen=set()
        while n!=1 and n not in seen:
            seen.add(n)
            n=sum(int(c)**2 for c in str(n))
        return n==1
```


### Ipoindi le ika lev
Bagupadipondi.....Enjoyy Fandagawww
