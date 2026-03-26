##  Day-5 Moving zeroes

##  Problem link- https://leetcode.com/problems/missing-number/

## Approach

Keep a pointer k for the position to place the next non-zero element.
Traverse the array.
If element is non-zero, place it at nums[k] and increment k
After traversal, fill remaining positions with 0

<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/fd3921dd-2f13-44b3-9e3f-befaadab990c" />
