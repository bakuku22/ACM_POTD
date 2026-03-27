##  Day-6 Check N and Double

##  Problem link- https://leetcode.com/problems/check-if-n-and-its-double-exist/

## Approach

Make an unordered set seen.
Traverse through the array and for each element check:
1) if its double exists in the array
2) if it's even, its half exists in the array
If any one of these is satisfied, true is returned, if not the element is added to the seen set using insert.

If these aren't satisfied for any element in the array, false is returned.


<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/b5721fe3-c2e1-4826-aaa9-8448063fb833" />
