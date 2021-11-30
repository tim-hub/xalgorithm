# Two Sum

```javascript
var twoSum = function(nums, target) {
    
    // brute force
    for (let i =0; i< nums.length; i++ ) {
        
        let i1 = i;
        let tmpTarget = target - nums[i];
        
        for (let j = i+1; j< nums.length; j++) {
            if (nums[j] === tmpTarget) {
                return [i,j];
            }
        }
    }
};
```
