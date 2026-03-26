##  Day-5 Moving zeroes

##  Problem link- https://leetcode.com/problems/missing-number/

## Approach

Keep a pointer k for the position to place the next non-zero element.
Traverse the array.
If element is non-zero, place it at nums[k] and increment k
After traversal, fill remaining positions with 0


<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/2d8e2140-d3ff-4d9e-bf45-abae23ccda33" />
