# Solution

```python
class Solution:
    def firstUniqChar(self, s: str) -> int:
        j=0
        for i in s:
            if s.count(i)==1:
                return s.index(i)
        else:
            return -1
```