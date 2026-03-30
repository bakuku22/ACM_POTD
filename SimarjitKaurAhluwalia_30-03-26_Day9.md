## Day 9- Linked list cycle
## Problem link-https://leetcode.com/problems/linked-list-cycle/

## Approach:

Make an unordered set visited in which we add all the visited nodes.
Till head is not equal to null, each head is checked if it exists in the visited set.
If it does, then it's a cycle.
If not, head points to the next node.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b75b6cf8-ef48-4c08-b2e8-807a616e7b4f" />
