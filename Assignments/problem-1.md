# Solution

```python
class Solution:
    def moveZeroes(self, nums: List[int]) -> None:
        j=0
        n=len(nums)
        for i in range(n):
            if(nums[i]!=0):
                nums[i],nums[j]=nums[j],nums[i]
                j+=1
            
        return nums
```