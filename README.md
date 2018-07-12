
LeetCode
===================
> Learning about *Algorithms* by solving [LeetCode](https://leetcode.com/problemset/algorithms/) problems.
>

Two Sum
-------------
> **Directions**
>Given an array of integers, return indices  of the two numbers such that they add up to a specific target.
>You may assume that each input would have  exactly  one solution, and you may not use the  same  element twice.
>
> **Example Output**:
> ```
>// Given nums = [2, 7, 11, 15], target = 9,
>// Because nums[0] + nums[1] = 2 + 7 = 9,
>// return [0, 1].
> ```
>
>**Example Code**:
>```
>var twoSum = function(nums, target) {
>    var result = [];
>    for(var i = 0; i < nums.length; i++) {
>        for(var z = i + 1; z < nums.length; z++) {
>          if(nums[i] + nums[z] === target) {
>              result.push(i);
>              result.push(z);
>          }
>        }
>    }
>    return result;
>};
>```
>
