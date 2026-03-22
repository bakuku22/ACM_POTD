##  Day-1 Remove duplicates from sorted array

##  Problem link- https://leetcode.com/problems/remove-duplicates-from-sorted-array/

## Approach

Created a dictionary to store key value pairs in which key is the element and value is the frequeny of that
element in the nums array.
Then traversed the dictionary and removed all those elements from nums array (frequency-1) times so that 
only unique elements remained in the array.

## Code (Python)

class Solution(object):
2    def removeDuplicates(self, nums):
3        di={}
4        for i in range(0,len(nums)):
5            if nums[i]in di:
6                di[nums[i]]+=1
7            else:
8                di[nums[i]]= 1
9        for j in di:
10            if di[j]>1:
11                for m in range(1,di[j]):
12                    nums.remove(j) 
13        k=len(nums)
14        print(k,nums)


<img width="718" height="856" alt="Screenshot 2026-03-22 at 6 20 30 PM" src="https://github.com/user-attachments/assets/20da2d4a-b4d4-4494-955c-a306e1d1afeb" />

