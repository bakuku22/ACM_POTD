## Day 8- Reverse Linked List
## Problem link-https://leetcode.com/problems/reverse-linked-list/

## Approach:

Start with two pointers:
prev = NULL, curr = head
Traverse the list:
Save next node - next = curr->next
Reverse link - curr->next = prev
Move pointers - prev = curr, curr = next
At the end prev becomes the new head of the reversed list

<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/13bc1574-0d5d-4c2d-bc68-be79f05754d3" />
